# RT

Developed in collaboration with:

|<img src="https://avatars2.githubusercontent.com/u/37712616?s=400&v=4" width="75px;"/>|<img src="https://avatars0.githubusercontent.com/u/46439498?s=400&v=4" width="75px;"/>|
| --------- | --------- | 
| [Arsen Abdullaiev](https://github.com/aisenn) |[Maksym Hedeon](https://github.com/mhedeon)|

The goal of this project is to implement a ray tracing algorithm. This render tool supports drawing elementary geometric shapes like sphere, cone, cylinder, plane and additional composed object - a wine glass. It displays shapes with given light sources depending on the viewpoint.

Additional functionality:
- ability to slice objects;
- point of view rotation and translation along XYZ axis in real time;
- reflection material property;
- GUI, screenshots option, sepia effect, etc.

Makefile supports such targets: make all, clean, fclean, re.
In [scene](/scene) directory you can find test maps.

### Manual file
+ cat MAN

### Usage
+ make
+ ./RT scene/configuration_file

### Examples

![Scene0](https://github.com/mhedeon/RT/blob/master/screenshots/screenshot0.png?raw=true "Basic scene")
![Scene1](https://github.com/mhedeon/RT/blob/master/screenshots/screenshot1.png?raw=true "Basic scene in sepia")
![Scene2](https://github.com/mhedeon/RT/blob/master/screenshots/screenshot2.png?raw=true "Columns")
![Scene3](https://github.com/mhedeon/RT/blob/master/screenshots/screenshot3.png?raw=true "Reflection scene")
