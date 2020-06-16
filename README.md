<!DOCTYPE html>
<html lang="em">
<head>
	<meta charset="utf-8">
	<title>Assignment Solution for Module 2</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div class="wrapper">
		<h1>OUR MENU!!</h1>

		<div class="menu">
			<div class="menu_name">
				<h3 id="h1">Chicken</h3>
				<p>
					Genetic studies have pointed to multiple maternal origins in South Asia, Southeast Asia, and East Asia,[5] but with the clade found in the Americas, Europe, the Middle East and Africa originating in the Indian subcontinent. From ancient India, the domesticated chicken spread to Lydia in western Asia Minor, and to Greece by the 5th century BC.[6] 
				</p>
			</div>
       		<div class="menu_name">
				<h3 id="h2">Beef</h3>
				<p>
					Most beef skeletal muscle meat can be used as is by merely cutting into certain parts, such as roasts, short ribs or steak (filet mignon, sirloin steak, rump steak, rib steak, rib eye steak, hanger steak, etc.), while other cuts are processed (corned beef or beef jerky). Trimmings, on the other hand, are usually mixed with meat from older, leaner (therefore tougher) cattle, are ground, minced or used in sausages.
				</p>
			</div>
        	<div class="menu_name">
				<h3 id="h3">Sushi</h3>
				<p>
					Sushi is traditionally made with medium-grain white rice, though it can be prepared with brown rice or short-grain rice. It is very often prepared with seafood, such as squid, eel, yellowtail, salmon, tuna or imitation crab meat. Many types of sushi are vegetarian.
				</p>
			</div>
        </div>
</body>
</html>



@import url('https://fonts.googleapis.com/css2?family=Metal+Mania&family=Sriracha&display=swap');

*{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}
body{
	background: white;
	font-family: 'Sriracha', cursive;
}	
.wrapper{
	margin-top: 5%;
}
.wrapper h1{
	font-family: 'Metal Mania', cursive;
	font-size: 52px;
	margin-bottom: 61px;
	text-align: center;
}

.menu{
	display: flex;
	width: auto;
	justify-content: center;
}

.menu .menu_name{
	background: grey;
	border: purple solid 3px;
	margin: 5px;
	margin-bottom: 50px;
	width: 300px;
	padding: 20px;
	line-height: 20px;
	border: 1px;

}

.menu .menu_name h3{
	color: black;
	font-size: 20px;
	margin: 1px;
	position: relative;
	right: 10px;
	border: black solid 2px;
	float: right;

 }

 #h1{
 	background-color: red;
 	position: top-right;
 }

 #h2{
 	background-color: blue;
 }

 #h3{
 	background-color: orange;
 }
