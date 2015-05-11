---
layout:     post
title:      "A Brief History of LoDo"
date:       2014-11-31 12:00:00
author:     "James Lord"
header-img: "img/LodoTwilight.jpg"
---

Oasis of Lodo
=============

###Year 1: Rites of Passage (2011)### 
Black Rock City.  After walking the dry and dusty streets, riding through duststorms across the playa, dancing under the stars to the heavy throb of techno, I fell madly, deeply in love with the mad community and complete chaos.  Like so many other denizens of that strange and wonderful place, I wanted not only to participate, but to build a  unique art experiences for others.  I had no idea yet what to do -- art, technology, performance. . .  But it had to be something and had to be on the playa.

###Year 2: Fertility 2.0 (2012)###
Second trip to BRC.  I thought, wow, I like lights and it is really dusty, let me bring some lasers and mirrors.  My bright idea was to bounce a laser beam around 6 mirrors positioned just above the ground.  The playa is so dusty, you should see the beam, which could define a space. The effort failed because it was really boring to create light effects in the back of camp among so many trailers jammed together.  

However, while climbing around one night on a art project shaped like a box, the inspiration hit -- _hey, this remindes me of QBert!  What if we built a human scale QBert!?_  For those of you not familiar with obscure 1980's video games, QBert was a little animal that jumps around on a 3-D pyramid of cubes.  Every cube that he hits changes color.   If you change all the cubes to the same color, you beat that level and get to move on.  Occastionally a snake or some other "bad guy" comes along and chases him.  So the vision  -- a 16' high pyramid of cubes that change color as you walk on them!  My partner-in-grime Chris D'Andrea signed on as well to make this become real.

###Year 3: Cargo Cult (2013)###
During the off season, we got to work.  The vision was a giant pile of plastic opaque cubes (8x8), each with pressure sensors and LED lights in the center.  After pricing out some of the materials, I realized that this may be damned expensive.  Each cube looked to be well over $200, as you need thick (expensive) plastic  -- remember, you could have a  350 pound, drug crazed guy with heels dive bombing off the top.

During this time, I made a trip down to Cool Neon (insert link) in Oakland to look at gear.  One of the guys suggested putting their TCL LEDs controlled by an Arduino (a small microcontroller) into wooden lids.  I drilled out some holes in a small sheet of plywood and started playing.  Cool Neon provides a software library on how to run the lights.  Next up was making a wooden frame and sensor system so we could tell where someone was standing.  Around this time we also decided to scale down to a smaller, lower 4x4 grid.

The first game coded we made was Simon.  The box would "play" a square, then the player would stop on that square.  Then the game would play a sequence of 2 squares, and you step on the same two squares in order.  The game then "plays" 3, then 4, 5, 6, and up to 7.  If you miss any of the sequence, a red X flashes, and the sequence repeats.  Miss three times and you lose.  The "field tests" we conducted at Oakland's Art Murmur went pretty well, but without sound it wasn't too captivating.

My son Robert who had been watching me slave over this work, said _Um, this would be really cool if it played pong..._.  I told him that he was free to program it, but I was too busy making damn thing work.  Three days later, he had version 1 up and running.  Turns out that Pong is a much better game than Simon (Doh!) 

<iframe width="560" height="315" src="https://www.youtube.com/embed/EclHhFcBG7s" frameborder="0" allowfullscreen></iframe>

The last step was to name it and create a site.  We thought of cargo crates on a loading dock, above which a broken sign hangs with only the letters Lo & Do remaining from Loading Dock (remember, Cargo Cult theme).  LoDo...  get it?  Chris painted the boxes camoflauge, then added a sign, desk, light, and other items that might be found in a 1940's Naval airbase loading dock.  We schlepped the boxes, batteries and gear to our camp (Burntown), set it up and flipped it on.  The highlight of the week was coming home in the wee hours of the morning to be challenged by a stranger to a game of pong.  Success! 

<img src="/img/LodoSmall.jpg" align="left" width="300" style="PADDING-RIGHT: 15px;"/>

The downside of placing it in camp is that there are so many lights in the city, that even Lodo with its 400 LEDs disappeared into the mix.  Next year, we were determined to bring it back bigger, brighter, and most importantly -- to the Playa!

###Year 4: Caravansary (2014)###
This year, we really went bigger and better.  We swapped out the Cool Neon lights for some cheaper lights shipped from China - why?  Because instead of 400 lights, we had 2000.  The grid expanded from 4x4 to 6x5, and we put lights into the sides of the boxes.  The Arduino was replaced by a Beaglebone Black running a full linux OS.  We added sound.  Chris repainted the boxes from Cargo Cult camo  to a deep blue green Caravansary oasis color (14 coats!).  Lastly, the flagship game bounced from Pong to Breakout including a custom soundtrack created by Chris' son Mario (we were keeping it in the families.)

All these improvements sound easy, but in reality were just as hard as the original.  I even broke down in tears of frustration once as Caravansary was nearing and nothing seemed to work right.  I finally set my expectations low -- please, please give me just one night when the damn thing works, and I will be happy, estatic even.  Chris and I broke it down from the garage, loaded it into the camper, and brought it east.

We arrived at the gates on Sunday morning, and proceeded to the Artery (the BM Art Coordination folks) to get our spot.  There was a long line, and we hemmed and hawed at the different places we could put it (no - not there!  That are it too bright, it won't stand out!).  We finally settled on the inner Playa, just to the left of the Insanity sign.  We drove out to the site where an Artery-ist pounded a stake in the ground and said _put it here!_  We were off and running.  Late that evening, we were close to setup and called it quits.

![Setting Up on the Playa](/img/LodoOnPlaya.jpg )

The next day we finished.  We rode out to the site and fired up the generator to power it that evening.  Everything came on, people came by and loved it, and it worked great.  Every evening we would fix something that was broken and every night through the week it worked.  My favorite moment came when riding by and I saw one group of burners explaining it to another group.  Chris had done such a great job with the site that it was used even during the day -- we found out that on two separate occations couples had gotten married on the platform! <names and photo?>

This year was bigger, more successful installation than I had dared hope for.  It took more blood, sweat, tears, and $$ than I ever had thought, but we created a fun, unexpected experience for our fellow citizens.

###Year 5 and Beyond###

And what does the future hold?  Lodo will be back on the playa for <BM Event> with more fit, sound and polish.  But its days are numbered.  The pressure sensors & LEDs that drive LoDo are being replaced by large format touch screens (you can find some really cool ones on You Tube), which makes Lodo look quaint.  Rather than move toward even more expensive technologies, I have been wondering about other things... like how to put brightly colored interactive objects in the sky.  How would it feel to walk under an eye in the sky that follows you? If you combining a flat spring with cable or rope, you could create a light-weight geodesic like dome.  With a few helium ballons, perhaps?  Look me up in Burntown, and see if it gets off the ground.