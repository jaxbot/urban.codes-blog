---
layout: post
title:  "How self-driving cars could benefit New York"
tags:
  - autonomous vehicles
  - new york
overlay: red
published: true

---

I've been meaning to write this ever since Cruise announced plans for testing in Manhattan. Then I started to write it after Uber's fatal crash. This week seems like a perfect time to actually finish it, since TransAlt's Reclaim magazine and The War on Cars podcast are talking about the subject, and Waymo is reported to launch their driverless service by end of year.

{: .lead}
<!–-break-–>

## Why I care

I've spent the last couple years [studying self-driving cars](https://jaxbot.me/articles/self-driving-car-koala-7-11-2015), the past year [taking courses about building software for them](https://github.com/jaxbot/udacity-car-projects), and overall have been passionate about their development for as long as I've been passionate about getting rid of cars, period. I'm also a cyclist, an urbanist, and an accomplished NUMTOT. Since it seems responsible to disclose, I do own a tiny amount of stake in Alphabet, which owns a company that builds these things. I don't speak for my employer, and my post history should show my opinions of the tech have existed long before I thought I'd have a tech job.

# The argument for self-driving cars in New York

Increasingly so, urbanists are at war against self-driving hype. This is understandable, but I believe misguided. While the fears of a dystopia where autonomous vehicles conquer the road aren't far fetched, we have a serious opportunity to remove the biggest impediments to livable cities today: parking, vehicle ownership, and *drivers*.

## The status quo

>"We've been fighting for bike lanes for 15 years, and it's not fucking working. We're losing. We're losing to the cars. We are losing the war on cars. And I feel like there is some opening now, where if we can somehow leverage this autonomous vehicle excitement and transformation, to fundamentally change the way we do cars. Because just painting stripes on the street isn't enough." -Doug Gordon, [The War on Cars Podcast](https://www.patreon.com/posts/war-on-cars-21662594), episode 2.

The status quo sucks, full stop. The narrowest streets are still home to two lanes of parking, and making any safety or transit improvement is met with fierce opposition, even to the prospect of preventing double parking. Uber vehicles clog the streets, stopping in bike/bus lanes. Citywide, around 200 people are killed by drivers yearly, and despite our mayor "supporting" Vision Zero, the populace at large seems content with this. Bus transit (and subway shuttle buses) suffer in increased congestion, leading to a cycle of increased private vehicle use. Cycling is on the rise, but the numbers are barely moving in the right direction, and building new safe infrastructure is a fight, even when someone has died in the current design.

Drivers have no regard for compliance. We build protected bike lanes because drivers disobey the laws of the road with impunity. And even when we build concrete walls to separate bike lanes and automobile traffic, drivers blame [the wall for being dangerous](https://newyork.cbslocal.com/2017/11/09/queens-problematic-bike-lanes/).

<img src="/uploads/bike-lane-crunch.jpg" alt="A car impaled on a concrete barrier separating the road from the bike lane.">

It's asinine that the most inventive solution we have to building safer streets is building roads that are idiot proof and allow drivers to remain as ignorant as ever of the laws only govern our streets on paper. Protected bike lanes aren't cyclist infrastructure. They're driver infrastructure, for the typical driver who barely pays attention to their surroundings.

## The opportunity

On the horizon is a set of technologies that have the potential to change this: a vehicle that is governed by its code, built to follow the law, with sensors that look 360 degrees simultaneously and can see through objects. On paper, traffic crashes could be as rare as train crashes, and deaths become rare and publicly discussed in detail. Vehicles can become an appliance as regulated as an elevator, integrated into the transit system, and purpose-built for their use and environment. Gone could be the days of the 'occasional use' vehicle, where SUVs are purchased for the occassional need for a large vehicle. Individuals outside of walkable transit coverage, or who are not ambulatory, could ride in small vehicles like the Firefly prototype to access services, which would require less street space & energy to move, and reduce dependence on privately owned vehicles. Vehicles could shift dramatically to fleet operation, removing the constant wasteful storage of vehicles moved only for alternate side parking.

Self-driving cars are a seemingly unstoppable wave -- a force with so much hype, so much lobbying, that efforts to fight it will surely be lost the same way efforts to stop the automobile as a whole are lost. Instead of fighting the movement, urbanists and self-street activists should leverage this as an opportunity to banish drivers from our cities and focus on what policies will reduce auto use and promote transit -- the rules are unwritten, and the conversation should be "how do we make this work?", not "how do we stop this?" Because no matter how dystopian AVs could be, our current situation is almost certainly worse.

But of course, there's a tremendous amount of bullshit out there. Anyone who thinks a robot car city could/should look like this understands neither cities nor robots:

<video src="/uploads/autonomous-intersection.mp4" autoplay="true" loop="true"></video>

<cite>[What a driverless world could look like | Wanis Kabbaj](https://www.youtube.com/watch?v=OlLFK8oSNEM&t=3s), an example of the endless amount of bullshit AV discussion that demonates the space.</cite>

I'm not going to entertain the idea of the intersection that assumes pedestrians and cyclists don't exist. Nor will I bother discussing L3 and below 'driver assistance' technology (it's well-documented garbage). There's a lot of players in this space, and there's basically only two I would currently trust to even *test* on our streets. Let's look at what best-in-class tech looks like today, and calibrate what our *minimum* expectations should be for anyone trying to roam our streets.

## What best-in-class tech looks like

This is obviously cherrypicked, but I can't help but balk at the remark from police after Elaine Herzberg was killed by an Uber test vehicle that the victim came out of the shadows. Uber's vehicles, like Cruise and Waymo's, are outfit with cameras, LIDAR, and radar. The sensing hardware is capable of seeing in 360 degrees, night or day, sometimes even through obstacles. Uber demonstrated an extreme failure of their software to determine the pedestrian was crossing, with ample time to have detected this. On the other hand, companies with a higher regard for safety tell a compelling story.

<video src="/uploads/waymo_sxsw_bike.mp4" autoplay="true" loop="true"></video>

In this clip, the car is following a bicycle through an intersection when another bicycle comes into frame, contraflowing in the lane the car wants to turn to. In the same frame the bike becomes visible to the car, the planner predicts the path will collide and slams on the brakes, yielding to the cyclist. All while tracking several cars in frame and two pedestrians in the crosswalk on the left -- and this video is years old.

Uber took an opportunity for a machine with superhuman vision and prediction to save lives, and instead turned it into a killing machine with powered by their subpar tech. No vehicle should be tested on public roads in this fashion unless it can stand up to the test above.

<video src="/uploads/waymo_dust.mp4" autoplay="true" loop="true"></video>

This clip dropped today in [Waymo's 10 million mile announcement video](https://www.youtube.com/watch?v=ROAwXEqDk7k) -- it's a demonstration of pedestrian detection while driving during a dust storm, which limits optical camera use and has other reprocussions for laser, unless you're one of the top robotics groups for the past 10 years. Am I biased here? Of course. This is the longest running robotic car group in the world, and they have the best tech. Their examples should be our minimum expectations for anyone wanting to test or operate in the city (they've gone 10M miles without causing any injuries, which is more than we can say of people like State Sen Marty Golden).

## Conclusion

The status quo is terrible, and efforts to change it have made slow progress, sometimes even just to prevent regressions (think NYC's speed camera fight this year). Suddenly, an opportunity to reshape street use, vehicle use, and remove drivers from the equation is on the table. Urbanists need to be having informed conversations on how to leverage this technology to move towards the goal of safe, sustainable, walkable cities. Fighting these efforts are misinformed, futile, and frankly, when an option is on the table to cut 30k+ deaths a year on USA streets has presented itself, irresponsible. We all hate cars. But let's get rid of drivers first.

Next steps: if you want to get informed about this space, read Lawrence Burns' Autonomy. It's one of the few non-bullshit works out there that covers the industry.
