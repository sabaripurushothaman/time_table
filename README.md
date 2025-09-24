# Ex03 Time Table
# Date: 24.09.2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Timetable</title>
  <style>
    table {
      border-collapse: collapse;
      width: 100%;
      text-align: center;
    }
    th, td {
      border: 2px solid black;
      padding: 10px;
    }
    th {
      background-color: rgb(177, 190, 53);
      color: rgb(247, 246, 246);
    }
    .vertical-word {
      background-color: rgb(123, 136, 51);
      font-weight: bolder;
      text-align: center;
      vertical-align: middle;
      width: 50px;
      font-size: 18px;
    }
    .vertical-word span {
      display: block;
      line-height: 1.8;
    }
    h2{
      text-align: center;
      margin-top: 10px
    }
    h3{
      text-align: center;
    }
  </style>
</head>
<body>
  <div style="text-align: center; margin: 15px 0;">
    <img src="/static/logo.png" height="110" width="540">
  </div>

  <h2>SAVEETHA ENGINEERING COLLEGE</h2>
  <H3>SLOT TIME TABLE - <span style="color:rgb(18, 176, 34)"> P.S.SABARI - (25013745)</span></H3>
  <table>
    <tr>
      <th>Day/Time</th>
      <th>08:00-10:00</th>
      <th>10:00-12:00</th>
      <th class="vertical-word" rowspan="7">
        <span style="color: black;">L</span>
        <span style="color: black;">U</span>
        <span style="color: black;">N</span>
        <span style="color: black;">C</span>
        <span style="color: black;">H</span>
      </th>
      <th>13:00-15:00</th>
      <th>15:00-17:00</th>
    </tr>
    <tr>
      <td>Monday</td>
      <td>FWAD</td>
      <td>PYTHON</td>
      <td>FREE SLOT</td>
      <td>FREE SLOT</td>
    </tr>
    <tr>
      <td>Tuesday</td>
      <td>FCC</td>
      <td>FCC</td>
      <td>FREE SLOT</td>
      <td>FREE SLOT</td>
    </tr>
    <tr>
      <td>Wednesday</td>
      <td>FWAD</td>
      <td>FWAD</td>
      <td>MENTOR MEET</td>
      <td>PYTHON</td>
    </tr>
    <tr>
      <td>Thursday</td>
      <td>PYTHON</td>
      <td>PYTHON</td>
      <td>FCC</td>
      <td>FREE SLOT</td>
    </tr>
    <tr>
      <td>Friday</td>
      <td>FREE SLOT</td>
      <td>FWAD</td>
      <td>FREE SLOT</td>
      <td>PYTHON</td>
    </tr>
    <tr>
      <td>Saturday</td>
      <td>FCC</td>
      <td>FWAD</td>
      <td>FREE SLOT</td>
      <td>FREE SLOT</td>
    </tr>
  </table>
  <H3></H3>
  <table>
    <tr>
      <th>S.NO</th>
      <th>Subject Code</th>
      <th>Subject Name</th>
    </tr>
    <tr>
      <td>1</td>
      <td>19AI414</td>
      <td>Fundamentals of Web Application Development(FWAD)</td>
    </tr>
    <tr>
      <td>2</td>
      <td>19AI301</td>
      <td>Python Programming(PYTHON)</td>
    </tr>
    <tr>
      <td>3</td>
      <td>19CS547</td>
      <td>Fundamentals of Crypto Currency(FCC)</td>
    </tr>
  </table>
</body>
</html>
```

# OUTPUT
![alt text](<Screenshot 2025-09-24 110901.png>)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
