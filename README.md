# FreeCAD

- Toggle visibility: <Space>
  - grey elements are hidden
- Selection of lines and faces
- CAD style navigation
- View manipulation buttons
- Navigation cube to access different angles
- Combo-view:
  - Model
    - Shows the _model tree_: structure and composition of the 3d model
    - properties are shown when an item in the tree is selected
  - Task
    - various available operations are listed there (depending what you have selected)
  - If you closed it, retrieve it with: view > panels > combo view
- _Feature Editing Methodology_
  - start with one base feature and apply various features or operations on it,
    in order to create the desired 3d geometry

## First model

- File > New
  - this will create a new _document_
- Save
- Create Body
  - either by clicking on the button or going to the tasks tab
  - body is a container that contains all of the 2d and 3d geometry
- You can __close__ a document by right clicking on the document and click on 'close document'
- Create a basic shape: button(create an additive primitive) > additive cylinder
  - recommendation: attach your new objects (primitives or sketches) on one of the standard planes

## Construction mode

Two modes of sketching:
- staggered mode: all the drawing will be visible in the 3d view (outside the sketch) and can be used for 3d operations like pad etc.
- construction mode: where you have some kind of "help" geometry that will not be used in the 3d view.

There's a button that toggles the mode. The objects of different modes have different colours. Also, you can toggle the mode of an object by selecting the object first and pressing the toggle mode button.

Note also that if you select multiple objects, this button toggles all of them.

## Fillet

Add a curve in the intersection of two straight lines.

## link to external geometry

with this one can have references to other sketches in the current sketch. meaning, for example, you can make lines parallel to another line in other sketches and so on.

## Random tips

- when the lines are tangent, for chamfer you only need to choose one line

