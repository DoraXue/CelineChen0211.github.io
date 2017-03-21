<html>
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="chrome=1">
    <title> Recent Job Market Analysis across Differnet Majors </title>
    <link rel="stylesheet" href="{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
    <script src="{{ '/assets/js/respond.js' | relative_url }}"></script>
    <!--[if lt IE 9]>
      <script src="//html5shiv.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->
    <!--[if lt IE 8]>
    <link rel="stylesheet" href="{{ '/assets/css/ie.css' | relative_url }}">
    <![endif]-->
    <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no">

  </head>
  <body>

    <div class="wrapper">

      <section>
        <div id="title">
          <h1> Recent Job Market Analysis </h1>
          <hr class = "style15">
          <p> <a href="mailto:cjwchen@ucdavis.edu?Subject=Hello%20again" target="_top">Jiewei Chen</a> and
          <a href="mailto:xdxue@ucdavis.edu?Subject=Hello%20again" target="_top">Da Xue</a> </p>
          <hr>
         </div>



<h2> <center>A quick look at this project</center> </h2>

<div class="youtube">
	<iframe width="560" height="315" src="https://www.youtube.com/embed/vwKmp3zmiXg" frameborder="0" allowfullscreen></iframe>
</div>
  
<div class = 'ex3'> </div>

<p>		What is the current demand in the job market? How much money can I make if I major in statistics? What are the most important skills to put into my resume? Where are the hiring companies located? How does the job market differ across different majors? When is the job market largest?… </p>

<p> 	These practical questions are faced by new graduates and even younger college students. This project tries its best to help the freshmen to choose the best major; senior and graduate students to draw a big picture of the current job market. </p>

<p> 	The majority of this project analyzes and compares the job market for the 3 majors of STAT, CHE, and MSE. (Because we are CHE and MSE students considering of pursuing a second degree!) </p>

<h2> METHOD & TECHENIQUES </h2>

<p>		The data of the job market come from indeed.com(link). We restricted our scope to STAT, CHE, and MSE, and California. (The procedure can be easily extended to other locations and majors.) </p>

<p>		To quickly get to the fun part of the results, the methodologies and techniques we used for this project are summarized in this table. You may scroll down to the very bottom to find the link to our jupyter notebook to find more details. </p>

<div>
	<img src="Figures/2-method.jpg" height="300" align="middle">
</div>

<h2> Interesting Findings </h2>
	<h3> Where are the hiring companies </h3>
	<div>
  	<img src="Figures/LocationofJobs.png" height="300" align="right">
  	</div>
	<p> Not surprisingly, there are two clusters on the map, one is at the silicon valley, and the other is around LA. </p>
	<p> Another interesting observation is that the STAT companies are more closely centered at these two locations, whereas the CHE and MSE companies are more widely distributed.</p>
	<p>	Check out these interactive maps to have a closer look at the job posts. Click the pins to find the job titles and company names! </p>
	
	<iframe width="200" height="200" src='Figures/Statistics.html' frameborder="1"></iframe><iframe width="200" height="200" src='Figures/Chemical_Engineering.html' frameborder="1"></iframe><iframe width="200" height="200" src='Figures/Materials_Science.html' frameborder="1"></iframe>
	
	<h3> Grads vs Undergrads, who are more wanted? </h3>
	<div>
		<img src="Figures/Degree requirement comparison.png" height="200" align="middle">
	</div>
<p>The majority of the jobs only require a Bachelors degree. For internships, the percentage of graduate is slightly higher. It is interesting to find that there is really high demand for Materials Science graduate students for internships.</p>
	<div>
		<img src="Figures/3-degree pie.jpg" height="150" align="middle">
	</div>
<p>The population data of the entire US in 2014 to 2015 academic year of the statistic major and engineering majors come from the National Center for Education Statistics. And the job demand data were obtained from Indeed website and only for California. Since the data are not on the same page in terms of time and locations, we only compared the percentage of different degrees. </p>
<p>Assuming the CA data is representative for the entire nation, the percentage of undergrad is smaller in population than that in the job market. It seems to be easier for undergrads to find a job. However, people with higher education levels may prefer to continue their career in academia rather than industry.</p>

	<h3>Skill set</h3>
	<div>
		<img src="Figures/4-venn.jpg" height="200" align="right">
	</div>
	<div>
		<img src="Figures/skill set of STAT.png" height="200" align="right">
	</div>	
	<h3> Salary Level </h3>
	<div>
		<img src="Figures/salary_violinplot.png" height="200" align="right">
	</div>
	<h3> Skill set of different salary levels</h3>
	<div>
		<img src="Figures/Skill Salary Bar Plot.png" height="250" align="right">
	</div>


<div class = 'ex3'>
</div>

<center> This is us laughing when finishing the project... (not really) </center>
<div >
<center><img class = "clip" src="laughing.JPG" width="410" height="273" align="middle"></center>
</div>
</section>
<div class = 'ex3'>
</div>

<center>
<footer class="site-footer">
    Copyright Jiewei Chen & Da Xue &copy; 2017
</footer>
</center>
