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
<figure>
	<a href="http://i.imgur.com/PNlqYwA" title="Connected"><img src="http://i.imgur.com/PNlqYwA"></a>
	<figcaption>Connection popover - Connected</figcaption>
	<a href="http://i.imgur.com/xdfL71k" title="Connecting"><img src="http://i.imgur.com/xdfL71k"></a>
	<figcaption>Connection popover - Connecting</figcaption>
	<a href="http://i.imgur.com/UF2RzBY" title="Connection error"><img src="http://i.imgur.com/UF2RzBY"></a>
	<figcaption>Connection popover - Connection error</figcaption>
</figure>
<p>
Basically, I had to add the change an existing error popover and make it show in every status. To do this, I had to modify a function to update the status label which is called when the connection status change. 
</p>
<p>
My biggest challenge in this implementation was the user interface. I never implemented an interface with Gtk before and I found myself hitting the wall many times. 
The worst part was not knowing how to nest objects or which class to use do to something, most of the times I didn't even know where to look for a reference, fortunately, as always, I had guidance from my mentor. 
</p>
<p>
For this implementation I created this bug. You can check the code and It's evolution there. ;D
Next week I'll be receiving the revision and making possible fixes in order to get everyting done for version 3.19. See you soon earthlings!
</p>