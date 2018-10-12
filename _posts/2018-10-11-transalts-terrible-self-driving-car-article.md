---
layout: post
title:  "Dissecting TransAlt's terrible self-driving car article"
tags:
  - autonomous vehicles
  - new york
overlay: red
published: true

---

TransAlt's Reclaim magazine just published a piece called ["All Hail the Robot Car?"](https://medium.com/reclaim-magazine/all-hail-the-robot-car-8d672221b18e), subtitled "toward a better debate about autonomous vehicles" in my physical copy. I was excited because TransAlt has taken several optimistic stances toward new ideas, such as e-scooters and parking permits. Unfortunately, the article is terrible, and it's not the author's fault (I actually have much respect for them and their work fighting for safe streets). While the online version cites many sources, including academic journals, this piece serves to show just how hard it is to bypass the fluff in self-driving car reporting, and unfortunately adds to the pile of misleading and inaccurate reporting around what could be [the biggest movement back to urbanism](http://urban.codes/posts/new-york-self-driving-car-benefits) since, well, the automobile destroyed it.

{: .lead}
<!–-break-–>

The article starts with discussion of a pretty obvious Cuomo bribe to authorize Cruise testing on our streets, and Uber's killing of Elaine Herzberg. Great opening to put the hype into context. But then we lead into a question:

>How would New York City have to change to accommodate autonomous vehicles? Is that what we want? Do we even have a say?

Why are we assuming we need to change? None of the robotics companies are trying to change anything about infrastructure at this point -- it would greatly simplify the [process of traffic light classification](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/37259.pdf) if we could modify existing infrastructure to relay this information electronically instead of optically. But nobody is doing that, because the proving ground is "can a robot car drive better than a human with the same environment as a human?"

>To figure out the answer, we asked Sam Schwartz, New York City traffic engineer and author of No One at the Wheel: Driverless Cars and the Road of the Future (out in November 2018 from Public Affairs)

Why are they asking Sam Schwartz? He's not a self-driving car industry member. He's a cool guy, for sure, but there are so many better people who could be asked. Why not Lawrence Burns, who has been in this industry since the beginning, and has a book currently published? I will read Schwartz book, but I have a feeling it'll be garbage, because he says:

>Some researchers are saying that don’t think they can solve ‘the pedestrian problem,’ so people will have to wear badges with a transponder to tell the driverless car that a person is walking, or biking, nearby.

Nobody is doing that! This comes from some UC Berkeley researchers who somehow convinced IEEE to [publish them](https://spectrum.ieee.org/cars-that-think/transportation/self-driving/the-selfdriving-cars-bicycle-problem). I can't blame the author of the Reclaim article for believing this, because IEEE *is* a reputable source, as are the sources that cite IEEE. But the fact IEEE published such garbage nonsense is remarkable. If pedestrians and cyclists are such an unsolvable problem, how has Waymo not hit a pedestrian or cyclist in the last 10M miles of testing on public roads? How does *this* work?

<video src="/uploads/waymo_sxsw_bike.mp4" autoplay="true" loop="true"></video>

This is a great example of how much garbage information exists, where best-in-class industry far outpaces lower industry and academia. IEEE Spectrum, an engineering publication, is suggesting that putting transponders on people will solve a robotics problem. Point me to a roboticist in the world who thinks that would ever work. Besides, even if you could get 100% compliance, you now have the problem of dealing with transponder localization...

>Moments when harming a pedestrian could put its passenger at risk confuse driverless cars, 

That's not confusing, that's just a trolley problem people discuss: what is the right answer, and is it ethical for a company to make that call? Chris Urmson, head of Google's project for many years and DARPA grand challenge team leader, basically answered with "if you have to ask that question, you fucked up several seconds ago."

>driverless cars have been found to have a higher crash rate than conventional vehicles

It's not wrong, but it's misleading. What's a self-driving car? Do we count a Tesla on Autopilot? Do we count disengagements that would have resulted in a collision? Do we count fender-benders caused by other drivers hitting a stopped robot, that would otherwise go unreported? As a counter point, Waymo's vehicles drove 10M miles without hitting a human, so that's not bad.

>Driverless cars are also highly susceptible to hacking

This is just a lazy point, in a laundry-list of lazy points. Every car is susceptible to hacking these days, because almost every car is internet connected anyway. Do you have more faith in cybersecurity from Ford Motors or Google? While it's true you can fuck around with classifiers, you can also just push people into the street. It's a lame argument. Let's remember that drivers routinely kill people *on purpose* (sometimes as an attack, sometimes as road rage) and focus on dealing with that, not a hypothetical situation where someone hijacks a robot car. How is that worse than hijacking a normal car?

>With artificial intelligence already proven to amplify our biases, and face recognition software that struggles with darker skin, will driverless cars also be less likely to recognize a person of color waiting to cross the street?

This is actually an interesting point, because it's of course true that software projects have some horrible biases against people of color and other groups who were not thought of by the development team. But it also shows how much better this article would be if they actually interviewed an industry expert in robotics, because pedestrian classification is done via lasers, which have no color perception anyway. But there are some things to think about here, so I won't immediately throw away the point.

In the meantime, let's just look at how unimportant optical can be for pedestrian detection:

<video src="/uploads/waymo_dust.mp4" autoplay="true" loop="true"></video>

>Even if all these kinks get worked out, which seems unlikely

Why? What's the justification? Again, Waymo has driven 10M miles without any of those problems you just mentioned. Why would any of this be *unlikely*?

> The smartest driverless car will still consume more street space, risk more lives, and cause more harm per passenger trip than a bus ride, a bike ride, or a walk.

Okay, sure. It's a fair point, and the following point about self-driving cars pulling people out of public transit is a very real concern of mine too. But let's keep in mind that the status quo is Uber drivers killing people. We can't compare SDCs to the ideal world where nobody utilizes automobiles. Also, a bus can be self-driving.

>technologists have adopted the phrase “pedestrian interference,” as though walking is a glitch in the system

This isn't cited, unfortunately, so I'm not sure where the term comes from. There's an [interesting paper](http://profiles.arts.monash.edu.au/robert-sparrow/files/2017/12/ethics-driverless-vehicles-drunk-robots.pdf) that uses the term, but in context I belive the author is discussing the general concern that, if SDCs are built to yield whenever possible, people may bully them. It's an interesting problem for sure. But this is something that needs to be discussed in the general urbanist community: how do you ensure vehicles, including buses and bicycles, can get move around in an orderly fashion? The cyclist community already hates when people cross in front of them against the light, so while jaywalking is a bullshit auto industry term, it's not like we should abolish courtesy.

>When cars first barrelled into cities a hundred years ago, our street were still playgrounds and marketplaces — a jaywalking paradise, you could say, except the term “jaywalker” had yet to be invented by automakers.

Let's just be clear, [streets weren't exactly safe before the automobile](https://www.nytimes.com/2011/12/25/realestate/the-railroad-tracks-that-turned-a-street-into-death-avenue.html). I'm nitting, though.

>Do you want to live in a driverless city full of cars, or in a city reclaimed from the automobile? Right now, for a little longer, it’s up to us.

The article ends with this question. Unfortunately, as stated in the War on Cars Podcast this week, *we're losing*. Reclaiming our cities completely from cars is an undefined path. Planning policies for self-driving cars that make traffic violence a rarity, greatly reduce energy usage/CO2 emissions, and reclaim parking spaces, are within scope and desirable for urbanists. Writing articles with low quality arguments to *fight* the technology that could liberate us in the shortterm is irresponsible as people continue to die in a never ending fight. For my thoughts on that, [see here](http://urban.codes/posts/new-york-self-driving-car-benefits).
