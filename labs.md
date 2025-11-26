# Experimental Features

At the very bottom of your Blocks menu you'll now see a beaker icon which lets you access prototype versions of your most-asked-for features. Here’s a breakdown:

### **Non-coplanar face mode**

Many of you have noticed that Blocks will create coplanar faces when reshaping meshes. This is helpful in many cases, but in others it creates extraneous triangles that make further operations like perfect subdivision difficult. Now you can enable non-coplanar faces to avoid creation of extra triangles.

![](.gitbook/assets/noncoplanar.gif)

### **Loop subdivide**

&#x20;Subdivision can be a really powerful tool. It’s even more powerful if you can cut a loop around an entire mesh. With loop subdivide enabled, simply long press on the trigger while subdividing to see a perfect subdivision loop form around your object.

![](.gitbook/assets/Models_LoopCut.gif)

### **Edge, Face and Vertex Deletion**

Many have asked for the ability to delete a single edge, face or vertex. With this feature enabled, use the eraser tool to do just that. We'll “collapse” the mesh based on the edge, face or vertex you delete.

![](.gitbook/assets/erase-an-edge.gif)

### **Worldspace grids**

Another option that helps with precision is enabling worldspace grids. This feature will show grids along every side of your worldspace. The grid units are equivalent to the actual worldspace grid units, so you can precisely measure and place objects along the grids.

![](.gitbook/assets/Models_Worldspace.gif)

### **Volume insertion ruler**

Modeling very precisely in Blocks can be difficult without a sense of relative scale. This experimental feature allows you to enable a ruler when you are inserting a mesh. As you insert the object, you'll see relative measurements in meters appear on each axis so you can precisely and accurately measure every object relative to the others.

![](.gitbook/assets/Models_Ruler.gif)

### **Expanded mesh wireframe**

&#x20;When reshaping a mesh you see a helpful wireframe around the section of the mesh you are reshaping. Many have asked for the ability to turn that wireframe on for the entire mesh, and this feature does exactly that.

![](.gitbook/assets/ReshapeWF.gif)

### **Stepwise selection undo**

Multi-selecting a lot of objects can be frustrating if you select the wrong object in the middle of your selection process. We wanted to make this easier, so we’ve experimented with allowing you to undo and redo steps in your multi-selection. You can use the undo and redo buttons on your non-dominant controller to undo or redo the selection of objects in order. Make sure to keep your trigger held down while undoing or redoing to ensure you can keep multi-selecting after correcting your mistake!

![](.gitbook/assets/stepwise5.gif)

It’s important to note that since these features are experimental, there may be minor bugs or issues when using them.
