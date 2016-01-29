---
layout: post
title: Adding features
excerpt: "Outreachy - Week 6 and 7"
modified: 2016-01-24
tags: [outreachy, week6, week7, gnome, FOSS, polari, ]
comments: true
---

<p>
The past two weeks I've been implementing the new feature of polari (you can see the mockup at <a href="http://belinhacbr.github.io/fresh-designs/">this</a> post)  
</p>

<p>
This is the pre-revision implementation:
</p>
<figure class="third">
<img src="http://i.imgur.com/RP0P7ZS.png">
	<!-- <a href="http://i.imgur.com/CyCD2Ai" title="Connected"><img src="http://i.imgur.com/CyCD2Ai"></a> -->
	<a href="http://i.imgur.com/RP0P7ZS" title="Connecting"><img src="http://i.imgur.com/RP0P7ZS"></a>
	<a href="http://i.imgur.com/EFz3K2h" title="Connection error"><img src="http://i.imgur.com/EFz3K2h"></a>
	<figcaption>Connection popover - Connected, Connecting and Connection error</figcaption>
</figure>
<p>
Basically, I had to add the change an existing error popover and make it show in every status. To do this, I had to modify a function to update the status label which is called when the connection status change. 
</p>
<p>
My biggest challenge in this implementation was the user interface. I never implemented an interface with Gtk before and I found myself hitting the wall many times. 
The worst part was not knowing how to nest objects or which class to use do to something, most of the times I didn't even know where to look for a reference, fortunately, as always, I had guidance from my mentor. 
</p>
<p>
For this implementation I created <a href="https://bugzilla.gnome.org/show_bug.cgi?id=709984">this bug</a>. You can check the code and It's evolution there!
</p>
<p>
Next week I'll be receiving the revision and making possible fixes in order to get everyting done for version 3.19. See you soon earthlings!
</p>
