---
title: "Unbreathable"
description: "A random developer with a big dream."
hero:
  title: "Hi, I'm Unbreathable 👋"
  description: "I'm currently creating way too ambitious apps like Liphium and in my free time I also like to cook things sometimes. I mostly develop cross-platform apps using stuff like Flutter or the Web. Well one of those creations is what you see right now."
---

# The biggest project I've ever worked on

[Liphium](https://liphium.com) has been the most fun and the most pain I've felt in a project. Over the past 1.5 years it's been almost the only codebase I've touched. The only time I stopped working on it was during vacation. During which I would still think about it all the time. It's a creation I will probably never forget.

So for this main page, I thought I'll talk a little bit about my philosophy for making software by taking Liphium as an example and hopefully teaching you a thing or two along the way.

## Nailing the feel of the app

For me, the balance between UI (User Interface) and UX (User Experience) is one of the most important things. I love animations and would like to have them everywhere if I'm totally honest, but there just shouldn't be too many animations in an app to make it feel slow or annoying to use. But on the other hand, there also shouldn't be no animations at all that will make the app feel unprofessional and outdated. This is one of the most important things to me in an app. Can the creator add animations in most places without making them annoying or feel out of place?

When I create an app, I try to not make animations distracting or ruin the user experience. If I add an animation to something that should be immediately visible, I make sure that the animation is at least not longer than 500 milliseconds.

In Liphium for example, there was a sliding or scale animation every time a dialog opens or everytime you open a sliding window in the desktop app. At first, it was a really cool to have an animation for all dialogs. But then after some time, the animation felt annoying and unnecessary, even for me, someone who loves animations and adds them to literally everything. But over time I noticed that it was annoying me when I was trying to test basic functionality throughout the entire app. So why is the animation still there and why did I not just remove it in the first place?

Well, when a dialog pops up, I added a shake effect to it and randomized the direction from which it flys or scales in. Only slightly, but just enough to make it more interesting to the eye. This immediately made it feel much better and since then a lot of people have been telling me that they like the way the dialogs fly in and specifically mention it as a part of their opinion about my app. There are of course going to be people that dislike stuff like this, but so far, I've only heard positive things from my friends. Then again, 10 people aren't exactly everyone in the world and there are gonna be people complaining about it at some point.

Then again, this whole thing was just created out of my need for an animation when dialogs open, and in the end, I think I got quite the good result out of it.

## Creating the right features

When making software, people often immediately try to make a gigantic plan for what features they want to have in an app. And I'm certainly not the only one that did this wrong at some point. But I have a new perspective on all of this thanks to my work on Liphium for the last 1.5 years that I want to share.

For me, when I add new features to Liphium they have to now fill a certain purpose and solve a real problem my friends or me have. I feel like this should be obvious but it's often overlooked how hard it is to actually find out if people are gonna use something or not. So over the past few months, I've come up with a strategy to determine if a feature is useful or not. And the best thing is that you don't even need A/B testing or some other complicated method that needs to be implemented in your app first. At least not if you're just making something for a small group of people like I am.

When I have the idea for a new feature, without asking anyone, I implement a prototype **version 1** of the feature. Then, after that I give that feature out as a beta that I compiled myself and try to see if people like it or if people use it. If it's actually good and might be useful I build a **version 2** of the feature that is a lot more stable and usually takes me around 2-3 weeks to fully get working. That work than gets hidden behind an experimental toggle in the settings somewhere and I show people a popup to see if they want to enable it or not. When that is also successful, I go on to make a full implementation **version 3** with comments and everything so the code looks nice and maintainable. That's my 3 version principle and how I implement every feature in Liphium. At least most of the time. Which is a good transition to this next paragraph.

## Have fun dude, no-one cares

I've just told you how I create software and all the rules I try to follow. And "try" is a good choice of words here. At the end of the day, programming is a hobby for me and I do all of it, especially the work on Liphium, for fun. If you're in a similar situation or even at a company, you don't always have to follow the rules. It's good to have a rough idea of what you want to do, but before you end up hating programming forever or get burnout, just try to chill a bit. If you want to attempt something stupid, then do it, who cares?

It was important for me to leave this message at the end of this website because when making something the journey along the way is always the most important thing. No matter what you are creating, if you don't have fun while doing it, it won't be good. Heck, at least as of writing this the entire Liphium codebase doesn't include a single test. It's over 30.000 lines of code for both client and server. Why doesn't it? Because it wouldn't be fun adding tests. And if I don't want to add tests but still test the features and make sure everything is bug-free, there are other ways of doing that as well. Well for now at least.

While I still have a lot more stories to tell about this app, this is what the main page of my landing page looks like. While others have fancy animations mine is just a wall of text. I honestly just didn't want to do more than this for now, because otherwise it wouldn't have been fun making this. And that's what all of this is about anyway, right?
