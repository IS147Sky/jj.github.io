<!DOCTYPE html>
<html lang="en">
<head>
<title>Lab4</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>


.topnav {
  overflow: hidden;
  background-color: #e9e9e9;
  
}

.topnav a {
  float: left;
  display: block;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: gold;
  color: black;
}

.topnav input[type=text] {
  float: right;
  padding: 6px;
  margin-top: 8px;
  margin-right: 16px;
  border: none;
  font-size: 17px;
}

    
section:after {
  content: "";
  display: table;
  clear: both;
}




@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
  
   footer {
      background-color: #f2f2f2;
      padding: 5px;
    }
    .x {
      text-align: right;
       }
    ul {
      width: auto;
       }
    li {
      display: inline-block;
    }
   h1 {
  color: gold;
  font-family: Times;
  font-size: 300%;

}

</style>
</head>
<nav>
<h1>UMBC</h1>
</nav>
<nav>
<h2>Department of Information Systems</h2>
</nav>
<nav class="navbar navbar-inverse">
  <div class="topnav">
  <a class="active" href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#undergraduate">Academics</a>
  <a href="#research">Admission and Aid</a>
  <a href="#research">Campus Life</a>
  
  <input type="text" placeholder="Search..">
</div>
</nav>



<section>
  <nav>
  <h3>Home</h3>
    
      <a href="#">Mission and Vision</a><br>
      <a href="#">Leadership</a><br>
      <a href="#">News</a><br>
      <a href="#">Rankings</a><br>
    
  </nav>
  
  <article>
    <h3>Contact Us</h3>
    <p>To reach any UMBC office, department, faculty member or student, please call our general information number at 410-455-1000.</p>
    
    
  </article>
</section>

<footer class="container-fluid text-center">
  <p>UMBC</p>
  <div class="x">
   <ul>
          <li><a href="#">About UMBC</a></li>
          <li><a href="#">Contact Us</a></li>
          <li><a href="#">Consumer Information</a></li>
                    </ul>
     </div>
</footer>

</body>
</html>


