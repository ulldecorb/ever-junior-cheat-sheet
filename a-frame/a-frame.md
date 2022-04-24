# A-FRAME
A web framework for building 3D/AR/VR experiences.
## Table of Content
* [Install](#install)
* [Concepts](#concepts)
* [ECS](#entity-component-system)
* []()
* []()
* []()
* []()
* []()
* [Links](#links)

## [INSTALL](https://aframe.io/docs/1.3.0/introduction/installation.html)
> CDN    
```html
<head>
  <script src="https://aframe.io/releases/1.3.0/aframe.min.js"></script>
</head>
```
> NPM   
```bash
$ npm install aframe
```
```javascript
require('aframe');
```
Also can use angle: command line interface for A-Frame
```bash
npm install -g angle && angle initscene
```
## Concepts
> Headsets features:   

Positional tracking (six degrees of freedom (6DoF))   
Rotation tracking (three degrees os freedom (3DoF))   

> WebXR:    

A-Frame uses the WebXR API to gain access to VR headset sensor data (position, orientation) to transform the camera and to render content directly to VR headsets.
> Primitives (also refers as [assemblages](http://vasir.net/blog/game-development/how-to-build-entity-component-system-in-javascript))

```html
<a-box color="red" width="3"></a-box>
```
sugar syntactic for:
```html
<a-entity geometry="primitive: box; width: 3" material="color: red"></a-entity>
```

> [Registering a Primitive](https://aframe.io/docs/1.3.0/introduction/html-and-primitives.html#registering-a-primitive)
```javascript
AFRAME.registerPrimitive(name, definition)
```
## Entity-Component-System
* [Entity-component-system on Wikipedia](https://en.wikipedia.org/wiki/Entity_component_system)
* [What is an Entity System? by Adam Martin](http://t-machine.org/index.php/2007/11/11/entity-systems-are-the-future-of-mmog-development-part-2/)
* [Decoupling Patterns — Component on Game Programming Patterns](http://gameprogrammingpatterns.com/component.html)
* [Evolve Your Hierarchy by Mick West](https://cowboyprogramming.com/2007/01/05/evolve-your-heirachy/)








## Links
* [Glitch to quick Test](https://glitch.com/edit/#!/reliable-righteous-belt?path=index.html%3A6%3A8)
* [A-frame school](https://aframe.io/)   
* [A-frame docs](https://aframe.io/docs/1.3.0/introduction/)
* [three.js](https://threejs.org/)