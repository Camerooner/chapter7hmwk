# chapter7hmwk
chapter 7 homework


https://camerooner.github.io/townhallhmwk/


index.html:

<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="utf-8">
	<title>San Joaquin Valley Town Hall</title>
	<link rel="shortcut icon" href="images/favicon.ico">
	<link rel="stylesheet" href="styles/c7_main.css">
</head>

<body>
	<header>
		<img src="images/town_hall_logo.gif" alt="Town Hall logo" height="80">
		<h2>San Joaquin Valley Town Hall</h2>
		<h3>Celebrating our <span class="shadow">75<sup>th</sup></span> Year</h3>

		<nav id="nav_menu">
			<ul>
				<li><a href="index.html">Home</a></li>
				<li>
					<a href="speakers/index.html">Speakers</a>
					<ul>
						<li><a href="speakers/brancaccio.html">David Brancaccio</a></li>
						<li><a href="speakers/sorkin.html">Andrew Ross Sorkin</a></li>
						<li><a href="speakers/chua.html">Amy Chua</a></li>
						<li><a href="speakers/c6_sampson.html">Scott Sampson</a></li>
					</ul>
				</li>
				<li><a href="luncheons.html">Luncheons</a></li>
				<li><a href="members.html" class="current">Become a Member</a></li> 
				<li class="lastitem">
					<a href="aboutus.html">About Us</a>
					<ul>
						<li><a href="history.html">Our History</a></li>
						<li><a href="board.html">Board of Directors</a></li>
					</ul>
				</li>
			</ul>
		</nav>

	</header>
	<main>
		<section>
			<h2>Our Mission</h2>
			<p>San Joaquin Valley Town Hall is a non-profit organization that is run by an 
			   all-volunteer board of directors. Our mission is to bring nationally and 
			   internationally renowned, thought-provoking speakers who inform, educate, 
			   and entertain our audience! As one or our members told us:</p>
			<blockquote>&ldquo;Each year I give a ticket package to each of our family members. 
			I think of it as the gift of knowledge...and that is priceless.&rdquo;</blockquote>
			<h1>Speaker of the Month</h1>
			<article>
				<h2>Fossil Threads in the Web of Life</h2>
				<img src="images/sampson_dinosaur.jpg" alt="Scott Sampson with dinosaur">
				<h3>February<br>
				Scott Sampson</h3>
				<p>What's 75 million years old and brand spanking new? A teenage Utahceratops! 
				Come to the Saroyan, armed with your best dinosaur roar, when Scott Sampson, Research 
				Curator at the Utah Museum of Natural History, steps to the podium. Sampson's research 
				has focused on the ecology and evolution of late Cretaceous dinosaurs and he has conducted 
				fieldwork in a number of countries in Africa.</p>
				<p><a href="speakers/c6_sampson.html">Read more.</a>&nbsp;<b><a href="media/sampson.mp4" target ="_blank">Or play video</a></b></p>
			</article>
			
			<h2>Our Ticket Packages</h2>
			<ul>
				<li>Season Package: $95</li>
				<li>Patron Package: $200</li>
				<li>Single Speaker: $25</li>
			</ul>
		</section>
		
		<aside>
			<h2>Guest speakers</h2>
			<h3>October<br><a href="speakers/brancaccio.html">David Brancaccio</a></h3>
			<img src="images/brancaccio75.jpg" alt="David Brancaccio photo">
			<h3>November<br><a href="speakers/sorkin.html">Andrew Ross Sorkin</a></h3>
			<img src="images/sorkin75.jpg" alt="Andrew Ross Sorkin photo">
			<h3>January<br><a href="speakers/chua.html">Amy Chua</a></h3>
			<img src="images/chua75.jpg" alt="Amy Chua photo">
			<h3>February<br><a href="speakers/c6_sampson.html">Scott Sampson</a></h3>
			<img src="images/sampson75.jpg" alt="Scott Sampson photo">
		</aside>
	</main>
	<footer>
		<p>&copy; 2022, San Joaquin Valley Town Hall, Fresno, CA 93755</p>
	</footer>
</body>
</html>




c7_main.css:

/* the styles for the elements */
* {
	margin: 0;
	padding: 0;
}
html {
	background-color: white;
}
body {
	font-family: Arial, Helvetica, sans-serif;
    font-size: 100%;
    width: 800px;
    margin: 0 auto;
    border: 3px solid #931420;
    background-color: #fffded;
}
a:focus, a:hover {
	font-style: italic;
}
/* the styles for the header */
header {
	padding: 0em 0 0em 0;
	border-bottom: 3px solid #931420;
		background-image: -moz-linear-gradient(
	    30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
	background-image: -webkit-linear-gradient(
	    30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
	background-image: -o-linear-gradient(
	    30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
	background-image: linear-gradient(
	    30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
}
header h2 {
	margin-top: 0;
	font-size: 175%;
	color: #800000;
}
header h3 {
	font-size: 130%;
	font-style: italic;
}
header img {
	float: left;
	padding: 0 30px;
}

 #nav_menu {
    margin: 0;
    padding: 0;
	margin-top: 20px;
}


#nav_menu {

    border-bottom: 3px solid #800000;

 }

 #nav_menu ul {

    list-style-type: none;
    position: relative;
 }

 #nav_menu ul li {

    float: left;
    width: 20%;

 }

 #nav_menu ul li a {

    text-align: center;
    display: block;
    padding: .7em 0;
    background-color: #800000;
    font-weight: bold;
    text-decoration: none;
    color: white;

 }

 #nav_menu ul ul {

    display: none;
    position: absolute;
    top: 100%;
    width: 100%;

 }

 #nav_menu ul ul li {

    float: none;


 }

 #nav_menu ul li:hover > ul {

    display: block;

}

#nav_menu > ul::after {

    content: "";
    clear: both;
    display: block;

}

#nav_menu a:hover {

    color:black;
    background-color: #800000;
}

 #nav_menu ul li {

    float: left;
    width: 20%;
 }
 

#nav_menu ul ul {

    display: none;

}

/* ===============================

        Navigation List

================================*/
#nav_list h2 {


    margin-bottom: 5px;
    text-align: center;

}

#nav_list ul {

    list-style-type: none;
}

#nav_list li {

    width: 90%;
    margin: 0 auto .5em;
    border: 1px solid #800000;

}

#nav_list a {

    display: block;
    font-weight: bold;
    text-decoration: none;
    background-color: white;
    padding: .5em;
    color: black;

}

#nav_list a:hover {

    background-color: #800000;
    color: white;

}


.shadow {
	text-shadow: 2px 2px 2px #800000;
}
/* the styles for the section */
section {
	width: 525px;
	float: right;
	padding: 0 20px 20px 20px;
}
section h1 {
	font-size: 150%;
	padding: .5em 0 .25em 0;
	margin: 0;
}
section h2 {
	color: #800000;
	font-size: 130%;
	padding: .5em 0 .25em 0;
}
section p {
	padding-bottom: .5em;
}
section blockquote {
	padding: 0 2em;
	font-style: italic;
}
section ul {
	padding: 0 0 .25em 1.25em;
}
section li {
	padding-bottom: .35em;
}

section ul {
	list-style-type: circle;
  }

/* the styles for the article */
article {
	padding: .5em 0;
	border-top: 2px solid #800000;
	border-bottom: 2px solid #800000;
}
article h2 {
	padding-top: 0;
}
article h3 {
	font-size: 105%;
	padding-bottom: .25em;
}
article img {
	float: right;
	margin: .5em 0 1em 1em;
	border: 1px solid black;
}

/* the styles for the aside */
aside {
	width: 215px;
	float: right;
	padding: 0 0 20px 20px;
}
aside h2 {
	color: #800000;
	font-size: 130%;
	padding: .5em 0 .25em 0;
}
aside h3 {
	font-size: 105%;
	padding-bottom: .25em;
}
aside img {
	padding-bottom: 1em;
}

/* the styles for the footer */
footer {
	background-color: #931420;
	clear: both;

}
footer p {
	text-align: center;
	color: white;
	padding: 1em 0;
}





c7_sampson.html:

<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<title>San Joaquin Valley Town Hall</title>
	<link rel="shortcut icon" href="../images/favicon.ico">
	<link rel="stylesheet" href="../styles/c6_speaker.css">
</head>
<body>
	<header>
		<img src="../images/town_hall_logo.gif" alt="Town Hall logo" height="80">
		<h2>San Joaquin Valley Town Hall</h2>
		<h3>Celebrating our <span class="shadow">75<sup>th</sup></span> Year</h3>

		<nav id="nav_menu">
			<ul>
				<li><a href="index.html">Home</a></li>
				<li>
					<a href="speakers/index.html">Speakers</a>
					<ul>
						<li><a href="brancaccio.html">David Brancaccio</a></li>
						<li><a href="sorkin.html">Andrew Ross Sorkin</a></li>
						<li><a href="chua.html">Amy Chua</a></li>
						<li><a href="c6_sampson.html">Scott Sampson</a></li>
					</ul>
				</li>
				<li><a href="luncheons.html">Luncheons</a></li>
				<li><a href="members.html" class="current">Become a Member</a></li> 
				<li class="lastitem">
					<a href="aboutus.html">About Us</a>
					<ul>
						<li><a href="history.html">Our History</a></li>
						<li><a href="board.html">Board of Directors</a></li>
					</ul>
				</li>
			</ul>
		</nav>
		
	</header>
	<main>
		<section>
			<h1>Fossil Threads in the Web of Life</h1>
			<article>
				<img src="../images/sampson_dinosaur.jpg" alt="Scott Sampson with dinosaur">
				<h2>February<br>Scott Sampson</h2>
				<p>What's 75 million years old and brand spanking new? A teenage Utahceratops! Come to the 
				   Saroyan, armed with your best dinosaur roar, when Scott Sampson, Research Curator at the 
				   Utah Museum of Natural History, steps to the podium. Sampson's research has focused on the 
				   ecology and evolution of late Cretaceous dinosaurs and he has conducted fieldwork in a number 
				   of countries in Africa.</p>
				<p>Scott Sampson is a Canadian-born paleontologist who received his Ph.D. in zoology from the 
				   University of Toronto. His doctoral work focused on two new species of ceratopsids (horned 
				   dinosaurs) from the Late Cretaceous of Montana, as well as the growth and function of certopsid 
				   horns and frills.</p>
				<p>Following graduation in 1993, Sampson spent a year working at the American Museum of Natural 
				   History in New York City, followed by five years as assistant professor of anatomy at the New 
				   York College of Osteopathic Medicine on Long Island. He arrived at the University of Utah 
				   accepting a dual position as assistant professor in the Department of Geology and Geophysics 
				   and curator of vertebrate paleontology at the Utah Museum of Natural History. His research 
				   interests largely revolve around the phylogenetics, functional morphology, and evolution of 
				   Late Cretaceous dinosaurs.</p>
				<p>In addition to his museum and laboratory-based studies, Sampson has conducted paleontological 
				   work in Zimbabwe, South Africa, and Madagascar, as well as the United States and Canada. He was 
				   also the on-air host for the Discovery Channel's Dinosaur Planet and recently completed a book, 
				   Dinosaur Odyssey: Fossil Threads in the Web of Life, which is one of the most 
				   comprehensive surveys of dinosaurs and their worlds to date.</p>
			</article>
		</section>
		
		<aside>
			<h2>Guest speakers</h2>
			<h3>October<br><a href="../speakers/brancaccio.html">David Brancaccio</a></h3>
			<img src="../images/brancaccio75.jpg" alt="David Brancaccio photo">
			<h3>November<br><a href="../speakers/sorkin.html">Andrew Ross Sorkin</a></h3>
			<img src="../images/sorkin75.jpg" alt="Andrew Ross Sorkin photo">
			<h3>January<br><a href="../speakers/chua.html">Amy Chua</a></h3>
			<img src="../images/chua75.jpg" alt="Amy Chua photo">
			<h3>February<br><a href="../speakers/c6_sampson.html">Scott Sampson</a></h3>
			<img src="../images/sampson75.jpg" alt="Scott Sampson photo">
			<h3><a href="../c6_index.html">Return to Home page</a></h3>
		</aside>
	</main>
	<footer>
		<p>&copy; 2022, San Joaquin Valley Town Hall, Fresno, CA 93755</p>
	</footer>
</body>
</html>






c7_speaker.css:

/* the styles for the elements */
* {
	margin: 0;
	padding: 0;
}
html {
	background-color: white;
}
body {
	font-family: Arial, Helvetica, sans-serif;
    font-size: 100%;
    width: 800px;
    margin: 0 auto;
    border: 3px solid #931420;
    background-color: #fffded;
}
a:focus, a:hover {
	font-style: italic;
}
/* the styles for the header */
header {
	padding: 1.5em 0 2em 0;
	border-bottom: 3px solid #931420;
		background-image: -moz-linear-gradient(
	    30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
	background-image: -webkit-linear-gradient(
	    30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
	background-image: -o-linear-gradient(
	    30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
	background-image: linear-gradient(
	    30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
}
header h2 {
	font-size: 175%;
	color: #800000;
}
header h3 {
	font-size: 130%;
	font-style: italic;
}
header img {
	float: left;
	padding: 0 30px;
}
.shadow {
	text-shadow: 2px 2px 2px #800000;
}

/* Style the navigation menu */
#nav_menu {
	background-color: #333;
	overflow: hidden;
  }
  
  #nav_menu ul {
	margin: 0;
	padding: 0;
	list-style: none;
  }
  
  #nav_menu > ul > li {
	float: left;
  }
  
  #nav_menu li a {
	display: block;
	color: white;
	text-align: center;
	padding: 16px;
	text-decoration: none;
  }
  
  #nav_menu li a:hover {
	background-color: #111;
  }
  
  #nav_menu ul ul {
	display: none;
	position: absolute;
	top: 100%;
	left: 0;
	background-color: #f9f9f9;
	border: 1px solid #ccc;
  }
  
  #nav_menu ul ul li {
	float: none;
  }
  
  #nav_menu ul ul li a {
	color: #333;
	padding: 12px 16px;
	text-decoration: none;
	display: block;
	text-align: left;
  }
  
  #nav_menu ul ul li a:hover {
	background-color: #ddd;
  }
  
  #nav_menu ul li:hover > ul {
	display: inherit;
  }
  
.shadow {
	text-shadow: 2px 2px 2px #800000;
}
/* the styles for the main content */

main {
	clear: left;
}

/* the styles for the section */
section {
	width: 525px;
	float: right;
	padding: 0 20px 20px 20px;
}
section h1 {
	color: #800000;
	font-size: 150%;
	padding-top: .5em;
	margin: 0;
}
section p {
	padding-bottom: .5em;
}
section blockquote {
	padding: 0 2em;
	font-style: italic;
}
section ul {
	padding: 0 0 .25em 1.25em;
}
section li {
	padding-bottom: .35em;
}

/* the styles for the article */
article {
	padding: .5em 0;
}
article h2 {
	font-size: 115%;
	padding: 0 0 .25em 0;
}
article img {
	float: right;
	margin: .5em 0 1em 1em;
	border: 1px solid black;
}

/* the styles for the aside */
aside {
	width: 215px;
	float: right;
	padding: 0 0 20px 20px;
}
aside h2 {
	color: #800000;
	font-size: 130%;
	padding: .5em 0 .25em 0;
}

aside h3 {
	font-size: 105%;
	padding-bottom: .25em;
}
aside img {
	padding-bottom: 1em;
}

/* the styles for the footer */
footer {
	background-color: #931420;
	clear: both;

}
footer p {
	text-align: center;
	color: white;
	padding: 1em 0;
}
