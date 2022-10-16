---
layout: post
title:  "Mirama Dev Blog #1 (October 2022)"
date:   2022-10-16 12:34:02 -0400
categories: mirama project devblog
excerpt_separator: <!--more-->
---

Welcome to a very special edition of the *Mirama* Dev Blogs! Yes, a special one indeed, as it's the very first! I don't know if it's better to wish for a long-lasting series or not, considering it would conclude with the game's release... In any case, we better make a good first impression!<br>
<br>
Ahem...<br>
<br>
These are going to be fairly informal affairs. I'm aiming for a new blog every two-to-three months. That should be a good way to follow the game's progress, frequent enough that it won't turn into a wall of text, but with enough time to have something fun to talk about every time! That's the hope, at least.
<!--more-->
<br>
Here's the Agenda for today!<br>

* What is *Mirama*?<br>
* What's been done in the past two months?<br>
* Story Mode and Classic Mode, two ways to play!<br>
<hr>
<br>

# What's Mirama?

Let's start with the elevator pitch. *Mirama* is a bullet-dodging adventure game, inspired by games like *Touhou*, *The Binding of Isaac*, and *NieR*.

A bit of backstory before I get into the nitty-gritty. *Mirama*'s story begins in the summer of 2020, the first year of the pandemic. I organized a game jam with friends to find something worthwhile to do with them during that lockdown-heavy period. The theme we ended up going with was "loss".

As I was brainstorming ideas, a concept locked into place for me.

Thematically, I’d make a game about the end of magic in a fantasy world, centuries before it evolves into a technologically-driven world like ours. After all, games like Final Fantasy VI were able to make captivating stories taking place in a world that tried to move past sorcery. Why wouldn’t a story about a pre...post...magic world be just as interesting?

![Gameplay of the original Miracles and Magic](/images/mirama/202210/theog.gif)

That's the original [*Miracles and Magic*](https://www.lexaloffle.com/bbs/?tid=39296)! But a proper development cycle will allow *Mirama* to go way beyond what the original game was able to deliver. We're talking:

* 5 dungeons to explore, instead of 3!
* NPCs to chat with, instead of just reading signs
* Longer stages, longer boss fights, more bullet pattern variety, more gameplay variety
* EVEN MORE SIGNS TO READ?? What were they thinking????
* Actual music!
* Save files, difficulty settings, collectibles, and much more!

![Old Mirama Trailer Gif](/images/mirama/202210/trailer3.gif)

(To avoid spoiling the next section, all the footage you're seeing is from two months ago)

You might notice that *Mirama*, visually, is already leagues above what I was able to accomplish with *Miracles and Magic*. These wonderful people are to thank for that!<br>
* [Lunate](https://twitter.com/lunoito) and [DAKU](https://twitter.com/fiopico) for their work on the in-game pixel art.
* [Shoorin](https://twitter.com/shoorinou) for their work on the character portraits.

# Recent progress on the project

Momentum has been good since last August! No change here is revolutionary by itself, but it adds up to something that feels substantially less of a proof of concept than two months ago.

1: The layout of the Hub world’s starting area really took shape. It used to be a single big room with the chapter select books, but take a look at it now:

![Mélodie sleeping in the Storyteller's House](/images/mirama/202210/house.gif)

A lot of different intractable objects were added as well, giving some flavor to the world. I was aiming for a messy look, something that feels... like the lair of a struggling has-been. Hopefully, that conveys well!

2: Screen shaking and death animations were added

![Béatrice's death animation, after being hit by a bullet](/images/mirama/202210/shaky3.gif)

3: Survival Rooms have been added as well! They have a trigger when started (like locking you in), and another trigger if you survive until time runs out.

![Alexis clears a survival room and gets rewarded with a key](/images/mirama/202210/survival.gif)

4: The game now features working checkpoints! They do what you’d expect, letting you reappear at the location of the last one you touched, in the state you were in when you last touched it.

![Alexis perishes at the end of a turret's bullet, then respawns at a checkpoint](/images/mirama/202210/checkpoint.gif)

5: The Costagonian boss, the Effigy of the Precursor, has new sprites, new attack names, and new bullet patterns

![The Effigy of Anna unleashes an attack called "In Her Name, Even This..." upon Béatrice](/images/mirama/202210/effigybullets.gif)

6: I rounded the corners of the main characters’ collision box so that running into a wall like an idiot happens less often!

![Mélodie swiftly dodges objects in the Hub while I just hold the right arrow key](/images/mirama/202210/ROUNDS.gif)

Plus a lot more little things that really aren’t worth mentioning here, but are necessary for progress!

The level design of Costagona isn’t doing it for me yet, so I was thinking that my next objective should be to find some good learning resources for that. Hopefully, I’ll be able to show you more from that chapter soon!

# Story Mode vs Classic Mode

So what's this about two different game modes? Am I already getting into scope creep territory?

Fear not! These two should provide some nice customization for players while being very simple to implement.

In Classic Mode, you will go straight from one chapter of Alexis and Beatrice’s story to the next, with no interruption and no ability to replay previous chapters. It’s like a run of the original *Miracles and Magic*, or of games like Touhou or Super Mario Bros. 5 chapters, each culminating in a boss. When it’s all done, you get a report of your final time and death count. That’s it. Perfect for speedrunners, or people looking for an old-school experience. This will probably end up being a replayable 2-3 hours experience.

Story Mode is meant to be a longer experience, bound to a save file. From a Hub based on the real world, you’ll be able to return to chapters you’ve already played, as well as do some tasks to unlock the next chapter. Every bit of content from Classic Mode will be playable, but the pacing will be slower with the new storyline the Hub comes with. This mode will also reward exploration, inside and outside of the storybook chapters, by unlocking content that would not be available in Classic. The playtime will depend on how hard you’ll try to perfect each stage, but I expect 5+ hours.

I expect both to bring something worthwhile to the table while giving me barely any additional work to do. Story Mode is the game I would have otherwise made, after all. The way I see it, games built like Classic Mode are more fun to run from start to finish. Games built like Story Mode, on the other hand, tend to make you more attached to your playthrough.<br>

Why not just give players the option?<br>
<hr>
<br>

Okay, that's all the time I've got! I've got to get back to playing Animal Crossing New Leaf, on my Nintendo 3DS.