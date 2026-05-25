<!DOCTYPE html>
<html>
<head>
<title>Student Registration Website</title>

<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background-color:#fff8dc;
}

header{
    background-color:blue;
    color:white;
    text-align:center;
    padding:20px;
}

.container{
    width:50%;
    margin:30px auto;
    background:white;
    padding:25px;
    border-radius:10px;
    box-shadow:0px 0px 10px gray;
}

h2{
    text-align:center;
    color:blue;
}

label{
    font-weight:bold;
}

input[type=text],
textarea,
select{
    width:100%;
    padding:8px;
    margin-top:5px;
    margin-bottom:15px;
    border:1px solid gray;
    border-radius:5px;
}

.buttons{
    text-align:center;
}

input[type=submit],
input[type=reset]{
    padding:10px 20px;
    border:none;
    border-radius:5px;
    cursor:pointer;
    font-size:16px;
}

input[type=submit]{
    background-color:green;
    color:white;
}

input[type=reset]{
    background-color:red;
    color:white;
}

footer{
    text-align:center;
    background-color:blue;
    color:white;
    padding:10px;
    margin-top:20px;
}
</style>

</head>

<body>

<header>
<h1>Student Registration Portal</h1>
</header>

<div class="container">

<h2>Registration Form</h2>

<form>

<label>Student Name:</label>
<input type="text">

<label>Father's Name:</label>
<input type="text">

<label>Age in Years:</label>
<input type="text">

<label>Gender:</label><br>
<input type="radio" name="gender"> Male
<input type="radio" name="gender"> Female
<br><br>

<label>Address:</label>
<textarea rows="4"></textarea>

<label>Activities:</label><br>
<input type="checkbox"> Chess <br>
<input type="checkbox"> Basketball
<br><br>

<label>Enroll for Class:</label>

<select>
<option>Class 1</option>
<option>Class 2</option>
<option>Class 3</option>
<option>Class 4</option>
<option>Class 5</option>
<option>Class 6</option>
<option>Class 7</option>
<option>Class 8</option>
</select>

<div class="buttons">
<input type="submit" value="SUBMIT">
<input type="reset" value="RESET">
</div>

</form>

</div>

<footer>
© 2026 Student Registration Website
</footer>

</body>
</html>
