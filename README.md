# Vanessa Chen Period 4
# Final Project

Implemented:

Existing commands:
- light
  - add a light to the symbol table
  - loop through all the lights when calculating diffuse and specular
- mesh
  - use an external .obj file for polygons
  - works with vertices and faces
- save_coord_system
  - saves a copy of the top of the stack to the symbol table

New primitive shapes:
- cone cx cy cz r h
  - creates a cone in which cx cy cz is the center of its base
- cylinder cx cy cz r h
  - creates a cone in which cx cy cz is the center of its top 
- pyramid x y z width height depth
  - creates a pyramid with a rectangular base in which x y z is the front left corner of its base

Proprosal:

Existing commands:
- light
- mesh
- shading
- save_coordinate_system

New primitive shapes:
- cone
- cylinder
- triangular prism
