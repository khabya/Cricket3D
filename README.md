# Cricket3D

Cricket 3D is a basic OpenGL renderer with cover of all core basics(Drawing, Shaders, Texture, Camera, Lights, etc). I started using Gtk+ widgets but I get weird issues and so I moved to the QT widgets. And I used the Assimp library for loading 3d models. I tried to abstract the gui and render engine from the start. And that helped me a lot when I switched from the Gtk+ to the QT widgets.

# Instructions

* App is very simple. 

* You can open 3d model on menu bar. 

* Model loading may take a time depending your model and your modeling skills (no offensive).

* Left Click and drag for rotate model horizontally.

* Middle Click and drag for rotate model vertically.

* Right Click and drag for move camera.

* Scroll Mouse Wheel for move camera forward and backward.

* Click window in menubar and click settings for opening settings panel. You can make light adjustments in here.

* App supports diffuse and specular maps. But textures must be in same folder as 3d model.

* Click edit and enable wireframe 

# Requirements
* QT5 for widgets and build system(qmake).
* GLM-0.9.5 for mathmatics.
* GLEW-2.0 for OpenGL functions.
* stb_image for image loading.
* Assimp-3.3.1 for 3d model loading.
