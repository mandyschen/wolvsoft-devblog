---
layout: post
title:  "Assignment #4: Week 3/9 to 3/23 (in progress)"
date:   2025-03-09 21:22:49 -0500
categories: assignments
---

## Main Tower Implementation
One task that I was assigned was implementing the main tower menu. There were two different pages in this implementation, and there was a toggle that would separate each page. There were a few things that existed in the game that were not directly depicted in the Figma, but I was able to communicate with the designers and other developers in order to figure out where to accurately place everything.

I was able to "grab" the images from the Figma file and add them to the actual implementation. This allowed me to have perfect spacing for the egg and for the paneling at the edges.

I created an update for this and pinged out director, and I received feedback to fix the fonts and the stretching in the resource images. Once I fixed these issues, I recieved a thumbs up on this change.

<video width="640" height="360" controls>
  <source src="{{ 'assets/hw4/main-tower-done.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>
*The finished UI/UX for the main tower.*

## Tried to Fix Merge Request Issues
I saw that my merge request was denied because there were issues that arose from merges that occurred in between when I submitted my resolved changes and when it was time to merge my changes.

I went through and I tried to fix my branch. However, similar to previous times when I was resolving merge conflicts, the `WorldScene.unity` file was giving me many issues. This was extremely frustrating because I had already spent a lot of time trying to workshop the changes I had implemented in order to fix the merge issues.

In addition, when I looked at the updated main branch, I realized that there were a lot of changes that had been made to the main branch that were not "pulled" into the branch I was working on. I realized that this was likely because I had accidentally overrode these changes when I was resolving merge requests.

After a couple hours of working on this issue, I thought that maybe starting from scratch with my new knowledge would be a better endeavor.

## Fixed Other Implementations
I had asked for help during the meeting as to the best ways to resolve merge conflicts. I got a lot of useful advice, but one thing that was mentioned that by editing just the prefabs, I would be able to resolve a lot of the conflicts. I remembered in the past before I learned what prefabs were and how to use them, I had made some changes outside of the prefabs, and I thought maybe that was what had been causing these issues continuously now. Furthermore, I implemented the smithy UI completely outside of its prefab, which was likely a massive part of the reason as to why there were so many conflicts whenever I pulled from main.

I decided to use my past implementation as a reference and to add the UI/UX implementations off a fresh branch so that I could once and for all resolve these issues. I edited the prefabs directly as much as possible, and I was fortunately able to heavily reference the existing branch and directly copy/paste certain parts, so it was definitely a lot quicker than recreating everything from scratch.

With my new knowledge, I was able to more efficiently create the menus for the smithy and the tavern (alongside its hiring menu). I also updated the resource header. I fixed some of the smaller issues I had overlooked in the previous branch such as font and slight stretching/warping of the images.

<video width="640" height="360" controls>
  <source src="{{ 'assets/hw4/smithy-tavern-done (1).mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>
*The finished UI/UX for the other buildings.*

## The Dungeon
For my next task, I was assigned to work on implementing the UI for the dungeon. This was a relatively straightforward task, but it involved a lot of meticulous work. Fortunately, the fact that the UI had repeatable parts that could be handled with prefabs made the process a lot quicker.

<img src="{{ 'assets/hw4/dungeon-figma-ui.png' | relative_url }}">
*What the dungeon UI should look like according to the Figma.*

<img src="{{ 'assets/hw4/finished-dungeon-ui.png' | relative_url }}">
*What the dungeon UI looks like after I implemented it.*

An extension of this task included implementing the dungeon minigame. I was unsure how to handle this particular task because it appeared as though there was some groundwork for the mini game laid down, but it wasn't particularly fleshed out. Also, what currently existed was with text instead of actual graphics described by the Figma.

When I was implementing the game, I made sure that I was including all of the situations inside the Figma. I saw in previous discussions about the dungeon that we intended the dungeons to have specific routes, so while I currently made the game situations randomly choose which "situation" to be in, I ensured that the code was easily modifiable to be able to take into account that the paths won't be random/arbitrary in the future.

<img src="{{ 'assets/hw4/dungeon-mini-game-figma.png' | relative_url }}">
*Some of the scenarios in the dungeon mini game described in the Figma.*

When I was done implementing the game, I made sure that I playtested a few times. I included a few details like enemy health and attacks, player health, disabling buttons in certain situations, etc. that I only caught after playtesting and realizing that certain things were needed to make the game more effective and "bug-proof." 

<video width="640" height="360" controls>
  <source src="{{ 'assets/hw4/mini-game-ui-trimmed.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>
*The finished UI/UX for the main tower.*

## Game Developers Conference 
Unfortunately, I was not able to attend the Game Developers Conference with the team, but I decided to watch a few of the most popular talks to gain some new perspectives. 

I decided to watch:
1. Video Game Rx: Narratives as Therapy
2. Death to the Three act Sturure! Toward a Unique Structure for Game Narratives
3. You Don't Need a F-ing Publisher
4. Sunset Overdrive: Transitioning from Linear to Open World Design
5. Building a Paper Prototype For Your Narrative Design
6. Less is More: Designing Awesome AI for Games

While they were all extremely interesting, and I learned a lot from listening to their perspectives and lessons, the talk "You Don't Need a F-ing Publisher" really stood out to me. 

I think it's uncommon for conversations about publishing to take place in academic settings (such as in a class). However, I think if someone wanted to take the leap to publish a game, it's important to know how to not get taken advantage of by predatory publishers. The speaker was humorous, but he was also extremely straightforward and made sure that the audience understood publishers gave the basic needs (funding, marketing, production, and distribution) but should also provide more to be truly beneficial (creativity and enthusiasm, a state and the spotlight, a personal relationship, and brutal honesty). I think he delivered the information in a great way, and in the future, if I want to publish my own game, I will definitely keep his ideas in mind.

## Conclusions
I think one strategy that I want to do in the future is to know when to give up and restart and use the knowledge I gained in that failure to improve. I kept on trying to resolve merge conflicts from a branch that I had a lot of work done on, and I was unwilling to recognize that I needed to start from scratch because of some mistakes I made way earlier on in the branch. Fortunately, I was able to recreate most of what I had done in a far more efficient way because of what I had previously learned, and I recognize that I should have done this after I had been struggling with the merge conflicts the first time around.

## Hours Breakdown
- Meeting: 2 hours
- Main tower UI to match Figma: 3 hours
- Try to fix merge errors: 2 hours
- Reimplement changes (smithy, tavern, hire, etc.): 6 hours
- Dungeon UI to match Figma: 3 hours
- Implement dungeon mini game: 5 hours
- Watch GDC talks: 4 hours

Total: 25 hours