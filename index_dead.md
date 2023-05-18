---
layout: default
---
# testing
## testing
### testing
here's *some* **more** _test_  `markdown`  [Outline](docs/Outline.md)


<div align="center">
<h1>In-Camera VFX for Indie filmmakers using Unreal Engine</h1>
<h3>Notes and resources from the 5/16/2023 Seattle Unreal Users Group meetup</h3>
</div> 

###  Scott's Workflow plugins (optional):
- [Scooter Utils](https://github.com/ScottKirvan/ScooterUtils) - Unreal plugin used to change editor font-size for readability and for quick restarts of the editor.
- [UE QuickLaunch](https://github.com/ScottKirvan/UE_QuickLaunch) - right-click context menu for launching unreal without the Epic Games Launcher.

### Required Equipment
- Computer: capable of running Unreal Engine.
- Camera: any camera that can record video will do.
- iPhone: used as a tracking source and attached to the camera.
- Network: you need the iPhone and the Computer connected to the same network so they can communicate.
- Display: This is the display/TV/monitor/projector/LED Wall/etc. that you will be projecting to and filming with your camera.  Your computer monitor will work for this and may be all you need to "tell your story" on film.  This setup will work with multiple Displays too.

### Required Unreal Project Plugins:
- Static Mesh Editor Modeling Mode (enabled by default in UE5+)
- nDisplay (enabling nDisplay automatically enables the LiveLink plugin too)
- Switchboard

### Outline
The basic outline of the demo went like this:
1. Collect IRL (In Real Life) Data  (written on the whiteboard).
3. Reconstruct our IRL display screen in Unreal.
4. Add CineCamera Actor and set it up to match your IRL camera.
5. Set up Livelink & connect the iPhone using Unreal Remote 2.
6. Configure nDisplay - add VP (Viewport) node, add static mesh screen, and add camera.
7. Launch listener.
8. Launch, Configure, and Connect Switchboard.
9. From Switchboard, run your Unreal project in nDisplay (node) mode.
10. Make your movie and get famous.


### Tutorials:
- YouTube - TBD
- text version will be here and on https://dev.epicgames.com/community/ - TBD


### Resources
- [Unreal Engine 4.27 In-Camera VFX Tutrials](https://www.youtube.com/playlist?list=PLZlv_N0_O1gaXvxPtn8_THYN_Awx-VYeu)
- [This info on GitHub](https://github.com/ScottKirvan/ICVFX)
- [www.ScottKirvan.com/ICVFX](https://www.scottkirvan.com/ICVFX)
- Contact me:  icvfx@skvfx.com