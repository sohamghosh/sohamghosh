<!DOCTYPE html>
	<html>
		<head>
			<title>{{ page.title }}</title>
			<link rel="stylesheet" type="text/css" href="/css/main.css">
		</head>
		<body>
			<nav>
	    		<ul>
	        		<li><a href="/">Home</a></li>
				<li><a href="/blog">Blog</a></li>
	    		</ul>
			</nav>
			<p/>
			<div class="container">
				<h2>{{ page.title }}</h2>
				<hr/>
				{{ content }}
			</div>
			<br/>
			<footer>
	    		<ul>
	        		<li><a href="https://github.com/sohamghosh/sohamghosh">Github</a></li>
				</ul>
			</footer>
		</body>
	</html>
