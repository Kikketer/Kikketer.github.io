---
title: Pokemon Rescue Makecode Version
description: Moving from GDevelop and GBStudio versions of Pokemon Rescue to now trying Makecode Arcade
permalink: posts/{{ title | slug }}/index.html
date: '2022-01-17'
tags: [video-game, code, unfinished-project]
---

After trying out [GDevelop](https://gdevelop-app.com/) and [GB Studio](https://www.gbstudio.dev/) I decided to see what differences the [Makecode Arcade](https://arcade.makecode.com/) has to offer.

## Moving to Makecode Arcade

This is my third installment of the Pokemon Rescue saga. I didn't plan on any of this but that's the nature of how technology moves and how quickly you need to adapt.

I decided to drop the [GDevelop version](/posts/pokemon-rescue/) and the [GameBoy version](/posts/pokemon-rescue-gb/) of my game "Pokemon Rescue" because they didn't satisfy the bare minimum I was looking for.

- Easy to develop (Both satisfied)
- Dedicated hardware (Only GBStudio)
- Build the game I wanted (Only GDevelop)

I say "Build the game I wanted" because as I was able to get really far and made some seriously awesome design changes due to the limitations GBStudio put on me, it was too limiting. The performance was very low for some simple things such as moving more than one sprite on the screen at a time.

GDevelop was great but it didn't have dedicated hardware like I wanted. I was actually thinking I could wrap up the web game and put it on an emulator handheld but that was just too much work (which "Easy to develop" also means "Easy to deploy").

That brings me to Makecode Arcade! I knew about this platform since the beginning but never gave it a solid look because I thought its entire intention was to teach programming. "How far could I get with block coding" I thought. Well come to find out it's an incredibly powerful platform and it has dedicated hardware to boot!

![Visual IDE with drag and drop blocks to write code](../../images/pokemon-rescue-MK-blocks.webp)


## Incredible Progress

Development in Makecode Arcade is incredibly fast. I went from using the blocks to understand just what was available to diving into the full Javascript angle. Now I already know how to write Javascript (been doing it for 14+ years) so that may be the reason this felt so much easier to develop for.

I've also been able to do what I want, as the power of the hardware device [Meowbit](https://meowbit.kittenbot.cc/) has just enough power to handle the logic I want all the while being small and simple.

One of the major takeaways I have from writing the code here is that I've almost starting like Typescript! I've always despised Typescript and how it can really get in the way sometimes (try figuring out a type from a library, etc etc) but it really helped out in their editor. Although every time I'm writing vanilla javascript it's within a solid IDE like [WebStorm](https://www.jetbrains.com/webstorm/) whiich is able to provide typeahead logic and guesses even with standard JS.

In just a few days I was able to get a solid foundation of the game running. Of course I had a solid idea of where things should go and how it should work based on all the builds that I've done in the previous platforms. So it was just a matter of writing the Javascript version of that design. I'm truely excited to see where this game will go!

<video controls title="Framerate drops" aria-label="A video game character picking up a dog and carrying it around a farm">
  <source src="/images/pokemon-rescue-mk-playing.webm">
  Sorry your browser doesn't support this video
</video>

## Powerful Development Environment

The Makecode Arcade site/IDE is actually quite powerful and helpful. If you switch over to the Javascript view you can see the file tree and even connect to Github!

I've been able to push my code to Github and using branches worked with my son for him to create the sprite assets while I throw the code. It's actually a really fun and collaborative experience that rivals even some of the best IDEs out there.

![A file list on the left and git controlls on the right, allowing users to commit and create branches](../../images/pokemon-rescue-mk-github.webp)

## Updates to Come

Like many of my other posts, I'll keep updating this one as I move forward. Right now I'm just focusing on getting this thing written and playable on the Meowbit hardware.
