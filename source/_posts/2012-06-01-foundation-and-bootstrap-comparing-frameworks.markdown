---
layout: post
title: "Foundation and Bootstrap: Comparing Frameworks"
date: 2012-06-01 10:50
comments: true
categories: 
---
Foundation and Bootstrap: comparing frameworks

"Oh no, not another bootstrap vs foundation discussion!"  

Wait, I agree with you!  The last thing we need is another blow by blow comparison between these two frameworks.  A simple google search will get you all the head to head comparisons you can handle.  There is no need for me to add to that clutter.  But I will say I have been a long time (in internet time) fan of Twitter Bootstrap and used it in many projects.  I recently discovered Foundation by Zurb thanks to a co-worker.  I have to say that I kind of want to give it a try on my next project.  There are some really cool and intuitive things I like that I always thought were sort of cumbersome in Bootstrap.
<!-- more -->
First, I like that in Foundation I can use a class to center one of the grid columns.  In Bootstrap, you have to give your div an offset that pushes your content to the middle.  In foundation, adding the center class is all it takes.

Foundation Example: 
{% gist 2852613 %}

Bootstrap Example:
{% gist 2852629 %}

I also really like the form elements in Foundation (the 'nice' form elements).  Bootstrap has the cool glow effect, but I think it may be a bit of an overstep on Twitter Bootstraps part.  It commits te designer to a look right up front.  Foundations form elements are stylized as well, but it is less obtrusive, in my opinion. 

Which leads perfectly to my next point!  I like Bootstraps button style better!  After I just said I think Bootstrap makes style commitments for the user, I say I like the style commitments made on the buttons.  Anyways, I think Bootstrap made better looking buttons for the out of the box user.  The blue color of the foundation buttons I find visually annoying.  That can be easily changed on both frameworks though, depending on taste. 

### Foundation Button
{% img ../images/Foundation-button.png "Foundation Button" %}

### Bootstrap Button
{% img ../images/Bootstrap-button.png "Bootstrap Button" %}

My goal with this post is to point out the pros and cons I found to be important when examining these frameworks.  I get the impression that I will use both in the future.  I feel like Bootstrap is best suited for rapidly prototyping a project with alot of visual bells and whistles.  Foundation feels like something you build with for keeps.  I'll let you know if that changes after my first real use of Faoundation.

