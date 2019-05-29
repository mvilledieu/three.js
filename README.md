### /!\ Experimental Fork, WebXR using three on Magic Leap's Helio /!\

Custom version of [three.js](https://threejs.org/) used to test and update the WebXR API implementation in three and Helio and make sure they match. The goal is then to use the work done here and propose updates to the main three.js repo. WebXR is still an unstable API and breaking changes are constantly introduced. 

## Installing (At your own risk)

If you use npm, run  `npm i ml-three`. Otherwise, to add the minified version:

```
<script src="https://unpkg.com/ml-three/build/three.min.js"></script>
```

To add the non minified version:

```
<script src="https://unpkg.com/ml-three/build/three.js"></script>
```

#### /!\ Only tested on Helio (Lumin OS **0.96.0**) /!\

**Try the three.js WebXR samples**
- [Working WebXR examples](https://mvilledieu.github.io/three.js/examples/?q=webvr)

**Start building using the hello world**
- [WebXR Hello World](https://github.com/mvilledieu/ml-threejs-webxr-hello-world)
