# urdf-editor
Text editor for viewing and modifying URDF models.

## Ideas
**Problems**
- Xacro does not simply map to a URDF file so it may be difficult to enable editing a Xacro file visually. It would all be editing the file then seeing results.
- If xacro data were mapped to the resulting joint configurations or generated parameters then at least you might be able to click on a joint and see what was used to generate the values associated with it and edit those causing ripple effects onto other models.

**Web-based editor**
- Drag and drop mechanism for adding URDF files, models.
- Re-instantiate URDF model on change of the text editor.
- Provide tree view for editing joint, link, and geometry positions.
- Begin with full model hierarchy and select which objects / frames should be joints.
- if just a position or numeric value changes then do a minimal change to the model instead of reparsing.
- allow custom sorting of joints and links in the xml doc.
- couple there links and associated joints in the displayed hierarchy.
- display joint limits on hover of a joint.
- display rotation axes on hover
- allow drag positioning of individual visual, link, or joint elements.
- toggle for displaying collision or visual elements
- display the workspace volume of a kinematic chain in 3d.
- node editor for editing individual attributes of a link / joint.
- allow joint manipulation / dragging to get a sense for movement possibilities.
- jump scroll to synchronize the hierarchy view and text view on click. And / or highlight the section on hover or focus.

**Electron editor**
- Allow for editing xacro files if ros is on the system path to generate the urdf file while editing.
- Edit multiple xacro files at once.
- Use ros to find meshes and get package directories
