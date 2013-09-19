---
layout : post
title :  The MPI Sintel Dataset
category : work
tags : ruby, rails, work, science
---

<a href="http://sintel.is.tue.mpg.de"><img class="img-rounded" src="/media/images/sintel.png" alt="Just a screenshot, nothing to see here!"></a>

Our department's web developer had to step out to have a baby, so I got the chance to dabble a little with Rails again. It's been a while, despite being a massive fan of the framework back in the mid 00's. I got hooked on [sinatra](http://sinatrarb.com) back at Sony when we were putting together our crazy 'Magick' app to manage cloudformation stacks in ec2, and it was very weird to go back to the comparitive heft of Activerecord and scaffolding. It wasn't terrible, and I was kind of handed the reins halfway through so there's a bunch of things I'd have done differently given the time.  
  
## What's the site about?  

So there's this open source movie, right - the Durian project - or [Sintel](http://sintel.org) as the actual thing is called. Big push for [Blender](http://www.blender.org) devs as far as I could see, but very cool in both it's execution and delivery. Because all the assets are open, you can do whatever you like with it as long as you credit the original team. So! Science. Ever heard of [Optical Flow](http://en.wikipedia.org/wiki/Optical_flow)? Because I certainly hadn't. This stuff's really important in the process of helping computers learn how to track and see stuff, so it's a big deal for my group - [Perceiving Systems](http://ps.is.tue.mpg.de). A couple of students have taken this movie and turned it into a massive (the biggest, I believe) dataset describing Optical Flow. Scientists from all over can download this data and then run their estimation algorithms against it to see how 'good' it is. There's a stack of metrics to measure against, none of which I really understand! :)  
  
## Anything exciting?

It's [Rails 3.2](http://rubyonrails.org), which meant lots of new things I wasn't aware of like the asset pipeline and some project layout changes. Had to get down and dirty with [Capistrano](https://github.com/capistrano/capistrano) again for the first time in ages, which was refreshingly fun. It was nice to have something to really tune for speed for multiple deployments. Also had to figure out a way to keep a single sqlite3 instance available across releases, which was a pain. MySQL support for Rails seems to be all well and good still, but complex to manage as a different DB abstraction in more than one environment - wanted to have sqlite3 for dev/staging and then MySQL for prod - didn't happen. Might do in the future if we need to worry about scale, but I don't think we will :D  
  
## Future things?

[Bootstrap 2.1](http://twitter.github.com/bootstrap/) is in there already, which I love to bits. Could probably look at learning more about their javascript plugins, I do like the carousel and the spiffy collapse-tabs. We'll see, eh?  
