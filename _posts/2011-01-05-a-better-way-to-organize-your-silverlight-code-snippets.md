---
layout: post
title: A better way to organize your Silverlight Code Snippets.
excerpt: 
tags: 
comments: true
---

<p>I hate re-writing code. I also hate it when I find a great code snippet on the web and forget to bookmark it or it gets lost in my endless sea of bookmarks. So what do you do to get around this? This is the question that I was asking myself at the end of 2010. How can I get my Silverlight code organized? </p>  <p>My requirements for a snippet manager were:</p>  <ol>   <li>Needs to be FREE. </li>    <li>An easy way to view XAML/C# code behind together in one “view”. </li>    <li>I wanted the ability to store the code snippets in cloud in case my HDD dies. </li>    <li>Searchable Keywords to quickly find code snippets. </li> </ol>  <p>I started looking for a snippet manager that would allow me to do just that and finally found <a href="http://www.snippetmanager.net/">Snippet Manager</a>. </p>  <p>Before going any further I think that one of the most important things to note here is that this software supports 37 languages. It’s not just for Silverlight developers nor C# only guys. The software supports Java SQL and even COBOL. </p>  <p><a href="http://michaelcrum.web713.discountasp.net/files/image_634591076681508101.png"><img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top-width: 0px; border-bottom-width: 0px; border-left-width: 0px; padding-top: 0px" title="image" border="0" alt="image" src="http://michaelcrum.web713.discountasp.net/files/image_thumb_634591076688060185.png" width="369" height="103" /></a></p>  <p>&#160;</p>  <p>Below is a screenshot of the Snippet Manager that shows my Silverlight code snippet. You will notice that I have highlighted two sections. The top part is my XAML and the bottom is my C# code behind. </p>  <p><a href="http://michaelcrum.web713.discountasp.net/files/SNAGHTML18dc4471_634591076733768771.png"><img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top-width: 0px; border-bottom-width: 0px; border-left-width: 0px; padding-top: 0px" title="SNAGHTML18dc4471" border="0" alt="SNAGHTML18dc4471" src="http://michaelcrum.web713.discountasp.net/files/SNAGHTML18dc4471_thumb_634591076768713219.png" width="821" height="440" /></a></p>  <p>I’ve included a sample below of my code snippets so that you can get an idea of how I organized it. Another thing that’s great about this software is that it supports plain text. I added some connection strings in the TEXT section below.&#160; </p>  <p><a href="http://michaelcrum.web713.discountasp.net/files/image_634591076775889311.png"><img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top-width: 0px; border-bottom-width: 0px; border-left-width: 0px; padding-top: 0px" title="image" border="0" alt="image" src="http://michaelcrum.web713.discountasp.net/files/image_thumb_634591076791333509.png" width="302" height="381" /></a></p>  <p>Once you have finished adding your code snippets you can store them in the cloud. I created a FTP directory called “snippets” on my FTP Server and hit the upload button once I am finished adding my new codes snippets. This will allow me to use the code snippets on another computer with this application on my USB Key. See screenshots below:</p>  <p>Enter your FTP credentials below: </p>  <p><a href="http://michaelcrum.web713.discountasp.net/files/SNAGHTML1906f846_634591076804749681.png"><img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top-width: 0px; border-bottom-width: 0px; border-left-width: 0px; padding-top: 0px" title="SNAGHTML1906f846" border="0" alt="SNAGHTML1906f846" src="http://michaelcrum.web713.discountasp.net/files/SNAGHTML1906f846_thumb_634591076824093929.png" width="701" height="355" /></a></p>  <p>Hit the Uploads button on the Toolbar: </p>  <p><a href="http://michaelcrum.web713.discountasp.net/files/image_634591076832986043.png"><img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top-width: 0px; border-bottom-width: 0px; border-left-width: 0px; padding-top: 0px" title="image" border="0" alt="image" src="http://michaelcrum.web713.discountasp.net/files/image_thumb_634591076840942145.png" width="969" height="110" /></a></p>  <p>Login in to your FTP Server and verify the following files are now on the FTP Server:</p>  <p><a href="http://michaelcrum.web713.discountasp.net/files/image_634591076845778207.png"><img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top-width: 0px; border-bottom-width: 0px; border-left-width: 0px; padding-top: 0px" title="image" border="0" alt="image" src="http://michaelcrum.web713.discountasp.net/files/image_thumb_634591076854982325.png" width="490" height="221" /></a></p>  <p>Another great feature of the Snippet Manager is that you can also integrate this into VS2010 by clicking Tools –&gt; External Tools: </p>  <p><a href="http://michaelcrum.web713.discountasp.net/files/image_634591076863094429.png"><img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top-width: 0px; border-bottom-width: 0px; border-left-width: 0px; padding-top: 0px" title="image" border="0" alt="image" src="http://michaelcrum.web713.discountasp.net/files/image_thumb_634591076878382625.png" width="275" height="389" /></a></p>  <p>And setting up your External Screen to point to the Executable:</p>  <p><a href="http://michaelcrum.web713.discountasp.net/files/SNAGHTML190df71d_634591076889146763.png"><img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top-width: 0px; border-bottom-width: 0px; border-left-width: 0px; padding-top: 0px" title="SNAGHTML190df71d" border="0" alt="SNAGHTML190df71d" src="http://michaelcrum.web713.discountasp.net/files/SNAGHTML190df71d_thumb_634591076906150981.png" width="388" height="378" /></a></p>  <p>You can now launch it by going to Tools –&gt; Snippet Manager. If you want you could also a shortcut to launch the program with HotKeys. </p>  <p><a href="http://michaelcrum.web713.discountasp.net/files/image_634591076914263085.png"><img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top-width: 0px; border-bottom-width: 0px; border-left-width: 0px; padding-top: 0px" title="image" border="0" alt="image" src="http://michaelcrum.web713.discountasp.net/files/image_thumb_634591076931735309.png" width="306" height="433" /></a></p>  <p>As you can see this is a nice little program that includes everything needed to organize your code snippets very clean. I didn’t go over every feature but this is something that you might want to download and give it a shot. </p>