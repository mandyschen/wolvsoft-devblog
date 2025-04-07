---
layout: post
title:  "Assignment #6: Week 4/6 to 4/20"
date:   2025-04-06 21:22:49 -0500
categories: assignments
---

## Building Menu Hi-Fi
My main task for this week was to implement the hi-fi version of the building menu. This was a tricky experience because it was a rather crowded menu, with a few different things going on.

One particular issue I had was that the button that is selected is supposed to "flip" when its clicked. This was interesting to implement, and it definitely took me a bit of time to fix issues (like disappearing the button when clicked, having both the flipped and unflipped appear at once, etc.). Fixing this issue was very satisfying, and I love the effect that it had when completed.

<img src="{{ 'assets/hw6/figma-building-menu.png' | relative_url }}">

*What the building menu is supposed to look like according to the Figma.*

<video width="640" height="360" controls>
  <source src="{{ 'assets/hw6/finish-build-menu-hifi.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>
*The finished building menu.*

## Fixing Smithy Hi-Fi Implementation
I also received feedback that my smithy hi-fi implementation wasn't exactly correct. I was supposed to add a scroll feature where you could select from a list of objects, and then after clicking on a specific object, you will be taken to more details about that item. What I had previously was that there was no scroll at the beginning, it just went to some blank item. 

Adding this feature was actually a bit difficult because it required quite a bit of code and changes to the functionality of the buttons. However, this was a lot of fun and a great learning experience because I got the chance to go back and see how I/others had implemented the smithy functionality.

<video width="640" height="360" controls>
  <source src="{{ 'assets/hw6/fixed-smithy-hifi.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>
*The corrected smithy menu.*

## Conclusions


## Hours Breakdown
- Meeting: 4 hours
- Building menu hi-fi: 6 hours
- Fix smithy menu, add scroll feature: 4 hours

Total: 