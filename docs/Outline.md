1. Collect IRL Data  (written on the whiteboard)
	- Display 
		- measurements (X, Y, Height to base of screen -- all in cm)
		- resolution (we used Full HD, 1920x1080px)
	- Camera
		- film back measurements (we had a full-frame DSLR video camera)
		- lens length (45mm fixed lens in our case)
		- addn'l lens stats (f-stop, etc. - which we weren't going to be using in the demo)
		- position relative to display (we set out camera up 1 meter away from the screen, aligned to the bottom of the screen)
	- Computer
				- ip address (use `ipconfig` in a windows command prompt to find your current IP)
2. Create and save a default level (map) to work on and set it as the default (maps&modes) in project settings
3.  reconstruct our IRL display screen in unreal
	- create a plane actor, duplicate it's static mesh into your content folder - delete the actor
	- drag the new SM plane into your scene, rotate it, align it's uv's, *then* scale it
		- we created a quick test material to visualize our UVs here
4.  Add CineCamera Actor
	- set the lens length, filmback, disable focus so we're not dealing with DOF
5. Set up Livelink & the iPhone
	- open livelink window
	- open UnrealRemote2 on iPhone - set the IP address, connect.
	- find the iphone in LiveLink, create a preset, save the preset, set the preset as default in Project Settings
	- add a livelink transform component to your cinecam, and  
6.  Configure nDisplay
7. Launch listener
8.  Launch, Configure, and Connect Switchboard
9. From Switchboard, run your Unreal project in nDisplay mode.
10. Make your movie and get famous.
- Then, on to the Unreal portion of the demo: