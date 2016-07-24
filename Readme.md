# narrative-map-system

**This is a work in progress.**

## Introduction

Game designers have long understood the power of game platforms to support story telling.  Numerous examples of technically stunning but nevertheless uncompelling games demonstrate that without artful story telling, the experience may not be enjoyable.  In contrast, masterful stories built with simplistic game engines are not inherently less enjoyable due to the simplicity of the platform.  Thus, it is usually the story that makes the experience.

Narrative Map System (NMS) is like a very simple game platform that was designed to function like a picture book for children.  A narrative map consists of multiple scenes that an avatar navigates, much like flipping through the pages of a book. Scenes may contain objects that support animation and limited interaction.  By walking their avatar from scene to scene, readers can wander and explore narrative worlds to discover story elements that build a coherent imagination space.

## What is the Narrative Map System?

NMS consists of building and viewing tools.  The viewing tool is an HTML5 application that is capable of "playing" NMS assets.  Building an NMS story is currently a "low-tech" operation:

- print the [templates](templates) and draw artwork directly upon them
- scan and post-process the artwork, saving all the images separately
- create a world configuration file that loads all of the artwork

The NMS world may then be tested using the viewer.

## How is a new story created?

Let's make a simple story about camping.

### Scenes

There will be two scenes in our story - a tent and a campfire - and we will be able to walk from the tent to the fire and vise versa.  Scenes are like map tiles that are placed next to one another.  For our camping story, we will have two scenes side-by-side and we will be able to walk back and forth between them.  A scene can also have a caption that helps the reader understand how the narrative is unfolding.

### Objects

There will also be two objects - the avatar and the campfire.  The campfire is an object because we wish to animate it, so instead of drawing a non-moving fire directly in the scene, we will make a dynamic fire object that visually changes over time.

### Avatar

The avatar is a special object, and there is only one avatar per story.  When reading a Narrative Map, the avatar is always in the center of the screen.  The avatar moves our view from scene to scene.  Avatars, like other objects, support animation.  However, in the case of avatars, the animation is always a depiction of "walking."

### Story Composition

The story is ready when the scenes have been stitched together, the avatar is placed on the scene, and the objects are imported.  There are a few more details that are described in the tutorial (forthcoming) but this is substantially "it."
