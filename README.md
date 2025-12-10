# CSC413-assignment
The Setup
A-Frame: The file starts by loading the A-Frame library, which allows us to create 3D scenes using simple HTML tags.

Materials (Mixins): It defines basic styles for things like wood (brown, rough) and metal (gray, shiny) so these styles can be reused easily throughout the scene.

The Environment
Sky and Ground: A plain color is set for the sky, and a large green circle is used for the grass/ground.

Walls: Curved sections that look like partial walls are used to create a simple, enclosed backdrop behind the main objects.

Lighting: The scene has a few lights: a strong directional light to cast shadows (making the objects look grounded) and soft ambient lights to ensure everything is visible.

Camera: The camera is set up so you can look around and use the WASD keys to move through the scene.

The Objects (The Table Cluster)
All the main objects are grouped together in one entity called #tableCluster to keep them organized:

The Table: A thin cylinder is the white tabletop, and four small cones act as the legs underneath it.

The Milo Tin: This is a green cylinder with the text "MILO" written on it and a silver top piece.

The Milk Tin: This is a lighter-colored cylinder labeled "MILK".

The Cups: There are two cups, each made from a cylinder for the body and a curved shape (half-torus) for the handle. They are filled with a dark liquid.

Decoration: A small decorative object, like a tiny plant or ornament, is placed in the center of the table.

Surrounding Items
Chairs: Two simple chairs, built from boxes (for the seat and back) and cylinders (for the legs), are placed facing the table.

Other Plants/Mats: There is a separate small plant in a box pot nearby, and a flat plane is used like a rug or mat under the table area.
