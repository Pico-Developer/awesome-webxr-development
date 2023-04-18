# Awesome WebXR Stack [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- TOC ignore:true -->
## Contents

<!-- vscode-markdown-toc -->
* [Engine / Framework](#EngineFramework)
	* [General 3D Rendering Engine](#General3DRenderingEngine)
	* [General 3D App Framework](#General3DAppFramework)
	* [3D Game Engine](#DGameEngine)
	* [Visual Editor](#VisualEditor)
* [XR Interaction](#XRInteraction)
* [2D GUI](#DGUI)
	* [Layout](#Layout)
	* [Form](#Form)
	* [Image & Text](#ImageText)
* [Animation](#Animation)
	* [Skeleton Animation](#SkeletonAnimation)
	* [Visual Animation Editor](#VisualAnimationEditor)
* [Particle System](#ParticleSystem)
* [Physics Engine](#PhysicsEngine)
* [Graphic](#Graphic)
* [Material / Shader](#MaterialShader)
	* [Visual Shader Editor](#VisualShaderEditor)
* [Assets](#Assets)
	* [GLTF & KTX2](#GLTFKTX2)
	* [Avatar](#Avatar)
* [Debug](#Debug)
* [Learning Resource](#LearningResource)
	* [WebXR](#WebXR)
		* [Case Study](#CaseStudy)
	* [3D Engine / Framework](#DEngineFramework)
	* [Graphics API, Computer Graphics](#GraphicsAPIComputerGraphics)

<!-- vscode-markdown-toc-config
	numbering=false
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

## <a name='EngineFramework'></a>Engine / Framework

### <a name='General3DRenderingEngine'></a>General 3D Rendering Engine

- [Three.js](https://threejs.org/) ![][threejs-badge]
- [React Three Fiber (R3F)](https://docs.pmnd.rs/react-three-fiber/) ![][threejs-badge] ![][r3f-badge]
- [Use.GPU](https://usegpu.live/) ![][webgpu-badge]
- [Simple-GPU](https://github.com/stackgpu/Simple-GPU) ![][webgpu-badge]

Three.js Boilerplates:

- [threejs-template-simple](https://github.com/brunosimon/threejs-template-simple) ![][threejs-badge]

Three.js + Vite Boilerplates:

- [threejs-template-complex](https://github.com/brunosimon/threejs-template-complex) ![][threejs-badge]

### <a name='General3DAppFramework'></a>General 3D App Framework

- [React Three](https://docs.pmnd.rs/) ![][threejs-badge] ![][r3f-badge]
- [A-Frame](https://aframe.io/) ![][threejs-badge] ![][aframe-badge]
- [Babylon.js](https://www.babylonjs.com/) ![][babylon-badge] ![][webgpu-badge]

React Three + Next.js Boilerplates:

- [React Three Next](https://github.com/pmndrs/react-three-next) ![][r3f-badge]

React Three Boilerplates:

- [create-r3f-app](https://github.com/utsuboco/create-r3f-app) ![][r3f-badge]

A-Frame Boilerplates:

- [xr-starter-kit](https://github.com/AdaRoseCannon/aframe-xr-boilerplate) ![][aframe-badge]

### <a name='DGameEngine'></a>3D Game Engine

- [PlayCanvas](https://playcanvas.com/) ![][webgpu-badge]
- [Wonderland Engine](https://wonderlandengine.com/) ![][wasm-badge]
- [Ethereal Engine](https://www.etherealengine.com/) ![][threejs-badge]

### <a name='VisualEditor'></a>Visual Editor

- [Polygon.js](https://polygonjs.com/) ![][threejs-badge] ![][r3f-badge]
- [Rogue Engine](https://rogueengine.io/) ![][threejs-badge]
- [Needle Engine](https://needle.tools/) ![][threejs-badge] ![][unity-badge]
- [react-three-editor](https://github.com/pmndrs/react-three-editor) ![][r3f-badge]
- [Babylon.js Editor](https://editor.babylonjs.com/)  ![][babylon-badge]

## <a name='XRInteraction'></a>XR Interaction

- [@react-three/xr](https://github.com/pmndrs/react-xr) ![][r3f-badge]

## <a name='DGUI'></a>2D GUI

### <a name='Layout'></a>Layout

- [three-mesh-ui](https://felixmariotto.github.io/three-mesh-ui/) ![][threejs-badge]
- [@coconut-xr/koestlich](https://coconut-xr.github.io/koestlich) ![][r3f-badge]
- [@react-three/flex](https://github.com/pmndrs/react-three-flex) ![][r3f-badge]
- [@etherealengine/xrui](https://github.com/EtherealEngine/etherealengine/tree/dev/packages/xrui) ![][threejs-badge]

### <a name='Form'></a>Form

- [r3f-form](https://github.com/JMBeresford/r3f-form) ![][r3f-badge]
- [@coconut-xr/input](https://github.com/coconut-xr/input) ![][r3f-badge]

### <a name='ImageText'></a>Image & Text

- [Drei](https://github.com/pmndrs/drei) - [Image](https://github.com/pmndrs/drei#image) ![][r3f-badge]
- [Drei](https://github.com/pmndrs/drei) - [Text](https://github.com/pmndrs/drei#text) ![][r3f-badge]
- [troika-three-text](https://protectwise.github.io/troika/troika-three-text/) ![][threejs-badge]
- [troika-3d-text](https://github.com/protectwise/troika/tree/main/packages/troika-3d-text) ![][threejs-badge]

## <a name='Animation'></a>Animation

- [React Spring](https://www.react-spring.dev/) [+ R3F](https://docs.pmnd.rs/react-three-fiber/tutorials/using-with-react-spring) ![][r3f-badge]
- [Drei](https://github.com/pmndrs/drei) - [useAnimations](https://github.com/pmndrs/drei#useanimations) ![][r3f-badge]

### <a name='SkeletonAnimation'></a>Skeleton Animation

- [ossos](https://github.com/sketchpunklabs/ossos)

### <a name='VisualAnimationEditor'></a>Visual Animation Editor

- [Theatre.js](https://www.theatrejs.com/) ![][threejs-badge] ![][r3f-badge]

## <a name='ParticleSystem'></a>Particle System

- [Three Quarks](https://quarks.art/) ![][threejs-badge]
- [Three Nebula](https://three-nebula.org/) ![][threejs-badge]

## <a name='PhysicsEngine'></a>Physics Engine

- [@react-three/rapier](https://github.com/pmndrs/react-three-rapier) ![][r3f-badge] ([Rapier](https://rapier.rs/) ![][rust-badge]  ![][wasm-badge])
- [use-cannon](https://github.com/pmndrs/use-cannon) ![][r3f-badge] ([cannon-es](https://github.com/pmndrs/cannon-es))

## <a name='Graphic'></a>Graphic

- [three-mesh-bvh](https://github.com/gkjohnson/three-mesh-bvh) ![][threejs-badge]
- [three-bvh-csg](https://github.com/gkjohnson/three-bvh-csg) ![][threejs-badge]
- [@react-three/csg](https://github.com/pmndrs/react-three-csg) ![][r3f-badge]

## <a name='MaterialShader'></a>Material / Shader

- [Drei](https://github.com/pmndrs/drei) - [Shader](https://github.com/pmndrs/drei#shaders) ![][r3f-badge]
- [Three Landscape](https://github.com/nwpointer/three-landscape) ![][r3f-badge]

### <a name='VisualShaderEditor'></a>Visual Shader Editor

- [NodeToy](https://nodetoy.co/) ![][threejs-badge] ![][r3f-badge]
- [Babylon NME (Node Material Editor)](https://nme.babylonjs.com/)  ![][babylon-badge]
- [lamina](https://github.com/pmndrs/lamina) ![][r3f-badge]
- [Alma](https://www.alma.sh/)

## <a name='Assets'></a>Assets

### <a name='GLTFKTX2'></a>GLTF & KTX2

- [Drei](https://github.com/pmndrs/drei) - [GLTF](https://github.com/pmndrs/drei#gltf) ![][r3f-badge]
- [gltfjsx](https://github.com/pmndrs/gltfjsx) ![][r3f-badge]
- [glTF-Transform](https://gltf-transform.donmccurdy.com/)
- [glTFast](https://github.com/atteneder/glTFast)
- [gltfpack](https://github.com/zeux/meshoptimizer/tree/master/gltf)

### <a name='Avatar'></a>Avatar

- [three-vrm](https://github.com/pixiv/three-vrm/) ![][threejs-badge]

## <a name='Debug'></a>Debug

- [Immersive Web Emulator](https://github.com/meta-quest/immersive-web-emulator)
- [LogXR](https://github.com/felixtrz/logxr)
- [R3F-Perf](https://github.com/utsuboco/r3f-perf) ![][r3f-badge]
- [Drei](https://github.com/pmndrs/drei) - [PerformanceMonitor](https://github.com/pmndrs/drei#performancemonitor) ![][r3f-badge]
- [@react-three/test-renderer](https://github.com/pmndrs/react-three-fiber/tree/master/packages/test-renderer) ![][r3f-badge]

[threejs-badge]: https://badgen.net/badge/eco/three.js/?color=blue
[r3f-badge]: https://badgen.net/badge/eco/react-three/?color=cyan
[aframe-badge]: https://badgen.net/badge/eco/a-frame/?color=pink
[babylon-badge]: https://badgen.net/badge/eco/babylon.js/?color=orange
[rust-badge]: https://badgen.net/badge/eco/rust/?color=red
[wasm-badge]: https://badgen.net/badge/eco/wasm/?color=purple
[unity-badge]: https://badgen.net/badge/eco/unity/?color=black
[webgpu-badge]: https://badgen.net/badge/eco/webgpu/?color=green

## <a name='LearningResource'></a>Learning Resource

### <a name='WebXR'></a>WebXR

- [MDN Tutorials](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API#guides_and_tutorials)
- [WebXR Samples](https://immersive-web.github.io/webxr-samples/)
- [W3C standards and explainers](https://immersive-web.github.io/)

#### <a name='CaseStudy'></a>Case Study

- [Project Flowerbed: A WebXR Case Study](https://developer.oculus.com/blog/project-flowerbed-a-webxr-case-study/)
- [Slow Roads](https://web.dev/slow-roads/) - How Slow Roads intrigues gamers and developers alike, spotlighting the surprising capabilities of 3D in the browser
- [SUMMER AFTERNOON](https://www.awwwards.com/summer-afternoon.html)
- [Above Paradowski WebXR Mini-Golf](https://paradowski.com/stories/above-par-adowski-webxr-mini-golf) - Taking WebXR putt putt from prototype to polished product on par with native Quest 2 games
- [Making PuttClub.io](https://www.etherealengine.com/blog-posts/making-puttclub-io-social-webxr-games-in-full-body-vr) - Social WebXR Games in Full Body VR

### <a name='DEngineFramework'></a>3D Engine / Framework

- [R3F Journey](https://journey.pmnd.rs/)
- [Three.js Journey](https://threejs-journey.com/)
- [Discover three.js](https://discoverthreejs.com/)
- [Threejs零基础入门](http://www.webgl3d.cn/pages/4a14ce/)

### <a name='GraphicsAPIComputerGraphics'></a>Graphics API, Computer Graphics

- [LearnOpenGL](https://learnopengl.com/)
- [Web3D Survey](https://web3dsurvey.com)
- [WebGL2 Fundamentals](https://webgl2fundamentals.org/)
- [Introduction to WebGPU - CIS 565 GPU Programming Fall 2022](https://youtu.be/Hm2_bH_8j3k)
- [WebGPU — All of the cores, none of the canvas](https://surma.dev/things/webgpu/)
- [MDN - WebGPU API](https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API)
- [WebGPU Explainer](https://gpuweb.github.io/gpuweb/explainer/)
- [WebGPU Fundamentals](https://webgpufundamentals.org/)
- [WebGPU Best Practices](https://toji.dev/webgpu-best-practices/)
- [The Book of Shaders](https://thebookofshaders.com/)
- [Shader School](https://github.com/stackgl/shader-school)
- [GAMES101: 现代计算机图形学入门](https://sites.cs.ucsb.edu/~lingqi/teaching/games101.html)
