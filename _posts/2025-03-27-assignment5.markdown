---
layout: post
title:  "Assignment #5: Week 3/23 to 4/6"
date:   2025-03-09 21:22:49 -0500
categories: assignments
---

## IGDA Ann Arbor: The Rise of Roblox
I saw the announcement for an event on March 27 called IGDA Ann Arbor: The Rise of Roblox. I thought this was an interesting topic, and I decided to join on Discord (unfortunately, I could not attend in person). Although there were some audio issues at first, they were quickly resolved, and the topics were super interesting.

At the beginning, people got the chance to present what they were working on. I thought that the first presenter with the multiplayer engine was extremely fascinating! One of the things I find most intimidating in game development is definitely on how implementing multiplayer would work. When he said that the engine would handle the multiplayer part of the process, I was really interested in how that would work. I believe I heard him say that he was planning on adding things like physics, animation, etc. before releasing, but this is definitely something I would like to keep an eye out for and learn more about.

<img src="{{ 'assets/hw5/igda-screenshot.png' | relative_url }}">
*Screenshot from the IGDA event.*

The presentation about UGC also touched on a topic that I have been interested in: developing on Roblox. Even though I really like making games, it's hard to find people who would enjoy playing unfortunately. I thought Roblox was the perfect solution, and with what the presenter said about the multitude of ways to earn money through the platform, it's definitely something I want to take a deeper look at. Unforunately, I have no experience with Fortnite, so I didn't feel as drawn to potentially developing an island, but it was definitely still interesting to hear about.

## Rain Splash Animation
I needed a "splash" animation for the rain when a rain drop ended/landed. This was an interesting task for me to take on because I didn't have a ton of experience with animating anything at all. I also did not have experience with integrating an animation within a Unity game. I didn't see one provided by the art team, and I thought that this would be a great opportunity to practice animating, even if it may be replaced.

Here is one of the first attempts I made:
<img src="{{ 'assets/hw5/first-splash.gif' | relative_url }}">

*One of my attempts at the rain splash animation.*

Here is the animation that I ended up using in the final:
<img src="{{ 'assets/hw5/final-splash.gif' | relative_url }}">

*The final rain splash animation.*

## Implementing Rain Effects
My main task for this week was to create a rain effect. This was a really interesting task because I had to learn to use particle effects, and this was something that I had never used before. It was a little overwhelming even with looking at online resources and tutorials because things definitely differed from game to game. 

A lot of the time I spent was also with experimenting with certain elements of the rain effect. It was difficult to manage the quantity and speed of the rain so that the rain wasn't overwhelming, but it was still observable. However, this was a really cool learning experience, and I got to experiment a lot with the different variables and categories inside the particle effects system in Unity. I'm relatively happy with the end result of the rain, and I think it's able to clearly convey the fact that it's raining.

<video width="640" height="360" controls>
  <source src="{{ 'assets/hw5/rainy-effect.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>
*What the final rain effect looks like in the game.*

## Merge Conflicts and Debugging Other Changes
For the merge request from a couple of weeks ago, there were some minor final merge conflicts that I had to resolve again in order to finally merge, and once I resolved those, I was happy to see that my changes were merged. This time resolving the conflicts did not take as long because I had previously changed the code to make it more easily merged.

<img src="{{ 'assets/hw5/merged-all-conflicts.png' | relative_url }}">

*Merged UI/UX changes into the final game.*

There were also some more changes that I had to make on another branch. For the dungeon UI, I noticed that the skill and health bars were being filled vertically instead of horizontally, and weren't exactly aligned with where they should be. I fixed that issue and now, the UI looks a lot cleaner and more readable.

I got feedback that the cancel button in the main tower should toggle to the stats screen (it currently wasn't doing anything at all). This was another change that I made and implemented into the same merge request as the dungeon.

<img src="{{ 'assets/hw5/fixed-dungeon-ui.png' | relative_url }}">

*The fixed dungeon UI.*

## Header Implementation
One of my tasks for this week was to implement the graphic and final implementation for the header. This was a relative straightforward process, and because there was already a base that closely matched where everything in the header was meant to go, it wasn't too difficult. However, I accidentally made all of my changes outside of the prefab, so I had to restart my progress and make sure that I was making changes inside of the prefab to prevent merge and other issues. It was also surprisingly difficult to extract all of the elements from the Figma file. I often had to delete/hide certain items to make sure that I was getting a "clean" version of the image without text or other elements that I would need to specifically add in Unity.

<img src="{{ 'assets/hw5/new-header.png' | relative_url }}">

*The new header*

## Smithy Implementation
Another one of my tasks was to implement the final version of the smithy UI. This was far less straightforward than the header because things often did not map one to one with the previous implementation. I had to make a few decisions regarding how I should connect the different pieces in the menu, and it was definitely an interesting learning experience. There was a lot of minor tweaks that I had to make in order to make sure that everything not only worked, but also closely matched what was in the Figma. However, I ultimately think that I did a good job and that the smithy UI was able to closely match what was described.

<video width="640" height="360" controls>
  <source src="{{ 'assets/hw5/smithy-new-ui.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>
*The final smithy UI.*

## Conclusions
I think I learned a lot about how to manage my time effectively. I did a large bulk of the work earlier in the week, so that I could receive feedback and ask for clarification on certain things throughout the week, and I wasn't rushing towards the end to finish my assigned tasks. I think this was a great decision because I was really able to make things that I was proud of, and I felt as though I was never under a ton of stress, even though I had a lot of things on my to do list this week.

## Hours Breakdown
- Meeting: 4 hours
- IGDA event: 2.5 hours
- Drawing rain splash animation: 1.5 hours
- Rain effects: 6 hours
- Resolve merge conflicts and other changes: 2
- Header: 1.5
- Smithy: 6.5

Total: 24