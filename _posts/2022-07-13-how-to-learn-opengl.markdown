---
layout: post
title:  "How to learn OpenGL"
date:   2022-07-13
categories: Learning
---
<html>
<head>
<meta charset="utf-8">
<title>How to learn OpenGL</title>
</head>

<body>
	<p>Copyright from Quora</p>
	<p><strong>I'm learning OpenGL currently and I feel like I don't know anything. I don't see myself finishing anything in the future. What are your experiences as a beginner while learning OpenGL?</strong>
</p>
	<p>Sadly for you, I began with “IrisGL” - which was the (very simple) precursor of OpenGL.
	  
	  Silicon Graphics (who invented OpenGL) kindly invited me to convert my software from IrisGL to OpenGL at their offices - using the very first (hand-made!) OpenGL hardware.</p>
<p> Unfortunately, they only had free time on it from 2am until 7am - so I was kinda brain-stunned through most of that week!
	  
	  Anyway - I’ve grown up with OpenGL incrementally - and it’s changed immensely over those decades.
	  
	  The best way to learn it is to find a good set of sequentially more complex example programs. </p>
	<ol>
	  <li>You’ll start with opening a window and drawing a triangle…working steadily to a spinning textured cube and so forth.
	    
	    There are really five skills you need:
	    
	    You need to know how to open an OpenGL graphics window (a “rendering context”) to draw stuff onto. This will start off as a piece of “boilerplate” code that you won’t understand - or need to understand - for a very long time. </li>
	  <li>You need to learn the GLSL programming language so you can write and load shader software.	  </li>
	  <li>You need to know how to load up vertices that describe a 3D object.	  </li>
	  <li>You need to know how to load up texture maps to provide surface detail.</li>
	  <li> You need to know how to set up to draw a 3D object with a given shader and a given set of textures.	  </li>
</ol>
	<p>Unfortunately, you need to know at least four of those five things (maybe you don’t need textures to start with) before you can draw anything at all! Since the first thing (opening a window) can be copy-pasted from example code - you can get away with just three things.</p>
	<p> Since you can’t learn all three of those things in parallel - you NEED to start with a working program that does all five of these things and gradually figure out what each bit is doing.	  </p>
	<p>Then you can gradually build on that knowledge until you have everything you need to write whatever it is you were thinking of writing.
	  
	  You don’t need to know all of it to be useful. </p>
</body>
</html>
