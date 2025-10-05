[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/d-DorLAf)
# minigame-1
## Devlog
A simple way of thinking about a Scene is to think of it like how a director might put together a scene in a movie. In real life, the scene needs a setting, props, actors, a camera, and so on. In Unity, the objects in the scene are called GameObjects, and they are (not always, but usually) the things that we see on screen while the game is playing.

Think about the objects I listed earlier (props, actors, camera). All of these things are *objects*, but they *behave differently*. For example, a person has a body and a brain that lets them move around, while a camera has a computer in it that does a bunch of calculations to record a video. Both are objects, but you would hardly call them similar because of their different attributes. In Unity, the attributes that define how objects are different, or more specifically how they behave, are called **components**.

Lets say we want to make our movie scene in Unity. The simplest scene might have a camera, one actor, and some props. The Scene needs a Camera, which is a GameObject with the Camera component, which tells it to act like a camera and record the scene. The Scene would also have some props, which would likely be GameObjects with MeshRenderer and MeshFilter components on them, which allow GameObjects to have a 3D model that can be seen by the camera. The Actor GameObject would likely have those same components (so that they can be seen!) as well as a component that tells them how to move around in the scene. Just like a scene in a movie, we can play the Scene when we're ready to see all of our GameObjects, with their unique behavior from their Components, in action.

In summary, a Scene consists of GameObjects, which have behavior implemented by Components.
## Open-Source Assets
- Starter first-person assets: https://assetstore.unity.com/packages/essentials/starter-assets-firstperson-updates-in-new-charactercontroller-pa-196525
- Low poly platformer kit: https://assetstore.unity.com/packages/3d/environments/lowpoly-platformer-kit-free-modular-stylized-blocks-319018 
