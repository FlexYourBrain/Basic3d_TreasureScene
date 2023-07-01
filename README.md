# Treasure 3d scene

This project showcases some of defolds rendering features for a 3d scene.

["Play The Scene Demo"](https://flexyourbrain.itch.io/treasure-scene)

 
**Key Controls** :

- Left Mouse | open/close chest
- D or right arrow | turntable right
- A or left arrow | turntable left

**Features** :

- Particles in 3d space
- Sprite animation as decal in 3d space
- Animated glTF model
- Single atlas texture for all models in scene (2k resolution)
- Baked lighting in texture
- Alpha transparency used on 3d model
- Single blend pass for (models,sprites,particles etc.) transparency (see render script)


The project contains a bootstrap ["main.collection"](defold://open?path=/main/main.collection) that includes game objects, camera component and script that sets a background color, sets the camera to active slot in render script and takes input for mouse and keyboard to make the camera turntable and treasure chest open and close. 

<sub>Tip: when you first open the main collection select "scene" game object in the outline then press the f key to focus the scene view to that object.</sub>

Check out [the documentation pages](https://defold.com/learn) for examples, tutorials, manuals and API docs.

If you run into trouble, check out the Defold [forum](https://forum.defold.com)



<sup><sub>Art Credit : Agustin R.</sub></sup>

