<!DOCTYPE html>
<!-- saved from url=(0047)https://ds.cs.rutgers.edu/assignment-play-2048/ -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
        
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Data Structures</title>
        <link rel="stylesheet" href="./readMe45.md_files/style.css">
   <link rel="dns-prefetch" href="https://maps.googleapis.com/">
<link rel="dns-prefetch" href="https://wordpress.cs.rutgers.edu/">
<link rel="dns-prefetch" href="https://s.w.org/">
		<script type="text/javascript">
			window._wpemojiSettings = {"baseUrl":"https:\/\/s.w.org\/images\/core\/emoji\/12.0.0-1\/72x72\/","ext":".png","svgUrl":"https:\/\/s.w.org\/images\/core\/emoji\/12.0.0-1\/svg\/","svgExt":".svg","source":{"concatemoji":"https:\/\/ds.cs.rutgers.edu\/wp-includes\/js\/wp-emoji-release.min.js?ver=5.4.14"}};
			/*! This file is auto-generated */
			!function(e,a,t){var n,r,o,i=a.createElement("canvas"),p=i.getContext&&i.getContext("2d");function s(e,t){var a=String.fromCharCode;p.clearRect(0,0,i.width,i.height),p.fillText(a.apply(this,e),0,0);e=i.toDataURL();return p.clearRect(0,0,i.width,i.height),p.fillText(a.apply(this,t),0,0),e===i.toDataURL()}function c(e){var t=a.createElement("script");t.src=e,t.defer=t.type="text/javascript",a.getElementsByTagName("head")[0].appendChild(t)}for(o=Array("flag","emoji"),t.supports={everything:!0,everythingExceptFlag:!0},r=0;r<o.length;r++)t.supports[o[r]]=function(e){if(!p||!p.fillText)return!1;switch(p.textBaseline="top",p.font="600 32px Arial",e){case"flag":return s([127987,65039,8205,9895,65039],[127987,65039,8203,9895,65039])?!1:!s([55356,56826,55356,56819],[55356,56826,8203,55356,56819])&&!s([55356,57332,56128,56423,56128,56418,56128,56421,56128,56430,56128,56423,56128,56447],[55356,57332,8203,56128,56423,8203,56128,56418,8203,56128,56421,8203,56128,56430,8203,56128,56423,8203,56128,56447]);case"emoji":return!s([55357,56424,55356,57342,8205,55358,56605,8205,55357,56424,55356,57340],[55357,56424,55356,57342,8203,55358,56605,8203,55357,56424,55356,57340])}return!1}(o[r]),t.supports.everything=t.supports.everything&&t.supports[o[r]],"flag"!==o[r]&&(t.supports.everythingExceptFlag=t.supports.everythingExceptFlag&&t.supports[o[r]]);t.supports.everythingExceptFlag=t.supports.everythingExceptFlag&&!t.supports.flag,t.DOMReady=!1,t.readyCallback=function(){t.DOMReady=!0},t.supports.everything||(n=function(){t.readyCallback()},a.addEventListener?(a.addEventListener("DOMContentLoaded",n,!1),e.addEventListener("load",n,!1)):(e.attachEvent("onload",n),a.attachEvent("onreadystatechange",function(){"complete"===a.readyState&&t.readyCallback()})),(n=t.source||{}).concatemoji?c(n.concatemoji):n.wpemoji&&n.twemoji&&(c(n.twemoji),c(n.wpemoji)))}(window,document,window._wpemojiSettings);
		</script><script src="./readMe45.md_files/wp-emoji-release.min.js" type="text/javascript" defer=""></script>
		<style type="text/css">
img.wp-smiley,
img.emoji {
	display: inline !important;
	border: none !important;
	box-shadow: none !important;
	height: 1em !important;
	width: 1em !important;
	margin: 0 .07em !important;
	vertical-align: -0.1em !important;
	background: none !important;
	padding: 0 !important;
}
</style>
	<link rel="stylesheet" id="theme-style-css" href="./readMe45.md_files/style(1).css" type="text/css" media="all">
<link rel="stylesheet" id="theme-style-override-css" href="./readMe45.md_files/override.css" type="text/css" media="all">
<link rel="stylesheet" id="wp-block-library-css" href="./readMe45.md_files/style.min.css" type="text/css" media="all">
<link rel="stylesheet" id="dashicons-css" href="./readMe45.md_files/dashicons.min.css" type="text/css" media="all">
<link rel="stylesheet" id="megamenu-fontawesome-css" href="./readMe45.md_files/font-awesome.min.css" type="text/css" media="all">
<link rel="stylesheet" id="megamenu-genericons-css" href="./readMe45.md_files/genericons.css" type="text/css" media="all">
<link rel="stylesheet" id="elementor-icons-css" href="./readMe45.md_files/elementor-icons.min.css" type="text/css" media="all">
<link rel="stylesheet" id="elementor-animations-css" href="./readMe45.md_files/animations.min.css" type="text/css" media="all">
<link rel="stylesheet" id="elementor-frontend-css" href="./readMe45.md_files/frontend.min.css" type="text/css" media="all">
<link rel="stylesheet" id="elementor-pro-css" href="./readMe45.md_files/frontend.min(1).css" type="text/css" media="all">
<link rel="stylesheet" id="font-awesome-5-all-css" href="./readMe45.md_files/all.min.css" type="text/css" media="all">
<link rel="stylesheet" id="font-awesome-4-shim-css" href="./readMe45.md_files/v4-shims.min.css" type="text/css" media="all">
<link rel="stylesheet" id="elementor-global-css" href="./readMe45.md_files/global.css" type="text/css" media="all">
<link rel="stylesheet" id="elementor-post-3289-css" href="./readMe45.md_files/post-3289.css" type="text/css" media="all">
<link rel="stylesheet" id="authorizer-public-css-css" href="./readMe45.md_files/authorizer-public.css" type="text/css" media="all">
<link rel="stylesheet" id="google-fonts-1-css" href="./readMe45.md_files/css" type="text/css" media="all">
<script type="text/javascript">
/* <![CDATA[ */
var OnePress_Plus = {"ajax_url":"https:\/\/ds.cs.rutgers.edu\/wp-admin\/admin-ajax.php","browser_warning":" Your browser does not support the video tag. I suggest you upgrade your browser."};
/* ]]> */
</script>
<script type="text/javascript" src="./readMe45.md_files/jquery.js"></script>
<script type="text/javascript" src="./readMe45.md_files/jquery-migrate.min.js"></script>
<script type="text/javascript" src="./readMe45.md_files/v4-shims.min.js"></script>
<script type="text/javascript">
/* <![CDATA[ */
var auth = {"wpLoginUrl":"https:\/\/ds.cs.rutgers.edu\/wp-login.php?redirect_to=%2Fassignment-play-2048%2F","publicWarning":"","anonymousNotice":"Notice: You are browsing this site anonymously, and only have access to a portion of its content.","logIn":"Log In"};
/* ]]> */
</script>
<script type="text/javascript" src="./readMe45.md_files/authorizer-public.js"></script>
<link rel="https://api.w.org/" href="https://ds.cs.rutgers.edu/wp-json/">
<link rel="EditURI" type="application/rsd+xml" title="RSD" href="https://ds.cs.rutgers.edu/xmlrpc.php?rsd">
<link rel="wlwmanifest" type="application/wlwmanifest+xml" href="https://ds.cs.rutgers.edu/wp-includes/wlwmanifest.xml"> 
<meta name="generator" content="WordPress 5.4.14">
<link rel="canonical" href="https://ds.cs.rutgers.edu/assignment-play-2048/">
<link rel="shortlink" href="https://ds.cs.rutgers.edu/?p=3289">
<link rel="alternate" type="application/json+oembed" href="https://ds.cs.rutgers.edu/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fds.cs.rutgers.edu%2Fassignment-play-2048%2F">
<link rel="alternate" type="text/xml+oembed" href="https://ds.cs.rutgers.edu/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fds.cs.rutgers.edu%2Fassignment-play-2048%2F&amp;format=xml">
<script src="./readMe45.md_files/saved_resource" type="text/javascript"></script>
<!-- teachPress -->
<script type="text/javascript" src="./readMe45.md_files/frontend.js"></script>
<link type="text/css" href="./readMe45.md_files/teachpress_front.css" rel="stylesheet">
<!-- END teachPress -->
<style type="text/css">.recentcomments a{display:inline !important;padding:0 !important;margin:0 !important;}</style><link rel="icon" href="https://wordpress.cs.rutgers.edu/ds-cs-rutgers-edu/wp-content/uploads/sites/82/2018/10/favicons_shield.gif" sizes="32x32">
<link rel="icon" href="https://wordpress.cs.rutgers.edu/ds-cs-rutgers-edu/wp-content/uploads/sites/82/2018/10/favicons_shield.gif" sizes="192x192">
<link rel="apple-touch-icon" href="https://wordpress.cs.rutgers.edu/ds-cs-rutgers-edu/wp-content/uploads/sites/82/2018/10/favicons_shield.gif">
<meta name="msapplication-TileImage" content="https://wordpress.cs.rutgers.edu/ds-cs-rutgers-edu/wp-content/uploads/sites/82/2018/10/favicons_shield.gif">
<style type="text/css">/** Mega Menu CSS: fs **/</style>

    <script type="text/javascript" charset="UTF-8" src="./readMe45.md_files/common.js"></script><script type="text/javascript" charset="UTF-8" src="./readMe45.md_files/util.js"></script></head>
    <body data-elementor-device-mode="desktop" data-new-gr-c-s-check-loaded="14.1135.0" data-gr-ext-installed="">
                <a class="sas-skip-to-content sas-link" href="https://ds.cs.rutgers.edu/assignment-play-2048/#sas-content">Skip to Main Content</a>
        <input type="checkbox" class="sas-sidenav-toggle" id="sas-sidenav-toggle">
        <label for="sas-sidenav-toggle" class="sas-sidenav-label" role="button" aria-label="Toggle Navigation Sidebar">
            <div class="sas-bar"></div>
            <div class="sas-bar"></div>
            <div class="sas-bar"></div>
        </label>
        <nav class="sas-sidenav" aria-label="Primary Navigation">
                
            <ul class="sas-ul sas-links-tree">
                <li class="sas-item">
                    <a class="sas-link" href="https://ds.cs.rutgers.edu/">Home</a>
                </li>
                
    <li id="menu-item-178" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-home menu-item-178 sas-item"><a href="https://ds.cs.rutgers.edu/" class="sas-link">Syllabus</a></li>
<li id="menu-item-198" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-198 sas-item"><a href="https://ds.cs.rutgers.edu/lectures/" class="sas-link">Lectures</a></li>
<li id="menu-item-291" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-291 sas-item"><a href="https://ds.cs.rutgers.edu/assignments/" class="sas-link">Assignments</a></li>
<li id="menu-item-371" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-371 sas-item"><a href="https://ds.cs.rutgers.edu/exams/" class="sas-link">Exams</a></li>
<li id="menu-item-40" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-40 sas-item"><a href="https://ds.cs.rutgers.edu/staff/" class="sas-link">Staff</a></li>

            </ul>
        
        </nav>

        <div class="sas-page">
                        <div class="sas-top-links">
                <div class="sas-container">
                        
            <ul class="sas-ul sas-links-strip">
                <li class="sas-item">
                    <a class="sas-link" href="https://www.rutgers.edu/">Rutgers Home</a>
                </li>
                
    <li id="menu-item-1267" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1267 sas-item"><a href="http://sas.rutgers.edu/" class="sas-link">SAS</a></li>
<li id="menu-item-1268" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1268 sas-item"><a href="http://cs.rutgers.edu/" class="sas-link">CS</a></li>

            </ul>
        
                    <div class="sas-search">
                            
    <form role="search" method="get" action="https://ds.cs.rutgers.edu/">
        <input class="sas-search-text" type="text" value="" name="s" placeholder="Search ..." aria-label="Search Query">
    </form>

                    </div>
                </div>
            </div>

                        <header>
                <div class="sas-banner">
                    <div class="sas-container">
                        <div role="img" aria-label="School of Arts and Sciences Logo">
                            <a href="https://sas.rutgers.edu/" aria-label="School of Arts and Sciences">
                            <img class="sas-logo sas-logo-big" src="./readMe45.md_files/red_banner.png" alt="School of Arts and Sciences Logo">
                            <img class="sas-logo sas-logo-small" src="./readMe45.md_files/sas_red_header_MOBILE.png" alt="School of Arts and Sciences Logo">
                            </a>
                        </div>
                        <h1 class="sas-title">
                            <a class="sas-link" href="https://ds.cs.rutgers.edu/" aria-label="">Data Structures</a>
                        </h1>
                        <h2 class="sas-tagline">
                           Computer Science Department                        </h2>
                    </div>
                </div>
            </header>

                        <nav class="sas-nav" aria-label="Primary Navigation">
                <div class="sas-container">
                        
            <ul class="sas-ul sas-links-strip">
                <li class="sas-item">
                    <a class="sas-link" href="https://ds.cs.rutgers.edu/">Home</a>
                </li>
                
    <li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-home menu-item-178 sas-item"><a href="https://ds.cs.rutgers.edu/" class="sas-link">Syllabus</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-198 sas-item"><a href="https://ds.cs.rutgers.edu/lectures/" class="sas-link">Lectures</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-291 sas-item"><a href="https://ds.cs.rutgers.edu/assignments/" class="sas-link">Assignments</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-371 sas-item"><a href="https://ds.cs.rutgers.edu/exams/" class="sas-link">Exams</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-40 sas-item"><a href="https://ds.cs.rutgers.edu/staff/" class="sas-link">Staff</a></li>

            </ul>
        
                </div>
            </nav>

            <main class="sas-content" id="sas-content">
                <div class="sas-container">
                        
    <article class="sas-post">		<div data-elementor-type="wp-post" data-elementor-id="3289" class="elementor elementor-3289" data-elementor-settings="[]">
			<div class="elementor-inner">
				<div class="elementor-section-wrap">
							<section class="elementor-element elementor-element-80a7e1b elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="80a7e1b" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-9d7b61e elementor-column elementor-col-100 elementor-top-column" data-id="9d7b61e" data-element_type="column">
			<div class="elementor-column-wrap">
					<div class="elementor-widget-wrap">
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-8fa4efd elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="8fa4efd" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-8029377 elementor-column elementor-col-100 elementor-top-column" data-id="8029377" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-dfa1af3 elementor-widget elementor-widget-text-editor" data-id="dfa1af3" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><h3>Play 2048 – 100 course points</h3><p><span style="font-weight: 400">In this assignment, you will be coding the game 2048 using 2-D arrays. You will practice array manipulation, how to navigate references to objects, and the object-oriented programming (OOP) paradigm.</span></p><p><b>Be sure to start your assignment early – don’t wait until the last minute! </b><span style="font-weight: 400">You will need time to understand this assignment and the many questions it may present.</span></p><p>Refer to our Programming <a href="https://ds.cs.rutgers.edu/assignment-faq/">Assignments FAQ</a> for instructions on how to install VSCode, how to use the command line and how to submit your assignments.</p><p><a href="https://youtu.be/1z87C5ODTV0">See this video on how to import the project into VSCode and how to submit into Autolab</a>.</p></div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-2be9c76 elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="2be9c76" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-80f825d elementor-column elementor-col-100 elementor-top-column" data-id="80f825d" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-1a1aa37 elementor-widget elementor-widget-text-editor" data-id="1a1aa37" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><h3>Overview</h3><p>2048 is a puzzle game where<span style="font-weight: 400"> you use the arrow keys to move left, right, up or down to merge tiles of the same number together.<a href="https://www.mathsisfun.com/games/2048.html"> Check it out</a> if you never played it before.</span></p><p><span style="font-weight: 400">The goal of the game is to keep merging numbered (non-zero) tiles until you get one 2048 tile. If two tiles with the same number touch each other, they are merged together in the direction swiped into a new tile with twice the value. (ex: if you move up, the topmost value doubles and the bottom value becomes 0). Be careful with your moves – if the board is full at the end of a turn and there are no other valid moves, it’s game over!</span></p><p><span style="font-weight: 400">In this assignment, we will represent the 2048 grid as a 4×4 array of integers, with 0’s representing empty tiles. </span><b>Note that we will grade your individual operations – not your score or ability to get to 2048.&nbsp;</b></p></div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-ef4a092 elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="ef4a092" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-5421d1e elementor-column elementor-col-100 elementor-top-column" data-id="5421d1e" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-6128703 elementor-widget elementor-widget-text-editor" data-id="6128703" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><h3>Implementation</h3><h3><b>Overview of files provided</b></h3><p>We provide two drivers (text and graphic) to help you test the individual methods. We suggest that you start with the text driver but once you have a good understanding of the assignment then you may use the graphic driver.</p><ul><li><b>Board: </b><span style="font-weight: 400">The Board class contains all methods needed to construct a functioning 2048 game. Edit the empty methods with you solution, but<strong> DO NOT edit the provided ones or the methods signatures of any method</strong>. This is the file you submit.</span></li><li><b>BoardSpot: </b><span style="font-weight: 400">An object used to represent a location on the board. It houses a row and a column, along with getters and setters. </span><b>Don’t edit or submit to Autolab.</b></li><li><b>TextDriver: </b><span style="font-weight: 400">A tool to test your 2048 board interactively using only</span><b> text-based boards. </b><span style="font-weight: 400">This driver is equivalent to AnimatedDriver and functions in the same way – you are free to use this driver to test all of your methods. Feel free to edit this class, as it is provided only to help you test. </span><b>It is not submitted and/or graded.</b><ul><li style="font-weight: 400"><span style="font-weight: 400">To use this driver, pick whether you want to test individual methods or play the full game (this option requires all methods to be completed) by selecting the number that appears for each option.&nbsp;</span></li><li style="font-weight: 400"><span style="font-weight: 400">To test individual methods, first type in the full file name for an input file. Then, select a method to test by typing in the number that appears for each method in the list. Additionally, for makeMove, moves are represented by using the WASD keys like arrow keys (w is up, a is left, s is down, and d is right). Type in the letter corresponding to the move you want to test.</span></li><li style="font-weight: 400"><span style="font-weight: 400">Playing the full game makes use of the WASD keys like arrow keys (W is up, A is left, S is down, and D is right). Press “Q” to quit.</span></li></ul></li><li><b>AnimatedDriver: </b><span style="font-weight: 400">A tool to test your 2048 board interactively through </span><b>rendered images. </b><span style="font-weight: 400">This driver is equivalent to TextDriver and functions in the same way – you are free to use this driver to test all of your methods. Feel free to edit this class, as it is provided only to help you test. </span><b>It is not submitted and/or graded.</b><ul><li style="font-weight: 400"><span style="font-weight: 400">To use this driver, pick whether you want to test individual methods or play the full game (this option requires all methods to be completed) by selecting the number that appears for each option.&nbsp;</span></li><li style="font-weight: 400"><span style="font-weight: 400">To test individual methods, first type in the full file name for an input file. Then, select a method to test by typing in the number that appears for each method in the list. You will then see the board stored in the input file. For all methods </span><b>besides makeMove, </b><span style="font-weight: 400">press any key to test your method. Press any key again to exit testing that method.</span></li><li style="font-weight: 400"><span style="font-weight: 400">For makeMove, moves are represented by using the WASD keys like arrow keys (w is up, a is left, s is down, and d is right). Type in the letter corresponding to the move you want to test when you see&nbsp;</span><span style="font-weight: 400">the board stored in the input file. Once you type that letter, the move you want to test will be made. Press any key afterward to exit testing that method.</span></li><li style="font-weight: 400"><span style="font-weight: 400">Playing the full game makes use of the WASD keys like arrow keys (w is up, a is left, s is down, and d is right). Press “q” to quit.</span></li></ul></li><li style="font-weight: 400"><span style="font-weight: 600">StdIn </span><span style="font-weight: 400">and </span><span style="font-weight: 600">StdOut:</span><span style="font-weight: 400">&nbsp;libraries to handle input and output. </span><b>Do not edit these classes.</b></li><li><b>StdRandom</b><span style="font-weight: 400">: Provides methods for generating random numbers. </span><b>Don’t edit or submit to Autolab.</b></li><li><b></b><b>Collage, Picture, StdDraw: </b><span style="font-weight: 400">Helper libraries to support AnimatedDriver. </span><b>Don’t edit or submit to Autolab.</b></li><li><b></b><b>Input Files</b>: Preset boards you’re able to use to test your 2048 board in the drivers (intput1.in, input2.in,…). <b>You can use all input files to test all methods. </b>Each input file contains 4 lines, each with 4 space separated numbers. Each number is either 0 (represents an empty space) or a power of 2 (represents a normal tile). Feel free to make your own input files, as <b>they will not be submitted to Autolab.</b></li></ul></div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-5365e11 elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="5365e11" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-619725f elementor-column elementor-col-100 elementor-top-column" data-id="619725f" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-10d1bca elementor-widget elementor-widget-text-editor" data-id="10d1bca" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><h3>Board.java</h3><ul><li>DO NOT add new import statements.</li><li>DO NOT change any of the method’s signatures.</li></ul><p><b>Methods to be implemented by you:</b></p><h3><b><span style="color: #993300">1. updateOpenSpaces</span></b></h3><ul><li class="c3 li-bullet-0"><span class="c4 c6">This method&nbsp;</span>adds a BoardSpot to the openSpaces array for every &nbsp;board open spot.<div><div>A spot <code>(i, j)</code> is open when <code>gameBoard[i][j] = 0</code>.</div></div></li></ul><ul><li>Initialize a new ArrayList of <code>BoardSpot</code> objects in <code>openSpaces</code>.</li><li>Add to <code>openSpaces</code> all pairs (row, column) where <code>gameBoard[row][column]</code> is 0 (ie. the tile is empty). Use <code>BoardSpot</code> objects to represent these pairs.</li><li>Submit Board.java with this method completed under <strong>Early Submission to receive extra credit</strong>.</li></ul><p><strong>Note</strong>: DO NOT call <code>updateOpenSpaces</code> in any method. The driver/Autolab will call <code>updateOpenSpaces</code> and <code>addRandomTile</code> before making a move.</p><p>Here is an example of testing this method using input1.in in both drivers. In TextDriver, open spaces in the <code>openSpaces ArrayList</code> are denoted by two asterisks **.</p></div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-5ae3e67 elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="5ae3e67" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-8061d2d elementor-column elementor-col-50 elementor-top-column" data-id="8061d2d" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-ea6ce17 elementor-widget elementor-widget-image" data-id="ea6ce17" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
							<figure class="wp-caption">
										<img width="424" height="312" src="./readMe45.md_files/Screen-Shot-2023-01-27-at-4.45.26-PM.png" class="attachment-large size-large" alt="" srcset="https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-4.45.26-PM.png 424w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-4.45.26-PM-300x221.png 300w" sizes="(max-width: 424px) 100vw, 424px">											<figcaption class="widget-image-caption wp-caption-text">Text Driver</figcaption>
										</figure>
					</div>
				</div>
				</div>
						</div>
			</div>
		</div>
				<div class="elementor-element elementor-element-75b496e elementor-column elementor-col-50 elementor-top-column" data-id="75b496e" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-4afc059 elementor-widget elementor-widget-image" data-id="4afc059" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
							<figure class="wp-caption">
										<img width="275" height="300" src="./readMe45.md_files/Screen-Shot-2023-01-27-at-11.08.45-AM-275x300.png" class="attachment-medium size-medium" alt="" srcset="https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-11.08.45-AM-275x300.png 275w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-11.08.45-AM.png 584w" sizes="(max-width: 275px) 100vw, 275px">											<figcaption class="widget-image-caption wp-caption-text">Animated Driver</figcaption>
										</figure>
					</div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-6165afe elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="6165afe" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-a93793f elementor-column elementor-col-100 elementor-top-column" data-id="a93793f" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-3627070 elementor-widget elementor-widget-text-editor" data-id="3627070" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><h3><span style="color: #993300"><b>2. addRandomTile</b></span></h3><p>Note: <code>updateOpenSpaces</code> <strong><span style="text-decoration: underline">must</span></strong> be completed before starting this method.</p><p><span style="font-weight: 400">This method adds a random tile into the board, following these rules:</span></p><ul><li style="font-weight: 400"><span style="font-weight: 400">First, pick a random <code>BoardSpot</code> from the <code>openSpaces</code> ArrayList (test cases are guaranteed to always have an open space). Use </span><code><b>StdRandom.uniform(int a, int b) </b></code><span style="font-weight: 400">to generate a random integer between a lower bound “a” up to (but not including) an upper bound “b”.&nbsp;</span><ul><li>To randomly pick a board spot the lower bound is 0 and the upper bound is the number of items in the ArrayList.</li></ul></li><li style="font-weight: 400"><span style="font-weight: 400">Next, assign a value to the tile. There is a 90% chance that a 2 tile will be inserted and a 10% chance that a 4 tile will be inserted. Use </span><code><b>StdRandom.uniform(double a, double b) </b></code><span style="font-weight: 400">to generate a random double between a lower bound “a” up to (but not including) an upper bound “b.” </span><ul><li>To randomly pick a number between 0 and 1 the lower bound is 0 and the upper bound is 1.</li><li style="font-weight: 400"><span style="font-weight: 400">If this value is less than, but not equal to, 10 percent (0.1), the tile will have a 4 value. Otherwise, the tile will have a 2 value.</span></li></ul></li><li style="font-weight: 400"><span style="font-weight: 400">Be sure to update the correct tile in the gameBoard array (as defined by the BoardSpot’s row and column values) with the proper value.&nbsp;</span></li><li style="font-weight: 400"><span style="font-weight: 400"><span style="text-decoration: underline">Note</span>: On the driver updateOpenSpaces() is called before this method to ensure that openSpaces is up to date. </span><b>You do not need to remove the board spot from the openSpaces ArrayList!</b></li><li><span style="text-decoration: underline">Note</span>: On the driver, the seed is set so you will get the same outputs every time when testing individual methods. Autolab uses the same seed as the driver to test this method. <b>However</b>, when playing the full game, the driver will not use seed values – it will use random values to generate different boards and tiles.</li></ul><p>Here is an example of testing this method using input1.in in both drivers.</p></div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-70203a8 elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="70203a8" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-924a4ec elementor-column elementor-col-50 elementor-top-column" data-id="924a4ec" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-137b33f elementor-widget elementor-widget-image" data-id="137b33f" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
							<figure class="wp-caption">
										<img width="316" height="362" src="./readMe45.md_files/Screen-Shot-2023-01-27-at-4.46.17-PM.png" class="attachment-large size-large" alt="" srcset="https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-4.46.17-PM.png 316w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-4.46.17-PM-262x300.png 262w" sizes="(max-width: 316px) 100vw, 316px">											<figcaption class="widget-image-caption wp-caption-text">Text Driver</figcaption>
										</figure>
					</div>
				</div>
				</div>
						</div>
			</div>
		</div>
				<div class="elementor-element elementor-element-2795c1b elementor-column elementor-col-50 elementor-top-column" data-id="2795c1b" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-12fb1f2 elementor-widget elementor-widget-image" data-id="12fb1f2" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
							<figure class="wp-caption">
										<img width="277" height="300" src="./readMe45.md_files/Screen-Shot-2023-01-27-at-5.08.14-PM-277x300.png" class="attachment-medium size-medium" alt="" srcset="https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-5.08.14-PM-277x300.png 277w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-5.08.14-PM.png 562w" sizes="(max-width: 277px) 100vw, 277px">											<figcaption class="widget-image-caption wp-caption-text">Animated Driver</figcaption>
										</figure>
					</div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-9e52fde elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="9e52fde" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-849f495 elementor-column elementor-col-100 elementor-top-column" data-id="849f495" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-4f7f329 elementor-widget elementor-widget-text-editor" data-id="4f7f329" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><h3><span style="color: #993300"><b>3. swipeLeft</b></span></h3><p><span style="font-weight: 400">Move all tiles as far left as possible while maintaining the same order and number of tiles. </span></p><ul><li><span style="font-weight: 400">There should be no empty spaces to the left of any tile. </span></li><li><span style="font-weight: 400">Remember that 0 (<code>gameBoard[row][col] = 0</code>) represents an empty space.&nbsp;</span></li><li>Watch this <a href="https://drive.google.com/file/d/1ZpR-8aSGJ8irZyWpQHh-HMOUCod3h2nT/view?usp=share_link">video</a> to learn more about this method.</li></ul><p><span style="font-weight: 400">Here is an example of testing this method using input1.in in both drivers.</span></p></div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-7164969 elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="7164969" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-a4c40ae elementor-column elementor-col-50 elementor-top-column" data-id="a4c40ae" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-6b7ff92 elementor-widget elementor-widget-image" data-id="6b7ff92" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
							<figure class="wp-caption">
										<img width="481" height="470" src="./readMe45.md_files/Screen-Shot-2023-01-27-at-4.46.56-PM.png" class="attachment-large size-large" alt="" srcset="https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-4.46.56-PM.png 481w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-4.46.56-PM-300x293.png 300w" sizes="(max-width: 481px) 100vw, 481px">											<figcaption class="widget-image-caption wp-caption-text">Text Driver</figcaption>
										</figure>
					</div>
				</div>
				</div>
						</div>
			</div>
		</div>
				<div class="elementor-element elementor-element-152f7ed elementor-column elementor-col-50 elementor-top-column" data-id="152f7ed" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-cb2a7a9 elementor-widget elementor-widget-image" data-id="cb2a7a9" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
							<figure class="wp-caption">
										<img width="275" height="300" src="./readMe45.md_files/Screen-Shot-2023-01-27-at-11.37.32-AM-275x300.png" class="attachment-medium size-medium" alt="" srcset="https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-11.37.32-AM-275x300.png 275w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-11.37.32-AM.png 475w" sizes="(max-width: 275px) 100vw, 275px">											<figcaption class="widget-image-caption wp-caption-text">Animated Driver</figcaption>
										</figure>
					</div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-be20249 elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="be20249" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-7f0c099 elementor-column elementor-col-100 elementor-top-column" data-id="7f0c099" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-3ec0d3e elementor-widget elementor-widget-text-editor" data-id="3ec0d3e" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><h3><span style="color: #993300"><b>4. mergeLeft</b></span></h3><p><span style="font-weight: 400">Merge all identical nonzero, horizontal pairs in the board.</span></p><ul><li style="font-weight: 400"><span style="font-weight: 400">The leftmost neighbor (ex. The first 2 in “0 2 2 0”) will double its value, while the rightmost neighbor (ex. The second 2 in “0 2 2 0”) will become 0. The method will turn this row into “0 4 0 0”.&nbsp;</span></li><li style="font-weight: 400"><span style="font-weight: 400">Only </span><b>pairs</b><span style="font-weight: 400"> will merge. 3-tile neighbors and 4-tile neighbors will not merge to become one tile. For example, “2 2 2 0” becomes “4 0 2 0” and “2 2 2 2” becomes “4 0 4 0”.&nbsp;</span></li><li>Watch this <a href="https://drive.google.com/file/d/1PtrvaWmHPrgBmQgyD1RzVIoPlpAEbm1W/view?usp=share_link">video</a> to learn more about this method.</li></ul><p><span style="font-weight: 400">Here is an example of testing this method using input1.in in both drivers.</span></p></div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-d5da4c7 elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="d5da4c7" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-b1d198d elementor-column elementor-col-50 elementor-top-column" data-id="b1d198d" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-e114bfc elementor-widget elementor-widget-image" data-id="e114bfc" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
							<figure class="wp-caption">
										<img width="492" height="481" src="./readMe45.md_files/Screen-Shot-2023-01-27-at-4.47.23-PM.png" class="attachment-large size-large" alt="" srcset="https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-4.47.23-PM.png 492w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-4.47.23-PM-300x293.png 300w" sizes="(max-width: 492px) 100vw, 492px">											<figcaption class="widget-image-caption wp-caption-text">Text Driver</figcaption>
										</figure>
					</div>
				</div>
				</div>
						</div>
			</div>
		</div>
				<div class="elementor-element elementor-element-dd622d7 elementor-column elementor-col-50 elementor-top-column" data-id="dd622d7" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-25e9ccc elementor-widget elementor-widget-image" data-id="25e9ccc" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
							<figure class="wp-caption">
										<img width="276" height="300" src="./readMe45.md_files/Screen-Shot-2023-01-27-at-11.41.27-AM-276x300.png" class="attachment-medium size-medium" alt="" srcset="https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-11.41.27-AM-276x300.png 276w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-11.41.27-AM.png 415w" sizes="(max-width: 276px) 100vw, 276px">											<figcaption class="widget-image-caption wp-caption-text">Animated Driver</figcaption>
										</figure>
					</div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-cf8d206 elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="cf8d206" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-26d6905 elementor-column elementor-col-100 elementor-top-column" data-id="26d6905" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-e3f0fa4 elementor-widget elementor-widget-text-editor" data-id="e3f0fa4" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p><b>The next two methods (transpose and flipRows) can be applied in sequence to rotate the board 90 degrees clockwise. <span style="font-weight: 400">This will allow you to reuse your existing code for <code>swipeLeft</code> and <code>mergeLeft</code> for any of </span><span style="font-weight: 400">the four directions. </span></b></p><p><b><span style="font-weight: 400">For example, we can swipe right by rotating the board twice, calling <code>swipeLeft</code>, then rotating the board twice to return it to its original orientation. The provided method <code>rotateBoard</code> calls <code>transpose</code> and <code>flipRows</code> in sequence to complete a 90 degree clockwise rotation. </span></b></p><ul><li>Watch <a href="https://drive.google.com/file/d/13dcyIH6J2cyLdwRNPEFsKZXFRlc7ACOY/view?usp=share_link">this video</a> to learn more about the intuition behind these methods.</li></ul><h3><span style="color: #993300"><b>5. transpose</b></span></h3><p><span style="font-weight: 400">Interchange the rows and columns of the board. In other words, row 1 should become column 1, row 2 becomes column 2, and so on. More formally, <code>gameBoard[i][j]</code> becomes <code>gameBoard[j][i]</code> for all 0 &lt;= i &lt; 4 and 0 &lt;= j &lt; 4.&nbsp;</span></p><ul><li style="font-weight: 400"><span style="font-weight: 400">Transposing flips the board along its main diagonal (top left to bottom right).&nbsp;</span></li><li>Watch <a href="https://drive.google.com/file/d/1roSMBcNI4NVE3dEZA3yaxuHMlafSmeRi/view?usp=sharing">this video</a> to learn more about this method<b>.</b></li></ul><p><span style="font-weight: 400">Here is an example of testing this method using input1.in in both drivers.</span></p></div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-8677f1d elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="8677f1d" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-f0ff0ab elementor-column elementor-col-50 elementor-top-column" data-id="f0ff0ab" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-5f6428c elementor-widget elementor-widget-image" data-id="5f6428c" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
							<figure class="wp-caption">
										<img width="427" height="424" src="./readMe45.md_files/Screen-Shot-2023-01-27-at-4.47.57-PM.png" class="attachment-large size-large" alt="" srcset="https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-4.47.57-PM.png 427w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-4.47.57-PM-300x298.png 300w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-4.47.57-PM-150x150.png 150w" sizes="(max-width: 427px) 100vw, 427px">											<figcaption class="widget-image-caption wp-caption-text">Text Driver</figcaption>
										</figure>
					</div>
				</div>
				</div>
						</div>
			</div>
		</div>
				<div class="elementor-element elementor-element-0a472c7 elementor-column elementor-col-50 elementor-top-column" data-id="0a472c7" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-0de9042 elementor-widget elementor-widget-image" data-id="0de9042" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
							<figure class="wp-caption">
										<img width="278" height="300" src="./readMe45.md_files/Screen-Shot-2023-01-27-at-11.50.51-AM-278x300.png" class="attachment-medium size-medium" alt="" srcset="https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-11.50.51-AM-278x300.png 278w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-11.50.51-AM.png 364w" sizes="(max-width: 278px) 100vw, 278px">											<figcaption class="widget-image-caption wp-caption-text">Animated Driver</figcaption>
										</figure>
					</div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-2b196dc elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="2b196dc" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-89bcf92 elementor-column elementor-col-100 elementor-top-column" data-id="89bcf92" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-559005d elementor-widget elementor-widget-text-editor" data-id="559005d" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><h3><span style="color: #993300"><b>6. flipRows</b></span></h3><p>Reverse all rows.</p><ul><li style="font-weight: 400"><span style="font-weight: 400">Columns 1, 2, 3, and 4 (in order) will have a new order of 4, 3, 2, and 1. For example, the row “2 0 4 0” would become “0 4 0 2”.</span></li><li style="font-weight: 400"><span style="font-weight: 400">Repeat this procedure for all 4 rows.</span></li><li style="font-weight: 400">Watch <a href="https://drive.google.com/file/d/1apE9o-tIqZToDocWXmggCOifQdhE5FSG/view?usp=sharing">this video</a> to learn more about this method.</li></ul><p><span style="font-weight: 400">Here is an example of testing this method using input1.in in both drivers.</span></p></div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-d95b34f elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="d95b34f" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-e229cf9 elementor-column elementor-col-50 elementor-top-column" data-id="e229cf9" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-5278a57 elementor-widget elementor-widget-image" data-id="5278a57" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
							<figure class="wp-caption">
										<img width="466" height="464" src="./readMe45.md_files/Screen-Shot-2023-01-27-at-4.48.31-PM.png" class="attachment-large size-large" alt="" srcset="https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-4.48.31-PM.png 466w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-4.48.31-PM-300x300.png 300w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-4.48.31-PM-150x150.png 150w" sizes="(max-width: 466px) 100vw, 466px">											<figcaption class="widget-image-caption wp-caption-text">Text Driver</figcaption>
										</figure>
					</div>
				</div>
				</div>
						</div>
			</div>
		</div>
				<div class="elementor-element elementor-element-2763b21 elementor-column elementor-col-50 elementor-top-column" data-id="2763b21" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-8fd3b60 elementor-widget elementor-widget-image" data-id="8fd3b60" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
							<figure class="wp-caption">
										<img width="277" height="300" src="./readMe45.md_files/Screen-Shot-2023-01-27-at-11.55.14-AM-277x300.png" class="attachment-medium size-medium" alt="" srcset="https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-11.55.14-AM-277x300.png 277w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-11.55.14-AM.png 504w" sizes="(max-width: 277px) 100vw, 277px">											<figcaption class="widget-image-caption wp-caption-text">Animated Driver</figcaption>
										</figure>
					</div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-02afeda elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="02afeda" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-49be7ec elementor-column elementor-col-100 elementor-top-column" data-id="49be7ec" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-0594200 elementor-widget elementor-widget-text-editor" data-id="0594200" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p><b>Watch </b><a href="https://drive.google.com/file/d/1Q8yTb3eFJgqLIluhJscBNxtdQNVfHvTn/view?usp=sharing"><b>this </b>video</a> to learn more about why we rotated the board and how we can use rotations in <code>makeMove</code> to make up, down, and right moves.</p><h3><span style="color: #993300"><b>7. makeMove</b></span></h3><p><span style="font-weight: 400">Putting everything together by calling previous methods to construct 2048 moves in all directions.&nbsp;</span><span style="font-weight: 400">Rotate as necessary to complete this method using different directions. Swipe left, merge neighbors, and swipe left again to re-fill blank spaces.&nbsp;</span></p><ul><li style="font-weight: 400"><span style="font-weight: 400">The method input parameter is a character that indicates which direction to move (‘U’ = up, ‘R’ = right, ‘D’ = down, ‘L’ = left). Assume that you will only receive these characters, case-sensitive, as arguments in the makeMove method.</span></li><li style="font-weight: 400"><span style="font-weight: 400">Be sure to have <code>transpose</code>, <code>flipRows</code>, <code>swipeLeft</code>, and <code>mergeLeft</code> completed before doing this method and all previous methods completed before testing.</span></li><li style="font-weight: 400"><b>As stated earlier, call <code>rotateBoard</code> to help with non-left directions. <span style="font-weight: 400">This allows for MUCH better code reuse than redoing your <code>swipeLeft</code> and <code>mergeLeft</code> in 3 new directions.</span></b></li><li style="font-weight: 400"><span style="font-weight: 400">To test this method, select the “makeMove” option in either driver and enter a character. You can use the W, A, S, and D keys like arrow keys (w = up, a = left, s = down and d = right). </span><b>Even though you will be using the WASD keys like arrow keys, these keys still map to U, L, D, and R respectively; for instance, pressing W will call makeMove with ‘U’ as the letter parameter.</b></li><li>Watch <a href="https://drive.google.com/file/d/1MnjpjUTf29Yu6uFv4ASx6yHkmyIo-Wk2/view?usp=share_link">this video</a> to learn more about this method.</li></ul><p>Here is the expected output after testing makeMove with input1.in, <b>moving up:</b></p></div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-d24a7c0 elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="d24a7c0" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-d738640 elementor-column elementor-col-50 elementor-top-column" data-id="d738640" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-30bdedb elementor-widget elementor-widget-image" data-id="30bdedb" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
							<figure class="wp-caption">
										<img width="509" height="287" src="./readMe45.md_files/Screen-Shot-2023-01-27-at-12.04.41-PM.png" class="attachment-large size-large" alt="" srcset="https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-12.04.41-PM.png 509w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-12.04.41-PM-300x169.png 300w" sizes="(max-width: 509px) 100vw, 509px">											<figcaption class="widget-image-caption wp-caption-text">Text Driver</figcaption>
										</figure>
					</div>
				</div>
				</div>
						</div>
			</div>
		</div>
				<div class="elementor-element elementor-element-049f49a elementor-column elementor-col-50 elementor-top-column" data-id="049f49a" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-ada4b7d elementor-widget elementor-widget-image" data-id="ada4b7d" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
							<figure class="wp-caption">
										<img width="278" height="300" src="./readMe45.md_files/Screen-Shot-2023-01-27-at-12.04.56-PM-278x300.png" class="attachment-medium size-medium" alt="" srcset="https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-12.04.56-PM-278x300.png 278w, https://ds.cs.rutgers.edu/wp-content/uploads/sites/82/2023/01/Screen-Shot-2023-01-27-at-12.04.56-PM.png 617w" sizes="(max-width: 278px) 100vw, 278px">											<figcaption class="widget-image-caption wp-caption-text">Animated Driver</figcaption>
										</figure>
					</div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-0954a99 elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="0954a99" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-55b8a0b elementor-column elementor-col-100 elementor-top-column" data-id="55b8a0b" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-7c04421 elementor-widget elementor-widget-text-editor" data-id="7c04421" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><h3>Implementation Notes</h3>
<ul>
 	<li>YOU MAY only update the methods updateOpenSpaces(), addRandomTile(), swipeLeft(), mergeLeft(), transpose(), flipRows(), and makeMove().</li>
 	<li><b>COMMENT all printing statements from Board.java</b></li>
 	<li>DO NOT add any instance variables to the&nbsp;Board class.</li>
 	<li>DO NOT add any public methods to the&nbsp;Board class.</li>
 	<li>DO NOT add/rename the project or package statements.</li>
 	<li>DO NOT change the class Board name.</li>
 	<li>YOU MAY add private methods to the&nbsp;Board class.</li>
 	<li>YOU MAY use any of the libraries provided in the zip file.</li>
 	<li><span style="color: #ff0000"><strong>DO NOT</strong></span> use System.exit()</li>
</ul></div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-c75ad14 elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="c75ad14" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-385f422 elementor-column elementor-col-100 elementor-top-column" data-id="385f422" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-134ac0f elementor-widget elementor-widget-text-editor" data-id="134ac0f" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><h3>VSCode Extensions</h3><p>You can install VSCode extension packs for Java. Take a look at <a href="https://code.visualstudio.com/docs/java/java-tutorial">this tutorial</a>. We suggest:</p><ul><li><a href="https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack">Extension Pack for Java</a></li><li><a href="https://code.visualstudio.com/docs/java/java-project">Project Manager for Java</a></li><li><a href="https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-debug">Debugger for Java</a></li></ul><h3>Importing VSCode Project</h3><ol><li>Download Play2048.zip from <a href="https://autolab.cs.rutgers.edu/">Autolab Attachments</a>.</li><li>Unzip the file by double clicking.</li><li>Open VSCode<ul><li>Import the folder to a workspace through&nbsp;<strong>File</strong> &gt; <b>Open</b></li></ul></li></ol><h3>Executing and Debugging</h3><ul><li>You can run your program through VSCode or you can use the Terminal to compile and execute. We suggest running through VSCode because it will give you the option to debug.</li><li><a href="https://code.visualstudio.com/docs/java/java-debugging">How to debug your code</a></li><li>If you choose the Terminal:<ul><li>first navigate to <strong>Play2048</strong> directory/folder<ul><li>to compile: &nbsp;<strong>javac -d bin src/game/*.java</strong></li><li>to execute: <strong>java -cp bin game.AnimatedDriver OR&nbsp;</strong><strong>java -cp bin game.TextDriver</strong></li></ul></li></ul></li></ul></div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-d1b173c elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="d1b173c" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-0cc9ebf elementor-column elementor-col-100 elementor-top-column" data-id="0cc9ebf" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-bf2241f elementor-widget elementor-widget-text-editor" data-id="bf2241f" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><h3>Before submission</h3><p><span style="color: #ff0000"><b>COMMENT all printing statements from Board.java</b></span></p><p><strong>Collaboration policy.</strong> Read our collaboration policy <a href="https://ds.cs.rutgers.edu/#academic-integrity">here</a>.</p><p><strong>Submitting the assignment.&nbsp;</strong>Submit <em>Board.java</em>&nbsp;separately via the web submission system called Autolab. To do this, click the <em>Assignments</em> link from the course website; click the <em>Submit</em> link for that assignment.</p><h3>Getting help</h3><p>If anything is unclear, don’t hesitate to drop by office hours or post a question on Piazza.</p><ul><li>Find instructors office hours&nbsp;<a href="https://ds.cs.rutgers.edu/staff/"><em>here</em></a></li><li>Find tutors office hours on Canvas -&gt; Tutoring, RU CATS</li><li>Find head TAs office hours&nbsp;<a href="https://ds.cs.rutgers.edu/staff/"><em>here</em></a></li><li>In addition to office hours we have the <a href="https://resources.cs.rutgers.edu/docs/rooms-equipment/cave/">CAVE</a> (Collaborative Academic Versatile Environment), a community space staffed with lab assistants which are undergraduate students further along the CS major to answer questions.</li></ul></div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
				<section class="elementor-element elementor-element-c7da9b3 elementor-section-boxed elementor-section-height-default elementor-section-height-default elementor-section elementor-top-section" data-id="c7da9b3" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
				<div class="elementor-row">
				<div class="elementor-element elementor-element-e01ccb9 elementor-column elementor-col-100 elementor-top-column" data-id="e01ccb9" data-element_type="column">
			<div class="elementor-column-wrap  elementor-element-populated">
					<div class="elementor-widget-wrap">
				<div class="elementor-element elementor-element-e758aa7 elementor-widget elementor-widget-text-editor" data-id="e758aa7" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p>Problem by Kal Pandit and Ishaan Ivaturi</p></div>
				</div>
				</div>
						</div>
			</div>
		</div>
						</div>
			</div>
		</section>
						</div>
			</div>
		</div>
		</article>

                </div>
            </main>
            <footer>
                                <div class="sas-info">
                    <div class="sas-container">
                        <div class="sas-links-section">
                            <h2 class="sas-links-title">Connect with Rutgers</h2>
                            <ul class="sas-ul sas-links-list">
                                <li class="sas-item"><a class="sas-link" href="http://www.rutgers.edu/">Rutgers Home</a></li>
                                <li class="sas-item"><a class="sas-link" href="http://www.rutgers.edu/news-center/rutgers-today">Rutgers Today</a></li>
                                <li class="sas-item"><a class="sas-link" href="https://my.rutgers.edu/portal">myRutgers</a></li>
                                <li class="sas-item"><a class="sas-link" href="http://scheduling.rutgers.edu/calendar.shtml">Academic Calendar</a></li>
                                <li class="sas-item"><a class="sas-link" href="http://ruevents.rutgers.edu/events/">Calendar of Events</a></li>
                                <li class="sas-item"><a class="sas-link" href="http://sas.rutgers.edu/news-a-events">SAS Events</a></li>
                            </ul>
                        </div>
                        <div class="sas-links-section">
                            <h2 class="sas-links-title">Explore SAS</h2>
                            <ul class="sas-ul sas-links-list">
                                <li class="sas-item"><a class="sas-link" href="http://sas.rutgers.edu/academics/departments-a-degree-granting-programs">Departments &amp; Degree-Granting Programs</a></li>
                                <li class="sas-item"><a class="sas-link" href="http://sas.rutgers.edu/academics/other-instructional-programs">Other Instructional Programs</a></li>
                                <li class="sas-item"><a class="sas-link" href="http://sasundergrad.rutgers.edu/index.php/academics/requirements/list-of-majors-and-minors">Majors &amp; Minors</a></li>
                                <li class="sas-item"><a class="sas-link" href="http://sas.rutgers.edu/for-faculty/795-research-programs-centers-and-institutes">Research Programs, Centers, &amp; Institutes</a></li>
                                <li class="sas-item"><a class="sas-link" href="http://sasip.rutgers.edu/">International Programs</a></li>
                                <li class="sas-item"><a class="sas-link" href="http://lifesci.rutgers.edu/">Division of Life Sciences</a></li>
                            </ul>
                        </div>
                            
                            <div class="sas-links-section">                    <h2 class="sas-links-title">Explore CS</h2>                    <ul class="sas-ul sas-links-list">                        <li class="sas-item"><a class="sas-link" href="https://www.cs.rutgers.edu/about/employment">We are Hiring!</a></li>                        <li class="sas-item"><a class="sas-link" href="https://www.cs.rutgers.edu/research/computer-and-network-systems-list">Research</a></li>                        <li class="sas-item"><a class="sas-link" href="https://www.cs.rutgers.edu/news-events/news">News</a></li>                        <li class="sas-item"><a class="sas-link" href="https://www.cs.rutgers.edu/news-events/cs-events">Events</a></li><a class="sas-link" href="https://www.cs.rutgers.edu/news-events/cs-events">                        </a><li class="sas-item"><a class="sas-link" href="https://www.cs.rutgers.edu/news-events/cs-events"></a><a class="sas-link" href="https://resources.cs.rutgers.edu/">Resources</a></li>                        <li class="sas-item"><a class="sas-link" href="https://www.cs.rutgers.edu/search">Search CS</a></li>                    </ul>                </div>            
            
            
                    
                    </div>
                </div>

                                <nav class="sas-bot-links" aria-label="Secondary Navigation">
                    <div class="sas-container">
                            
            <ul class="sas-ul sas-links-strip">
                <li class="sas-item">
                    <a class="sas-link" href="https://ds.cs.rutgers.edu/">Home</a>
                </li>
                
    
            </ul>
        
                    </div>
                </nav>

                                <div role="contentinfo" class="sas-copyright">
                    <div class="sas-container">
                        <a class="sas-link sas-to-top" href="https://ds.cs.rutgers.edu/assignment-play-2048/#">Back to Top</a>
                        <p class="sas-copyright-p">
                          Copyright 2020, Rutgers, The State University of New Jersey. All rights reserved.<br>
                          Rutgers is an equal access/equal opportunity
                          institution. Individuals with disabilities are
                          encouraged to direct suggestions, comments, or
                          complaints concerning any accessibility issues
                          with Rutgers web sites to: <a class="sas-link" href="mailto:accessibility@rutgers.edu">accessibility@rutgers.edu</a> or complete the <a class="sas-link" href="https://oit.rutgers.edu/accessibility/barrierform">Report Accessibility Barrier or Provide Feedback Form</a>.
                        </p>
                    </div>
                </div>

            </footer>
        </div>
        <div aria-hidden="true">
                <link rel="stylesheet" id="academicons-css" href="./readMe45.md_files/academicons.min.css" type="text/css" media="all">
<link rel="stylesheet" id="font-awesome-css" href="./readMe45.md_files/font-awesome.min(1).css" type="text/css" media="all">
<script type="text/javascript" src="./readMe45.md_files/js"></script>
<script type="text/javascript" src="./readMe45.md_files/override.js"></script>
<script type="text/javascript" src="./readMe45.md_files/owl.carousel.min.js"></script>
<script type="text/javascript" src="./readMe45.md_files/slider.js"></script>
<script type="text/javascript" src="./readMe45.md_files/hoverIntent.min.js"></script>
<script type="text/javascript">
/* <![CDATA[ */
var megamenu = {"timeout":"300","interval":"100"};
/* ]]> */
</script>
<script type="text/javascript" src="./readMe45.md_files/maxmegamenu.js"></script>
<script type="text/javascript" src="./readMe45.md_files/public.js"></script>
<script type="text/javascript" src="./readMe45.md_files/wp-embed.min.js"></script>
<script type="text/javascript" src="./readMe45.md_files/frontend-modules.min.js"></script>
<script type="text/javascript" src="./readMe45.md_files/jquery.sticky.min.js"></script>
<script type="text/javascript">
var ElementorProFrontendConfig = {"ajaxurl":"https:\/\/ds.cs.rutgers.edu\/wp-admin\/admin-ajax.php","nonce":"d41b80b4b0","i18n":{"toc_no_headings_found":"No headings were found on this page."},"shareButtonsNetworks":{"facebook":{"title":"Facebook","has_counter":true},"twitter":{"title":"Twitter"},"google":{"title":"Google+","has_counter":true},"linkedin":{"title":"LinkedIn","has_counter":true},"pinterest":{"title":"Pinterest","has_counter":true},"reddit":{"title":"Reddit","has_counter":true},"vk":{"title":"VK","has_counter":true},"odnoklassniki":{"title":"OK","has_counter":true},"tumblr":{"title":"Tumblr"},"delicious":{"title":"Delicious"},"digg":{"title":"Digg"},"skype":{"title":"Skype"},"stumbleupon":{"title":"StumbleUpon","has_counter":true},"mix":{"title":"Mix"},"telegram":{"title":"Telegram"},"pocket":{"title":"Pocket","has_counter":true},"xing":{"title":"XING","has_counter":true},"whatsapp":{"title":"WhatsApp"},"email":{"title":"Email"},"print":{"title":"Print"}},"facebook_sdk":{"lang":"en_US","app_id":""}};
</script>
<script type="text/javascript" src="./readMe45.md_files/frontend.min.js"></script>
<script type="text/javascript" src="./readMe45.md_files/position.min.js"></script>
<script type="text/javascript" src="./readMe45.md_files/dialog.min.js"></script>
<script type="text/javascript" src="./readMe45.md_files/waypoints.min.js"></script>
<script type="text/javascript" src="./readMe45.md_files/swiper.min.js"></script>
<script type="text/javascript" src="./readMe45.md_files/share-link.min.js"></script>
<script type="text/javascript">
var elementorFrontendConfig = {"environmentMode":{"edit":false,"wpPreview":false},"i18n":{"shareOnFacebook":"Share on Facebook","shareOnTwitter":"Share on Twitter","pinIt":"Pin it","downloadImage":"Download image"},"is_rtl":false,"breakpoints":{"xs":0,"sm":480,"md":768,"lg":1025,"xl":1440,"xxl":1600},"version":"2.9.8","urls":{"assets":"https:\/\/wordpress.cs.rutgers.edu\/ds-cs-rutgers-edu\/wp-content\/plugins\/elementor\/assets\/"},"settings":{"page":[],"general":{"elementor_global_image_lightbox":"yes","elementor_lightbox_enable_counter":"yes","elementor_lightbox_enable_fullscreen":"yes","elementor_lightbox_enable_zoom":"yes","elementor_lightbox_enable_share":"yes","elementor_lightbox_title_src":"title","elementor_lightbox_description_src":"description"},"editorPreferences":[]},"post":{"id":3289,"title":"Assignment%20Play%202048%20%E2%80%93%20Data%20Structures","excerpt":"","featuredImage":false}};
</script>
<script type="text/javascript" src="./readMe45.md_files/frontend.min(2).js"></script>

        </div><span id="elementor-device-mode" class="elementor-screen-only"></span>
    

</body><grammarly-desktop-integration data-grammarly-shadow-root="true"><template shadowrootmode="open"><style>
      div.grammarly-desktop-integration {
        position: absolute;
        width: 1px;
        height: 1px;
        padding: 0;
        margin: -1px;
        overflow: hidden;
        clip: rect(0, 0, 0, 0);
        white-space: nowrap;
        border: 0;
        -moz-user-select: none;
        -webkit-user-select: none;
        -ms-user-select:none;
        user-select:none;
      }

      div.grammarly-desktop-integration:before {
        content: attr(data-content);
      }
    </style><div aria-label="grammarly-integration" role="group" tabindex="-1" class="grammarly-desktop-integration" data-content="{&quot;mode&quot;:&quot;full&quot;,&quot;isActive&quot;:true,&quot;isUserDisabled&quot;:false}"></div></template></grammarly-desktop-integration></html>
