<!DOCTYPE html>
<html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Library Books Management</title>

<style>
body{
    font-family: Arial, sans-serif;
    background-color:#f4f4f4;
}

form{
    width:400px;
    margin:auto;
    background:white;
    padding:20px;
    border-radius:5px;
}

input, select, textarea{
    width:100%;
    padding:6px;
    margin-top:5px;
}

input[type="radio"]{
    width:auto;
}

input[type="submit"], input[type="reset"]{
    background-color:#4CAF50;
    color:white;
    margin-top:15px;
    cursor:pointer;
}
</style>
</head>

<body>

<form>

Name:<br>
<input type="text" name="name" placeholder="Enter your name"><br><br>

Roll No:<br>
<input type="text" name="rollno"><br><br>

Gender:<br>
<input type="radio" name="gender" value="male"> Male
<input type="radio" name="gender" value="female"> Female<br><br>

Email ID:<br>
<input type="email" name="email"><br><br>

Password:<br>
<input type="password" name="password"><br><br>

College Name:<br>
<input type="text" name="college"><br><br>

Department:<br>
<select>
<option>CSE</option>
<option>IT</option>
<option>ECE</option>
<option>EEE</option>
<option>AIML</option>
<option>AIDS</option>
<option>Mechanical</option>
<option>Civil</option>
<option>Mechatronics</option>
</select><br><br>

Address:<br>
<textarea rows="5"></textarea><br><br>

<input type="submit" value="Submit">
<input type="reset" value="Reset">

</form>

</body>
</html>
