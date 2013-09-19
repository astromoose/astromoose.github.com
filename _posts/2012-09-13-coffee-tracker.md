---
layout : post
title :  Coffee Tracker and the Magic Meteor
category : chaff
tags : fun, nodejs, meteor, javascript, caffeine
---

[![Just a screeenshot](/media/images/coffeetracker.png)](http://coffeetracker.meteor.com)

I've been unreasonably excited about [Meteor](http://www.meteor.com) since finding out about it a few weeks ago. Now I've actually done something with it!
  
## What exactly have you done?

We got a goooorgeous new espresso machine a few months ago, and now we're all kind of getting into the swing of using the thing. I went to grab a coffee the other day and realised we were a crack team of IT development genii and we could do better than the scrap of paper sellotaped to the wall with checkmarks on it next to our names...
  
## Yes, so what EXACTLY have you done-

I took the 'leaderboard' example that meteor ships with (`meteor create --example leaderboard`) and changed it a bit. I added some prettiness (the easy bit) and some functionality (the hard bit). Had to learn a bit more javascript/nodejs, a little MongoDB and brush up on my css. Was fun!
  
## Future things?

Would be nice if I could track/show shots consumed per day/week/month/year, but that'd involve more complexity on the mongodb end which I will need to really read up on. I would like to investigate moving it to redis as well so I could use [redistogo](http://redistogo.com). Maybe some kind of OAuth integration, so people could link their 'Connoiseur' with their twitter/github/facebook account. I dunno, maybe overkill :)
