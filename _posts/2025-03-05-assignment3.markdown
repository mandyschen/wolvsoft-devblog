---
layout: post
title:  "Assignment #3: Week 2/23 to 3/2"
date:   2025-02-23 23:22:49 -0500
categories: assignments
---

## Fixing the Smithy UI/UX
During the meeting, the studio director went over the implementations I made for the Smithy UI/UX. During this time, I wanted to ask how exactly the interface should look while something is being built (a feature that the Smithy interface has).

Previously, I had assumed that we would be able to have multiple weapons, armor, and charms being built at the same time, so I tried to lay out a foundation to create that. However, we discussed that instead, we should make it so that when something is being built, have the screen "lock" so that other things cannot be built or viewed during the build time.

After receiving this feedback, I went to work in modifying the previous implementation so that the Smithy would behave the way that the director stated. I had to make sure that the timer stayed "alive" during the entire time (even when clicking off the smithy and back on) as well as disabling other interactions when something was being built.

## Creating a Merge Request
I was also told during the meeting to create a merge request, and this was a massive challenge for me. I really struggled to create something that worked and implemented both my changes and the new merged to main changes that had occurred while I was developing.

Previously, I did not have a ton of experience with merging my branch with a massive existing code base. Usually, I was the sole person in charge of the project, or my teammates and I would pull each other's changes before developing. So, I usually did not deal with merge conflicts.

However, there were a LOT of merge conflicts when I tried to merge my branch with main, and this was incredibly difficult to work with. I really struggled to keep as much of the "updated" version from main as possible while making sure it didn't erase the changes I had made.

I had to change multiple files, but the one that gave me the most issues was the `WorldScene.unity` file. It was extremely difficult to figure out what changes to keep or discard in this file because the code was so foreign to me. It was a Unity file, so I had previously been interacting with this file through the Unity inspector and changing things through that visual interface. However, seeing all the information laid out in plain text was very interesting, but it was also very difficult to debug and figure out what to keep since that visual element was missing. I even had to restart once and undo the merge changes I made for the file because I ended up duplicating some elements which was causing compile issues.

However, despite my struggle, I was ultimately able to create a successful merge request that resolved all of the conflicts and still preserved the changes from the most up to date main and my own branch.

<img src="{{ 'assets/hw3/pr-trying.png' | relative_url }}">
*The finished merge request.*

<video width="640" height="360" controls>
  <source src="{{ 'assets/hw3/finish-merge.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>
*The merged UI/UX.*

## Learned More Git
In my experience creating this merge request, I realized that I did not know much git at all. I took this as an opportunity to look more into how git works, especially because I realized this would be an incredibly important skill for not just WolverineSoft Studio, but for any future job that involves software development.

I found a website that had extremely useful (and fun!) git lessons. I solved most of the puzzles/lessons that they had, and I learned a lot about git commands that I hadn't seen before (such as cherry-picking, rebasing, etc.).

Below is a screenshot of what the levels selection looks like with some of the lessons that I completed.

<img src="{{ 'assets/hw3/learn-git.png' | relative_url }}">
*A website I used to learn some git commands ([Learn Git Branching](https://learngitbranching.js.org/)).*

## Conclusions
I think that I was able to very effectively use my time during development, but I definitely struggled when I was creating the merge request. It was extremely difficult for me to figure out what I was supposed to keep versus discard, and I think this is related to the fact that this is my first time adding to such a large code base that so many people have worked on versus just working off something that I created on my own.

Learning about git definitely allowed me to utilize my time better because unfortunately, a lot of time was wasted searching online what I was supposed to do in order to reverse a commit, pull from a branch, etc. which I could have been using to analyze the code and figure out how to best resolve merge conflicts. Fortunately, I know next time how to use git commands effectively and efficiently, so I will save time in this aspect.

## Hours Breakdown
- Meeting: 2 hours
- Fix smithy implementation: 2 hours
- Create merge request: 5 hours
- Research git/merge requests: 3 hours

Total: 12 hours