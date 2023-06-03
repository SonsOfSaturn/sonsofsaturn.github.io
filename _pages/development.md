---
layout: single
title: "Development"
permalink: /development/
header:
  overlay_color: "#000"
  overlay_filter: "0.25"
  overlay_image: /assets/images/development.png
excerpt: "Or: how this game came to be."
author:
  name             : "Charles"
  avatar           : "/assets/images/selfie_cropped.png"
  bio              : "I caved to my intrusive thoughts and made a video game."
  location         : "Northeast U.S."
  links:
    - label: "Email"
      icon: "fas fa-fw fa-envelope-square"
      url: "mailto:sonsofsaturngame@email.com"
    - label: "Instagram"
      icon: "fab fa-fw fa-instagram"
      url: "https://instagram.com/interstitial_explorer"
author_profile: true
date: 2023-06-01T03:19:20+00:00
---

Development on Sons of Saturn started in early 2022.  For years I have a strong interest in exploring and photographing abandoned locations, and I wanted to build an old school adventure game that captured the aura and atmosphere of these spaces.  So, I quit my engineering job and got to work sketching out the rough framework for what would become Sons of Saturn.

The first step was choosing a game engine.  I ended up choosing Godot, both for its elegant design and for its permissive licensing.  The entire game - the dialogue system, the navigational mechanics, the minimap, and everything else - was built from the groundup in Godot, with very little reliance on third-party frameworks or plugins.

<figure>
	<a href="https://sonsofsaturngame.com/assets/images/godot.png"><img src="https://sonsofsaturngame.com/assets/images/godot.png"></a>
	<figcaption>Sons of Saturn was built using the Godot game engine.</figcaption>
</figure>

Next I needed to decide what to focus on, design wise.  I knew I wanted to make something with a strong emphasis on atmosphere and narrative, a la *Night in the Woods* or *Disco Elysium*.  Structurally, a first person point and click style game seemed best suited, given the nature of my photo assets.  When it came time to deciding how this would actually play out, I adopted the *Team Ico* "subtractive design" approach.  I wanted a point and click game with a world you could engage in, but any superfluous mechanics were to be cut - anything unnecessary distracts the player and breaks the immersion.  That said, I had to be careful not to polish it down to nothing, as narratives require engagement for the player to be invested.  Ultimately, I found that the game worked best if structured like a classic point and click game, but with the more esoteric trappings of the genre largely stripped out.  The player is still required to manipulate parts of their environment, talk to people, and make decisions - but the player should be spared the experience of dragging every item in their inventory against every pixel they see.

<figure>
	<a href="https://sonsofsaturngame.com/assets/images/sub-design.jpeg"><img src="https://sonsofsaturngame.com/assets/images/sub-design.jpeg"></a>
	<figcaption>Subtract away everything unnecessary - but nothing more.</figcaption>
</figure>

Next, I needed to make my exploring images work for this format.  Simply using the images, unmodified, was an option - an option employed by a lot of campy 90's games.  However, I found that the images had more power if made abstract.  The Photoshop Cutout filter seemed particularly well suited to produce images that were abstract, but retained the high-fidelity crispness and clarity of the originals.  Nearly every point of view image in the game currently is a lightly modified photograph that was run through the Cutout filter.

<figure>
    <a href="/assets/images/color-chairs-unfiltered.jpg"><img src="/assets/images/color-chairs-unfiltered.jpg"></a>
	<figcaption>Before cutout filter.</figcaption>
</figure>

<figure>
    <a href="/assets/images/GameStills/colorful_chair_hall.png"><img src="/assets/images/GameStills/colorful_chair_hall.png"></a>
	<figcaption>After cutout filter.</figcaption>
</figure>

With that breakthrough, most technical issues and key design decisions had been settled.  The task, then and now, was turning that framework into a fleshed out, polished product.

At the time of writing, development largely consists of writing revisions and photo editing, both of which are essential to bringing the world to life.  I am on track to have the full game complete by Summer 2024.