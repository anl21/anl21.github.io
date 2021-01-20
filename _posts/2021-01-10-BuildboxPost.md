---
layout: post
title:  "Buildbox Simple Platform Game Display "
date:   2020-10-03
excerpt: "I made a simple hyper-casual platform game using Buildbox GameMaker engine"
tag:
- post
- video
- pictures
- level design
- Buildbox
#comments: true
---

# Mind Map

* Mind map contains the nodes <!-- blueprints  --> that we can use to control the game's 3D world, UI, startup screen and new scenes.

<img src="\assets\img\BuildboxPost\mindmap.png"/>

# Menu UI

* We can create opening & fading animations with the UI menu editor. 

<img src="\assets\img\BuildboxPost\Levelselection.png"/>

# 3D world 

* On 3D world editing screen we can find smart assets like coin that we can integrate with our game very simply.

<img src="\assets\img\BuildboxPost\gameedit.png"/>

# Brainboxes 

* Brainboxes are very useful to make a hyper-casual game with simple moves. We can just add it to the meshes that we want and tey will move & jump with the values that we've assigned. I used it on <I> Main Character </I> to jump and the <I> Backgrond </I> to follow the character at the same exact speed. 

<img src="\assets\img\BuildboxPost\brainbox.png"/>

# Character Nodes

* We're using nodes to determine character's movement and it's states.
* As an example for the sates, <b>if collide</b><br/> state is used for the collision with the enemy and the nodes connected to the <I> GameOver screen </I>. Before GameOver screen we can add a delay for the death animation, which is getting apart into pieces in our game. 

<img src="\assets\img\BuildboxPost\maincharacternodes.png"/>

# GameOver UI

* We can either add pictures or buttons to our gameover screen and link the buttons (restart, mainmenu) from our <I> Mind map</I>.

<img src="\assets\img\BuildboxPost\gameOverscreen.png"/>


# Gameplay

<video width="320" height="240" controls>
  <source src="\assets\img\BuildboxPost\video.mp4" type="video/mp4">
  <source src="\assets\img\BuildboxPost\video.ogg" type="video/ogg">
</video
