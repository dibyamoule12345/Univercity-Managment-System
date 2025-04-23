<!DOCTYPE html> 
<html lang="en"> 
<head> 
  <meta charset="UTF-8" /> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0" /> 
  <title>University Management System</title> 
  <style> 
    * { 
      box-sizing: border-box;
	  margin: 0;       
	  padding: 0; 
    } 
 body {      
	font-family: 'Segoe UI', sans-serif;       
	background-color: #f4f4f4;      
	color: #333; 
    } 
header {      
	background-color: #2c3e50;       
	color: red;       
	padding: 20px 0;      
	text-align: center; 
    } 
nav ul {       
 list-style: none;       
 padding: 10px 0;       
 display: flex;      
 justify-content: center;       
 gap: 20px; 
    } 
nav a {       
	color: white;       
	text-decoration: none;       
	font-weight: bold; 
    } 
nav a:hover {       
	text-decoration: underline; 
    } 
main {       
	display: flex;       
	justify-content: space-around;       
	padding: 40px 20px;       
	flex-wrap: wrap; 
    } 
.card {      
	background-color: white;       
	padding: 20px;       
	margin: 10px;       
	width: 300px;      
	border-radius: 8px;       
	box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);       
	text-align: center; 
    } 
.card h2 {       
	margin-bottom: 10px; 
    } 
 .card .btn {       
	display: inline-block;       
	margin-top: 10px;       
	padding: 10px 20px;       
	background-color: #2980b9;       
	color: white;       
	text-decoration: none;       
	border-radius: 5px; 
    } 
 .card .btn:hover {       
	background-color: #1c5980; 
    } 
footer {       
	background-color: #2c3e50;      
	color: white;      
	text-align: center;       
	padding: 15px 0;       
	margin-top: 30px; 
    } 
  </style> 
</head> 
<body> 
  <header> 
    <h1>University Management System</h1> 
    <nav> 
      <ul> 
        <li><a href="#">Home</a></li> 
        <li><a href="#">Students</a></li> 
        <li><a href="#">Faculty</a></li> 
        <li><a href="#">Courses</a></li> 
        <li><a href="#">Logout</a></li> 
      </ul> 
    </nav> 
  </header> 
 
  <main> 
    <section class="card"> 
      <h2>Students</h2> 
      <p>Manage student records, enrollment, grades, and more.</p> 
      <a href="#" class="btn">View Students</a> 
    </section> 
 
    <section class="card"> 
      <h2>Faculty</h2> 
      <p>Manage faculty profiles, schedules, and assignments.</p> 
      <a href="#" class="btn">View Faculty</a> 
    </section> 
 
    <section class="card"> 
      <h2>Courses</h2> 
      <p>View and edit course offerings, schedules, and credits.</p> 
      <a href="#" class="btn">View Courses</a> 
    </section> 
  </main> 
 
  <footer> 
    <p>&copy; 2025 University Management System</p> 
  </footer> 
</body> 
</html> 
