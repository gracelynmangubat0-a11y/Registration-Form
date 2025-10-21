<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width", initial-scale=1.0>
  <title>Students Registration Form</title>
  <style>
  body {
    font-family: Arial, san-serif;
    background: white;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh
  }
  .form-container {
    background: white;
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    width: 400px;
  }
  .form-container h2 {
    text-align: center;
    margin-bottom: 50px;
    color: blue;
  }
  label {
    font-weight: bold;
    margin-top: 20px;
    display: block;
  }
  input, select, textarea {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    margin-top: 15px;
    border: 1px solid #ccc;
    border-radius: 6px;
    font-size: 15px;
  }
  button {
    width: 100%;
    padding: 12px;
    background: #4CAF50;
    border: none;
    color: white;
    font-size: 16px;
    border-radius: 6px;
    cursor: pointer;
  }
  button:hover {
    background: #45a049;
  }
  </style>
</head>
<body>
  <div class="form-container">
    <h2 style="background-color:yellow; text-align: center;">LLCC REGISTRATION FORM</h1>
    <form action="#" method="post">
      <hr>
      
      <label for="schoolid">School Id:</label>
      <input type="drop" id="drop" name="drop" required>
      
      <label for="fullname">Full Name:</label>
      <input type="text" id="fullname" name="fullname" required>
      
      <label for="email">Email Address:</label>
      <input type="email" id="email" name="email" required>
      
      <label for="phone">Phone Number:</label>
      <input type="tel" id="phone" name="phone" required>
      
      <label for="dob">Date Of Birth:</label>
      <input type="date" id="dop" name="dop" required>
      
      <label for="gender">Gender</label>
      <select id="gender" name="gender" required>
        <option value="">--Select--</option>
        <option value="male">Male</option>
        <option value="female">Female</option>
        <option value="gay">Gay</option>
        <option value="bisexual">Bisexual</option>
      </select>
      
      <label for="address">Address:</label>
      <input type="add" id="add" name="add" required>
      
      <label for="zipcode">ZIP Code:</label>
      <input type="code" id="code" name="code" required>
      
      <label for="course">Course / Program</label>
      <select id="course" name="course" required>
        <option value="">--Select--</option>
        <option value="BEEd">Bachelor of Elementary Education</option>
        <option value="BSEd">Bachelor of Secondary Education</option>
        <option value="BindTech">Bachelor of Information Technology (CompTech)</option>
        <option value="BindTech">Bachelor of Information Technology (Electronics)</option>
        <option value="BSHM">Bachelor of Science In Hospitality Management</option>
        <option value="BSTM">Bachelor of Science In Tourism Management</option>
        </select>
      
      <label for="schedule">Preferred Schedule</label>
      <select id="schedule" name="schedule" required>
        <option value="">--Select--</option>
        <option value="morning">Morning</option>
        <option value="afternoon">Afternoon</option>
        <option value="evening">Evening</option>
      </select>
      
      <hr>
      
    <h2 style="background-color:Yellow; text-align: center;">OTHER INFORMATION</h1>
      
      <label for="fathername">Father's Name:</label>
      <input type="father" id="father" name="father" required>
      
      <label for="occ">Occupation:</label>
      <input type="occ" id="occ" name="occ" required>
      
      <label for="phone">Phone Number:</label>
      <input type="tel" id="phone" name="phone" required>
      
      <label for="address">Address:</label>
      <input type="add" id="add" name="add" required>
      
      <label for="mothername">Monther's Name:</label>
      <input type="mother" id="mother" name="mother" required>
      
      <label for="occ">Occupation:</label>
      <input type="occ" id="occ" name="occ" required>
      
      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" name="phone" required>
      
      <label for="address">Address:</label>
      <input type="add" id="add" name="add" required>
      
      <hr>
        
      <button type="submit">Register</button>
    </form>
  </div>
</body>
</html>
