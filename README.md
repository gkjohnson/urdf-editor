# urdf-editor
Text editor for viewing and modifying URDF models.

## Ideas
- Web-based editor
  - Drag and drop mechanism for adding URDF files, models.
  - Re-instantiate URDF model on change of the text editor.
  - Provide tree view for editing joint, link, and geometry positions.
- Electron editor
  - Allow for editing xacro files if ros is on the system path to generate the urdf file while editing.
  - Edit multiple xacro files at once.
  - Use ros to find meshes and get package directories 
