![](https://raw.githubusercontent.com/janstieler/Three-JS-Snippets/master/img/logo.png)

# THREE JS Snippets for Visual Studio Code

This extension adds Three JS Code Snippets into Visual Studio Code.

This is a VSCode Server extension that provides Three.JS snippets to speed up your Three.js development. Snippets exist for the popular framework React Three Fiber (R3F) and Three.js on its own, for Typescript and Javascript.

Specifically, it is the only extension on the marketplace that provides general functions for Three.JS, both for R3F as well as for the core library. The snippets contain intial starter functions as well as general constructors/objects.

Each snippet starts with the letter t, followed by the name of the shortcut, in order to avoid conflicts with other snippets (I.E instead of using 'ren' to create a WEBGLrenderer, you use 'tren' to create a WEBGLrenderer to avoid a conflict with a very common React.JS snippet). See below for a list of all the snippets.

PS: Typscript is supported but many snippets may not work. For example, OrbitControls will break if you use typescript.


### It looks like:
 - Empty


## List of Snippets

### Shared  R3F and Three.js Snippets
|trigger|contents|
|:--:|:--:|
|tgui|Creates a Leva GUI for R3F or a DAT Gui for Three.js|
|tcam|Creates and chooses a specific Camera constructor|
|tgeo|Creates and chooses a specific Geometry constructor|
|thlp|Creates and chooses a specific helper constructor|
|tmat|Creates and chooses a specific material constructor|
|tlig|Creates and chooses a specific light constructor|
|tls|Creates and chooses a specific lights/shadows constructor|
|ttext|Loads and creates a 3D text object|
|ttexture|Creates and chooses a specific texture constructor|
|tmesh|Creates and chooses a specific object constructor|
|tresize|Automatically resize the canvas to the size of the window|
|tbufmesh|Creates and chooses a specific buffer object constructor|
|tfog|Creates and chooses a specific fog construtor| 

### Three.js Snippets
|trigger|contents|
|:--:|:--:|
|tinit|Creates a entire Three.JS scene with a camera, a light, a renderer, a render function for animation, and optional settings|
|tinitgui|Same as `tinit`, but with a DAT GUI template|
|tbi|Basic Init function (camera, scene, renderer)|
|tloader|Creates and chooses a specific loader constructor|
|tload|Loads a specific resource and creates a template function to modify/use the resource in a scene|
|tren|Creates and chooses a specific renderer constructor|
|tloadfunc|Combines`tload` and `tloadfunc` all at once|
|ttexture|Creates and chooses a specific texture constructor|

### R3F Snippets
|trigger|contents|
|:--:|:--:|
|tinit|Creates a R3F scene with a basic Canvas|
|tinitd|Same as `tinit`, but with an extra import of DREI and its hooks|
|tut|Creates a R3F useThree hook|
|tuf| Creates a R3F useFrame hook|
|tul|Creates a R3F useLoader hook|
|tut|Creates a R3F useGraph hook|
|tmeshd|Same as`tmesh`, but uses the DREI shape components|

## Known Issues

This is a new extension so please let me know if you run into any issues by filing an issue on Github. 

### Base on
[acrose99 ??? Three-JS-Snippets](https://github.com/acrose99/Three-JS-Snippets)

## Release Notes

See the [CHANGELOG.md](CHANGELOG.md) for a list of changes for each version.
