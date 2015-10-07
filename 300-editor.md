---
layout: page
title: Modeller
permalink: /modeller/
---

Taking advantage of the embedded *Destructive* 3D Editor tool, users can choose between quickly modify an existing 
model or create a new one from scratch.
The *Destructive* Editor provides a simplistic interface with clearly distinct functionalities for both model and view 
manipulation, and also for model creation and transformation.

![][editor-overview]

Powered by a non-intrusive suggestion engine, the *Destructive* Editor estimates possible future states based on the
current modelling progress, providing a list of contextualized suggestions for the next step.
The operations suggested include finishing 2D strokes, transformation of 2D strokes into 3D models, boolean operations 
between solids, confirmation of the delete gesture, and replacement with an existing model (primitive or from the 
collection).

![][editor-suggestions]

In touch-enabled devices, the standard single point interaction is replaced by a set of multi-touch gestures, allowing 
a higher degree of control for manipulation and transformation operations.
Using multi-touch interaction allows a literal hands-on approach, enabling a more natural way to create and express 
ideas.

![][editor-multitouch]

*Destructive* 3D Editor feature list:

- Suggestion engine;
- Tools:
   - 2D Sketching tool;
   - Camera and Model manipulation tool;
   - Smart-positioning tool;
   - Free-form tool;
   - Extrusion tool;
   - Cloning tool;
- Primitive set of shapes;
- Model creation from Variational Implicit Surfaces (VIS);
- Delete gesture;
- Model Subtraction, Union and Intersection (Boolean operations);
- Multi-touch support;
- Real-time collaboration.

[editor-overview]: {{site.baseurl}}/images/editor/editor-overview.png "Diorama Editor overview"
[editor-suggestions]: {{site.baseurl}}/images/editor/editor-suggestions.png "Suggestion list"
[editor-multitouch]: {{site.baseurl}}/images/editor/editor-multitouch.png "Multi-touch gestures" 