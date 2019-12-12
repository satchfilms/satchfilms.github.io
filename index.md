

<!DOCTYPE html>
<html>
<head>

<style>
</style>

<link rel="stylesheet" type="text/css" href="Assignment3.css">
</head>


<body>
  <img src="https://www.asu.edu/asuthemes/4.8/assets/full_logo.png" height="142">

  <h1>Satchel Reid</h1>
  <a href=' https://www.google.com/maps/place/922+E+Apache+Blvd,+Tempe,+AZ+85281/data=!4m2!3m1!1s0x872b08e901c5dbf5:0x8e6fcd887f7aaf02?sa=X&ved=2ahUKEwiGm5mu4dTkAhVULX0KHdhWDHsQ8gEwAHoECAoQAQ' target='_blank'>  922 East Apache Blvd, Tempe AZ </a>
  <br><br><br>
  <a href="mailto:streid2@asu.edu" target="_blank"> streid2@asu.edu </a>
  <br><br><br>
  <a href="tel:480-208-9663" target="_blank"> 480-208-9663 </a>
<section id="accordion">
<br><br><br>
<div>
  <input type="checkbox" id="check-1" />
	<label for="check-1">Objective</label>
				<article>
          <body>
            <li> I am currently pursuing a degree in Digital Culture with a film focus. <br> My objective is to work in the VFX industry and eventually work myself up into creative direction.</li>
          </body>
        </article>
</div>
<br><br><br>

<div>
  <input type="checkbox" id="check-2" />
	<label for="check-2">Education</label>
			<article>
        <a>
          <table style="width:70%" border="1">
            <tr>
              <th>COURSE</th>
              <th>SCHOOL</th>
              <th>YEAR OF PASSING</th>
            </tr>
            <tr>
              <td>Diploma</td>
              <td>Hamilton High School</td>
              <td>2018</td>
            </tr>
            <tr>
        <td>Bachelors in Digital Culture</td>
        <td>ASU</td>
        <td>In Progress </td>
      </tr>
          </table>
        </a>
      </article>
</div>

<br><br><br>

<div>
  <input type="checkbox" id="check-3" />
	<label for="check-3">Experience</label>
	<article>
    <ol>
      <li>VFX Artist for AP Studios (2019-Present). Responsibilities include animation and stage visuals<br>as well as video editing and design.</li>
      <li>Independent Video Director (2018-Present)</li>
      <li>Sales Representitive; Retail (2016)</li>
    </ol>
  </article>
</div>

<br><br><br>

<div>
  <input type="checkbox" id="check-4" />
	<label for="check-4">References</label>
	<article>

  <ul style="list-style-type:square;">
      <li>John Doe</li>
      <li>Jane Doe</li>
    </ul>
  </article>
</div>

</body>

</html>

body {background-color: DarkSeaGreen;}
h1{
color: black;
font-family: verdana;
font-size: 300%;
}

p1{
color: black;
font-family: arial;
font-size: 40%;
font-weight: lighter;
}

a{
  color: black;
  font-family: helvetica;
  font-size: 150%;
  border: 2px solid black;
  background-color: MediumSeaGreen;
  padding: 10px;
}

label{
  color: black;
  font-family: verdana;
  font-size: 300%;
}

tr{
  background-color: MediumSeaGreen ;
}

td{
  font-weight: lighter;
}

li{
  color: black;
  font-family: arial;
  font-size: 100%;
}

#container {
    margin: 0 auto;
    width: 50%;
}
#accordion input {
	display: none;
}
#accordion label {
	background: #eee;
	border-radius: .25em;
	cursor: pointer;
	display: block;
	margin-bottom: .125em;
	padding: .25em 1em;
	z-index: 20;
}
#accordion label:hover {
	background: #ccc;
}

#accordion input:checked + label {
	background: #ccc;
	border-bottom-right-radius: 0;
	border-bottom-left-radius: 0;
	color: white;
	margin-bottom: 0;
}
#accordion article {
	background: #f7f7f7;
	height:0px;
	overflow:hidden;
	z-index:10;
}
#accordion article p {
	padding: 1em;
}
#accordion input:checked article {
}
#accordion input:checked ~ article {
	border-bottom-left-radius: .25em;
	border-bottom-right-radius: .25em;
	height: auto;
	margin-bottom: .125em;
}
