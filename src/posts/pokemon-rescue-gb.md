---
title: Pokemon Rescue GameBoy Version
description: Moving from GDevelop to GBStudio to build a video game for my daughter
permalink: posts/{{ title | slug }}/index.html
date: '2021-12-26'
tags: [video-game, code, unfinished-project]
---

Moving from [GDevelop](https://gdevelop-app.com/) to [GB Studio](https://www.gbstudio.dev/) to and really gaining traction on the game development.

## Moving to GBStudio

In my previous post about the game development of [Pokemon Rescue](/posts/pokemon-rescue/) I explained how I decided on using GDevelop to quickly create a game for my daughter.  The idea was to keep it simple and force myself into a limited environment.

In today's realm of web and mobile technology, there's really no limit to what you can do. That can be entirely overwhelming for anyone learning something new, I've tried several times to build a video game using things like [PhaserJS](https://phaserjs.com/). However whenever I start a project like this I always get hung up for hours on the development environment, graphics and "what limits should I put on myself".

[GDevelop](https://gdevelop-app.com/) opened my eyes to the "drag and drop IDEs" that have been built to create games. And my experience in GDevelop has been amazing. I was able to quickly create a small video game and focus on the fun stuff instead of useless little details that make me twitch like code formatting.

Then I discovered [GBStudio](https://www.gbstudio.dev/) that was geared for building games for GameBoy. This satisfied nearly the exact requirements I set for myself: simple, limited and playable on dedicated hardware. With that I decided to give GBStudio a real chance.

![Visual IDE with drag and drop coding logic](../../images/pokemon-rescue-gb-drag-drop.webp)

## Some Clear Progress

Within a few days (these are parent/adult days, where I only get to spare a few hours) I was able to get a game built out that mirrored the same functionality that I had in GDevelop!

As I was building and adapting the game, I had to take into account a few more limitations that I think actually improved the game. This reminds me of the other things I'm studying around web accessibility: making a website accessible tends to make the site even better than you first imagined.

I started by making sure I could do the more difficult requirement: "carry a creature from one space to another". Unlike what I built in GDevelop, I wasn't able to simply take a sprite and move it with the character. I had to create a "carrying" sprite for the player and show/hide the creature being carried. This actually turned out quite well and is exciting to see how it works.

With this new "carrying" technique figured out I changed my initial plan to be more of a "pick up and carry" game vs a menu-driven game for each creature. This type of "just carry creatures around" aspect the game actually became much more fun. I'm still working out all the details but here are a few initial screens:

![A video game character picking up a duck then dropping it inside a fenced area](../../images/pokemon-rescue-gb-pickup.gif)

## Development Experience in GBStudio

GBStudio a bit more buggy than GDevelop as there are several times when I attempt to use one of their more advanced features and it doesn't work as expected. There's not much feedback for the developer either as I've not yet found a "run in debug mode" type of thing. I've actually had to use in-game dialogs to debug what variables are set to.

![A really crazy nest of if checks within the drag and drop IDE](../../images/pokemon-rescue-gb-crazy-nest.webp)

The drag and drop nature of the IDE can feel a bit cumbersome at times as well especially when you are already a developer. A bug I've filed recently really makes my head hurt because of my ingrained knowledge of if checks.

![A screenshot of the GBStudio with an if check clearly failing to evaluate properly](../../images/pokemon-rescue-gb-dialog-bug.webp)

## Work Progresses

I'll be updating this post as the game gets closer and closer to what I think is completion. I'm hoping to have it done by the new year and open up the "how do I get this on a physical GameBoy" realm.
