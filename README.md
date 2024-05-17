# Spine-Simulation

# Goal - Help surgeons locate pain source
•	Create a patient-specific graphical model of lumbar spine.
•	Simulate bending and twisting of the spine to look for the places where nerves could be pinched.

# Requirements
•	3D Slicer 
•	Blender
•	Unreal Engine

# Steps
•	Installed 3D Slicer software.
•	Imported raw data into 3D Slicer and created a spine model.
•	Exported the obj files in a new folder.
•	Installed Blender software.
•	Stacked the obj files together in blender.
•	Now, got a spine model with single obj file.
•	Imported the model in blender.
•	Removed the extra vertebrae’s and created a disk in between the vertebrae’s and Created a armature(cone like structure) so the vertebrae’s can act as rig.
•	Changed the material of vertebrae’s.
•	Created animations of bending and twisting by adding keyframes on multiple intervals.
•	Exported the model in the .fbx format so that we can import in unreal engine.
•	Installed Unreal Engine.
•	Created a new project and imported the .fbx file in unreal engine.
•	In the blueprint of the Bone, we created the EventGraph and triggered the animation on some inputs.
•	We set the bending and twisting angle, and when the bone exceeds that angle we can see the pinching.

 

 



