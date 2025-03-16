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

## Conclusions

## Hours Breakdown
- Meeting: 4 hours
- Main tower UI: 3 hours
- Try to fix merge errors: 2 hours
- Reimplement changes (smithy, tavern, hire, etc.): 6 hours

Total: 13 hours