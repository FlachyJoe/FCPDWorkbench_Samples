# FCPDWorkbench Samples

You can find here some demo to start with FCPDWorkbench. Directories store related Pure-Data and FreeCAD objects.

Below is the list of sample with the used objects.

## 3d keyboard:
Select the key in FreeCAD and ear sound from Pure-Data

  * [fc_selObserver] 
  * [fc_getObjectProperty]

## animator:
A keyframe-based animation recorder and player. See README in the directory.

  * [fc_getObjectProperty]
  * [fc_setObjectProperty]
  * [fc_placement]
  * Pure-Data dynamic patching

## clone:
Use the [clone] object to parallelize 3d object creation.

  * [fc_list]
  * [fc_object]
  * [fc_vector]
  * [fc_rotation]
  * [fc_placement]
  * [draft/make_bspline]

## random-tiles
Another [clone] demo which show how to send data to instances.

  * [fc_byLabel]
  * [fc_copy]
  * [fc_translate]
  * [fc_getObjectProperty]
  * [fc_setSketchConstraint]

## animate.pd
Select a FreeCAD object and see an animate move.

  * [fc_process]
  * [fc_getObjectProperty]
  * [fc_setObjectProperty]
  * [fc_PlacementPosRot]
  * [fc_vectorXYZ]
  * [fc_vector]
  * [fc_setPlacementPos]

## parametric_object_demo.pd
Create a box and lets you use sliders to move it.

  * [fc_object]
  * [fc_vector]
  * [fc_rotation]
  * [fc_placement]
  * [fc_setObjectProperty]

## simple_draft_demo.pd
Create a circle.

  * [fc_vector]
  * [fc_rotation]
  * [fc_placement]
  * [draft/make_circle]

## simple_part_demo.pd
Create a box.

  * [fc_vector]
  * [part/makeBox]
  * [part/show]

## simple_ref_demo.pd
Move a Body object in a Part.

  * [fc_process] with specific messages

## simple_shape_demo.pd
Fuse 3 boxes to create a U shape.

  * [fc_vector]
  * [part/makeBox]
  * [shape/fuse]
  * [shape/removeSplitter]
  * [part/show]