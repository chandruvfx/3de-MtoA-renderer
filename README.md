# 3de4-MtoA-renderer

## A  3dequalizer deadline render farm submitter

Below video demonstrates the workflow of the maya arnold deadline renderfarm submitter through 3de4(3dequalizer4).

## A tool snippet in the 3de4 end doing multiple tasks  


1. Converts the camera and geomentry mesh elements of scene file into alembic archives. and also converts the distortion nuke gizmo of the plate's
2. Creating the maya files by collectiing all the converted files using maya standalone. 
Creating and Assigning the arnold wireframe shaders for various render layers.
3. The tool submit multiple Deadline rener jobs. One maya job and two Nuke jobs. 
   Once the maya arnold renders successfully completed, A dependent secondnuke job started which collect all the rendered files 
   and generate a nuke script with the distorted plate.  A third nuke job renders the generated nuke script. 
    
```diff
- *Client Confidential Python repo is NOT INCLUDED ..*
```
## <ins> Tool in Action </ins> :point_down: [Youtube Link]

[![Video Demo](https://img.youtube.com/vi/diug0lMhQpE/0.jpg)](https://www.youtube.com/watch?v=diug0lMhQpE)
