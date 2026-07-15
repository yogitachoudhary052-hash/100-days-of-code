# Day 05

# Images
<img src="images/profile.jpg" alt="Profile Photo">

- used to display images on web pages
- ATTRIBUTES:- 
- src, alt, height, width
- if the image is not shown due to some reason alt is message which decribes what the image looks like in words.

# audio

- this tag plays audio files
- <audio controls>
    <source src="song.mp3" type="audio/mpeg">
</audio>

- ATTRIBUTES:- 
- controls: shows play/pause controls
- autoplay: starts playing automatically
- loop: repeats the audio
- muted: starts muted

# Video 

- displays videos directly on your webpage.

- <video controls width="500">
    <source src="movie.mp4" type="video/mp4">
</video>

- ATTRIBUTES:
controls
autoplay
muted
loop
poster (shows an image before the video plays)

<video controls poster="thumbnail.jpg">
    <source src="video.mp4" type="video/mp4">
</video>

# iframe

- Instead of uploading a video, you can embed one from YouTube.

<iframe
width="560"
height="315"
src="https://www.youtube.com/embed/VIDEO_ID">
</iframe>

# favicon

- A favicon is the small icon shown on the browser tab.

<head>
<link rel="icon" href="logo.png">
</head>

<link rel="icon" type="image/png" href="favicon.png">

# Semantic HTML
- Semantic tags describe the purpose of the content instead of just its appearance.

- <header>
<nav>
<section>
<footer>

# header

- Represents the top section of a webpage.

<header>
<h1>My Portfolio</h1>
</header>

sually contains:

Logo
Website title
Navigation

# nav
Contains navigation links.

<nav>
<a href="#">Home</a>
<a href="#">About</a>
<a href="#">Projects</a>
<a href="#">Contact</a>
</nav>

# main

<main>

- Contains the primary content of the page.

<main>

<h2>About Me</h2>

<p>I am learning Full Stack Development.</p>

</main>

# section
- Groups related content together.

- <section>

<h2>Skills</h2>

<ul>
<li>HTML</li>
<li>CSS</li>
<li>JavaScript</li>

</ul>

</section>


# article

Represents content that can stand alone.

Examples:

Blog posts
News articles
Product cards


<article>

<h2>HTML Basics</h2>

<p>HTML is used to create web pages.</p>

</article>


# aside
- Contains content related to the main content but not essential.

Examples:

Sidebar
Advertisements
Related posts

- <aside>

<h3>Latest Articles</h3>

<ul>

<li>CSS</li>

<li>JavaScript</li>

</ul>

</aside>

# footer
- Represents the bottom section of the webpage.

Usually contains:

Copyright
Contact details
Social media links
Privacy policy

-<footer>

<p>© 2026 Yogita Choudhary</p>

</footer>


# HTML Entities

- Some characters have special meaning in HTML, so you use entities to display them.

- Common Entities
Character	Entity
<	&lt;
>	&gt;
&	&amp;
Copyright ©	&copy;
Registered ®	&reg;
Rupee ₹	&#8377;
Non-breaking space	&nbsp;

- Example:

<p>&copy; 2026 Yogita Choudhary</p>

<p>Price: &#8377;500</p>

# meta tags

- Meta tags provide information about the webpage to browsers and search engines.

- <head>

<meta charset="UTF-8">

<meta name="viewport"
content="width=device-width, initial-scale=1.0">

<meta
name="description"
content="Portfolio Website">

<meta
name="keywords"
content="HTML,CSS,Portfolio">

<meta
name="author"
content="Yogita Choudhary">

</head>

- Common Meta Tags
Meta Tag	Purpose
charset	: Defines character encoding (usually UTF-8).
viewport : Makes the page responsive on mobile devices.
description :	Brief summary of the page for search engines.
keywords :	Relevant search keywords (less important today but still valid).
author : Specifies the page author.

