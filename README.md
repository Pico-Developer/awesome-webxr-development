# Awesome WebXR Development [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- TOC ignore:true -->
## Contents

<!-- TOC -->

- [Engine / Framework](#engine--framework)
    - [General 3D Rendering Engine](#general-3d-rendering-engine)
    - [General 3D App Framework](#general-3d-app-framework)
    - [3D Game Engine](#3d-game-engine)
    - [Visual Editor](#visual-editor)
- [State Management](#state-management)
- [Utilities](#utilities)
- [Interaction](#interaction)
    - [XR Interaction](#xr-interaction)
    - [Desktop Interaction](#desktop-interaction)
    - [Mobile Interaction](#mobile-interaction)
- [2D GUI](#2d-gui)
    - [Layout](#layout)
    - [HTML Layout](#html-layout)
    - [Form](#form)
    - [Image & Text](#image--text)
- [Animation](#animation)
    - [Skeleton Animation](#skeleton-animation)
    - [Visual Animation Editor](#visual-animation-editor)
- [Particle System](#particle-system)
- [Physics Engine](#physics-engine)
- [Gameplay](#gameplay)
- [Graphics](#graphics)
    - [Optimization](#optimization)
    - [Post Processing](#post-processing)
- [Material / Shader](#material--shader)
    - [Visual Shader Editor](#visual-shader-editor)
- [Assets](#assets)
    - [GLTF & KTX2](#gltf--ktx2)
    - [USD](#usd)
    - [Avatar](#avatar)
- [Audio](#audio)
- [Debug](#debug)
- [Learning Resources](#learning-resources)
    - [WebXR](#webxr)
        - [Case Studies](#case-studies)
        - [Performance Optimization](#performance-optimization)
    - [3D Engine / Framework](#3d-engine--framework)
    - [Graphics API, Computer Graphics](#graphics-api-computer-graphics)
    - [Game](#game)

<!-- /TOC -->

## Engine / Framework

### General 3D Rendering Engine

- [Three.js](https://threejs.org/) ![][threejs-badge] - An easy to use, lightweight, cross-browser, general purpose 3D library. The current builds only include a WebGL renderer but WebGPU (experimental), SVG and CSS3D renderers are also available as addons
- [React Three Fiber (R3F)](https://docs.pmnd.rs/react-three-fiber/) ![][threejs-badge] ![][r3f-badge] - A React renderer for three.js. Build your scene declaratively with re-usable, self-contained components that react to state, are readily interactive and can participate in React's ecosystem
- [Use.GPU](https://usegpu.live/) ![][webgpu-badge] - A set of declarative, reactive WebGPU legos. A stand-alone Typescript+Rust/WASM library with its own React-like run-time
- [Simple-GPU](https://github.com/stackgpu/Simple-GPU) ![][webgpu-badge] - Functional WebGPU. Replaces the WebGPU API with two fundamental abstractions, resources and commands

Three.js Boilerplates:

- [threejs-template-simple](https://github.com/brunosimon/threejs-template-simple) ![][threejs-badge]
- [threejs-andy-boilerplate](https://github.com/ektogamat/threejs-andy-boilerplate) ![][threejs-badge] - Very simple threejs boilerplate in VanillaJS to start your projects. There is only a basic scene, a load model method and a simple webpack

Three.js + Vite Boilerplates:

- [threejs-template-complex](https://github.com/brunosimon/threejs-template-complex) ![][threejs-badge]

### General 3D App Framework

- [React Three](https://docs.pmnd.rs/) ![][threejs-badge] ![][r3f-badge] - A vibrant and extensive eco system around three-fiber, full of libraries, helpers and abstractions
- [Babylon.js](https://www.babylonjs.com/) ![][babylon-badge] ![][webgpu-badge] - A powerful, beautiful, simple, and open game and rendering engine packed into a friendly JavaScript framework
- [A-Frame](https://aframe.io/) ![][threejs-badge] ![][aframe-badge] - A web framework for building 3D/AR/VR experiences. Make 3D worlds with HTML and Entity-Component On any headset, mobile and desktop
- [ion Engine](https://ion-3d-engine.io/) ![][threejs-badge] - A Javascript library for building 3D websites and virtual reality experiences. Supports creating interactive user interfaces for WebGL and WebXR projects using HTML/CSS/JS
- [Elixr](https://elixrjs.io/) ![][threejs-badge] - A lightweight and flexible framework for building WebXR experiences. Built on top of three.js, Rapier physics engine and [ECSY](https://ecsyjs.github.io/ecsy/)
- [Bezi](https://bezi.com/) - Bezi is a 3D design and prototyping tool for the team workflow. Bezi empowers you to ideate quickly, create compelling prototypes, and collaborate with your team-even if they don’t have 3D expertise.

React Three + Next.js Boilerplates:

- [React Three Next](https://github.com/pmndrs/react-three-next) ![][r3f-badge] - A minimalist starter for Next.js, React Three Fiber and Three.js (and Tailwind and Styled-components)

React Three Boilerplates:

- [create-r3f-app](https://github.com/utsuboco/create-r3f-app) ![][r3f-badge]
- [r3f-project-boilerplate](https://github.com/Ctrlmonster/r3f-project-boilerplate) ![][r3f-badge] - a simple boilerplate project for react three fiber projects with Typescript, TailwindCSS and Vite

A-Frame Boilerplates:

- [xr-starter-kit](https://github.com/AdaRoseCannon/aframe-xr-boilerplate) ![][aframe-badge]

### 3D Game Engine

- [PlayCanvas](https://playcanvas.com/) ![][webgpu-badge] - The web-first game engine. A visual development platform for interactive web content
- [Wonderland Engine](https://wonderlandengine.com/) ![][wasm-badge] - Development Platform
for VR & AR Web Apps
- [Ethereal Engine](https://www.etherealengine.com/) ![][threejs-badge] - Metaverse infrastructure for everyone. Everything you need to build and deploy scalable realtime 3D social apps and more
- [Phy](https://github.com/lo-th/phy) ![][threejs-badge] - Phy simplify creation of game, is like a bridge between three.js and physics. Phy support last version of Oimo and Ammo. Now full support of two best engine Physx and Havok
- [Lattice](https://github.com/unavi-xyz/lattice) - A lightweight, modular, and extendable 3D game engine built for the web. The engine is also highly performant, with speed gains from the ECS architecture and multi-threading via WebWorkers that would be difficult to achieve when using these libraries individually

### Visual Editor

- [Polygon.js](https://polygonjs.com/) ![][threejs-badge] ![][r3f-badge] - Node-Based Design & Animation Tool for the Web
- [Rogue Engine](https://rogueengine.io/) ![][threejs-badge] - A Unity3D-like environment to create WebXR enabled apps and games for the browser with three.js
- [Needle Engine](https://needle.tools/) ![][threejs-badge] ![][unity-badge] - Needle Engine is a web-based runtime for 3D apps. Needle Exporter for Unity bridges the Unity Editor and the web runtime. Together, they enable incredible iteration speeds and help you to bring your content to the web
- [Triplex](https://triplex.dev/) ![][r3f-badge] - Visually edit React Three Fiber components where code is source of truth
- [react-three-editor](https://github.com/pmndrs/react-three-editor) ![][r3f-badge] - A one of a kind scene editor that writes changes back into your code, and you don't need to change your code at all for it to to work!
- [Babylon.js Editor](https://editor.babylonjs.com/)  ![][babylon-badge] - Provide community-driven powerful and simple tools that help Babylon.JS users to create beautiful, awesome 3D games / applications
- [Theatre.js](https://www.theatrejs.com/) ![][threejs-badge] ![][r3f-badge] - Most of its users are using it as a visual editor now, than an animation editor
- [Threed Studio](https://threed.world/) ![][threejs-badge] - A 3D animation editor with a set of design, lighting and motion tools. It helps you create any 3D scene, from a simple product presentation to a complete game made with Three.js

## State Management

- [bitECS](https://github.com/NateTheGreatt/bitECS) - Functional, minimal, data-oriented, ultra-high performance ECS library written using JavaScript TypedArrays
- [Miniplex](https://github.com/hmans/miniplex) - A developer-friendly entity management system for games and similarly demanding applications, based on ECS architecture
- [Becsy](https://lastolivegames.github.io/becsy/) - Multi-threaded ECS for TypeScript and JavaScript
- [XState](https://xstate.js.org/) - JavaScript and TypeScript finite state machines and statecharts for the modern web
- [Zustand](https://github.com/pmndrs/zustand) ![][r3f-badge] - A small, fast and scalable bearbones state-management solution using simplified flux principles. Has a comfy API based on hooks, isn't boilerplatey or opinionated
- [Jotai](https://github.com/pmndrs/jotai) ![][r3f-badge] - Primitive and flexible state management for React. Scales from a simple useState replacement to an enterprise TypeScript application
- [Valtio](https://github.com/pmndrs/valtio) ![][r3f-badge] - Makes proxy-state simple for React and Vanilla

## Utilities

- [three-stdlib](https://github.com/pmndrs/three-stdlib) ![][r3f-badge] - Stand-alone version of threejs/examples/jsm written in Typescript & built for ESM & CJS. Designed to run without transpilation in node & browser
- [Drei](https://github.com/pmndrs/drei) ![][r3f-badge] - A growing collection of useful helpers and fully functional, ready-made abstractions for @react-three/fiber

## Interaction

### XR Interaction

- [@coconut-xr/natuerlich](https://github.com/coconut-xr/natuerlich) ![][r3f-badge] - WebXR Interaction library. Deliver composable and extensible interactions for immersive experiences
- [@react-three/xr](https://github.com/pmndrs/react-xr) ![][r3f-badge] - React components and hooks for creating VR/AR applications with @react-three/fiber
- [Reality Accelerator Toolkit (RATK)](https://github.com/meta-quest/reality-accelerator-toolkit) ![][threejs-badge] - A WebXR utilities library designed to simplify the integration of Mixed Reality features in WebXR apps. It is currently compatible with the three.js 3D library and aims to bridge the gap between low-level WebXR APIs and higher-level APIs provided by three.js
- [XRKeys](https://github.com/felixtrz/xrkeys) ![][threejs-badge] - A highly performant and plug-and-play WebXR keyboard library for Three.js applications
- [Handy.js](https://stewartsmith.io/handy/) - Makes defining and recognizing custom hand poses in WebXR a snap

### Desktop Interaction

- [Drei](https://github.com/pmndrs/drei) - [KeyboardControls](https://github.com/pmndrs/drei#keyboardcontrols) ![][r3f-badge] - A rudimentary keyboard controller which distributes your defined data-model to the useKeyboard hook. It's a rather simple way to get started with keyboard input
- [Drei](https://github.com/pmndrs/drei) - [PointerLockControls](https://github.com/pmndrs/drei#controls) ![][r3f-badge]
- [Floating Capsule Character Controller](https://github.com/ErdongChen-Andrew/CharacterControl) ![][r3f-badge] - Rigibody control

### Mobile Interaction

- [NippleJS](https://www.npmjs.com/package/nipplejs) - A vanilla virtual joystick for touch capable interfaces
- [MeshWalk.js](https://github.com/yomotsu/meshwalk) ![][threejs-badge] - A JS library which helps your TPS game development with three.js

## 2D GUI

### Layout

- [three-mesh-ui](https://felixmariotto.github.io/three-mesh-ui/) ![][threejs-badge] - A small library for building VR user interfaces. The objects it creates are three.object3Ds, usable directly in a three.js scene like any other Object3D. It is not a framework, but a minimalist library
- [@coconut-xr/koestlich](https://coconut-xr.github.io/koestlich) ![][r3f-badge] - Builds on yoga (flexbox implementation), Three.js to deliver compatible and performant 3D UIs with out-of-the-box animations
- [@react-three/flex](https://github.com/pmndrs/react-three-flex) ![][r3f-badge] - Brings the webs flexbox spec to react-three-fiber. It is based on Yoga, Facebook's open source layout engine for react-native

### HTML Layout
- [@etherealengine/xrui](https://github.com/EtherealEngine/etherealengine/tree/dev/packages/xrui) ![][threejs-badge] - XRUI provides functionlity for using DOM elements to construct a user interface for XR applications
- [Satori](https://github.com/vercel/satori) - Enlightened library to convert HTML and CSS to SVG
- [html2canvas](https://html2canvas.hertzen.com/) - JavaScript HTML renderer. Allows you to take "screenshots" of webpages or parts of it, directly on the users browser
- [HTMLMesh](https://github.com/mrdoob/three.js/blob/dev/examples/jsm/interactive/HTMLMesh.js) ![][threejs-badge] - [demo](https://threejs.org/examples/webxr_vr_sandbox.html)

### Form

- [r3f-form](https://github.com/JMBeresford/r3f-form) ![][r3f-badge] - A webGL form component for use with React Three Fiber. Ultimately, the goal is to have fully functioning HTML `<form>`s -- with all viable input types -- rendered in webGL
- [@coconut-xr/input](https://github.com/coconut-xr/input) ![][r3f-badge] - input fields for 3D UIs with @coconut-xr/koestlich

### Image & Text

- [Drei](https://github.com/pmndrs/drei) - [Image](https://github.com/pmndrs/drei#image) ![][r3f-badge] - A shader-based image component with auto-cover (similar to css/background: cover)
- [Drei](https://github.com/pmndrs/drei) - [Text](https://github.com/pmndrs/drei#text) ![][r3f-badge] - Hi-quality text rendering w/ signed distance fields (SDF) and antialiasing, using troika-3d-text. All of troikas props are valid! Text is suspense-based!
- [troika-three-text](https://protectwise.github.io/troika/troika-three-text/) ![][threejs-badge] - Provides high quality text rendering in Three.js scenes, using signed distance fields (SDF) and antialiasing using standard derivatives
- [troika-3d-text](https://github.com/protectwise/troika/tree/main/packages/troika-3d-text) ![][threejs-badge] - Provides high quality text rendering in the Troika scene management framework, using signed distance fields (SDF) and antialiasing using standard derivatives. It is based on troika-three-text

## Animation

- [React Spring](https://www.react-spring.dev/) [+ R3F](https://docs.pmnd.rs/react-three-fiber/tutorials/using-with-react-spring) ![][r3f-badge] - A spring-physics first animation library. It works perfectly with React Three Fiber as it comes from the same maintainers and it also has exports created specifically for use with React Three Fiber
- [Drei](https://github.com/pmndrs/drei) - [useAnimations](https://github.com/pmndrs/drei#useanimations) ![][r3f-badge] - A hook that abstracts Three.js's AnimationMixer (a player for animations on a particular object in the scene)
- [Framer Motion 3D](https://www.framer.com/motion/three-introduction/) ![][r3f-badge] - A simple yet powerful animation library for React Three Fiber. It offers most of the same functionality as Framer Motion for declarative 3D scenes

### Skeleton Animation

- [ossos](https://github.com/sketchpunklabs/ossos) - A complete character skinning & animation library for the web (with the IK Rig & IK Animations type system)

### Visual Animation Editor

- [Theatre.js](https://www.theatrejs.com/) ![][threejs-badge] ![][r3f-badge] - A javascript animation library with a professional motion design toolset. It helps you create any animation, from cinematic scenes in THREE.js, to delightful UI interactions

## Particle System

- [Three Quarks](https://quarks.art/) ![][threejs-badge] - The Fastest Real-Time Particle VFX Engine for Web Experiences For Games, VR, AR, and UX
- [Three Nebula](https://three-nebula.org/) ![][threejs-badge] - A WebGL based 3D particle system engine for Three.js
- [r3f-effekseer](https://github.com/Ctrlmonster/r3f-effekseer) ![][r3f-badge] - Provide React bindings for the WebGL + WASM runtime of Effekseer. Effekseer is a mature Particle Effect Creation Tool, which supports major game engines, is used in many commercial games, and includes its own free to use editor

## Physics Engine

- [@react-three/rapier](https://github.com/pmndrs/react-three-rapier) ![][r3f-badge] ([Rapier](https://rapier.rs/) ![][rust-badge]  ![][wasm-badge]) - A wrapper library around the Rapier (Fast 2D and 3D physics engine for the Rust) WASM-based physics engine, designed to slot seamlessly into a @react-three/fiber pipeline
- [PhysX (physx-js-webidl)](https://github.com/fabmax/physx-js-webidl) - Javascript/WASM bindings for Nvidia PhysX based on emscripten/WebIDL
- [Havok (@babylonjs/havok)](https://www.npmjs.com/package/@babylonjs/havok) - Havok is now available for the web, using a WebAssembly version of the engine. It is available, free to use, under the MIT license
- [Jolt (JoltPhysics.js)](https://github.com/jrouwe/JoltPhysics.js) - Port of JoltPhysics to JavaScript using emscripten. Jolt Physics is a multi core friendly rigid body physics and collision detection library suitable for games and VR applications, used by Horizon Forbidden West
- [use-cannon](https://github.com/pmndrs/use-cannon) ![][r3f-badge] ([cannon-es](https://github.com/pmndrs/cannon-es)) - React hooks for cannon-es (A lightweight 3D physics engine written in JavaScript). Use this in combination with @react-three/fiber
- [Oimo.js ](https://github.com/lo-th/Oimo.js) ![][threejs-badge] - A lightweight 3d physics engine for JavaScript. It's a full javascript conversion of OimoPhysics (A lightweight 3D physics engine originally created for ActionScript 3.0)
- [Enable3d](https://github.com/enable3d/enable3d) ![][threejs-badge] - Written in TypeScript, uses three.js and ammo.js, brings physics to your three.js project and the third dimension to your Phaser 3 game

## Gameplay

- [three-pathfinding](https://github.com/donmccurdy/three-pathfinding) ![][threejs-badge] - Navigation mesh toolkit for ThreeJS, based on PatrolJS (helps your AI agents navigate around your world. It uses the A* and Funnel algorithms to calculate a path on a navigation mesh)
- [recast-navigation-js](https://github.com/isaac-mason/recast-navigation-js) ![][threejs-badge] - A WebAssembly port of Recast Navigation (state of the art navigation mesh construction toolset for games)
- [Yuka](https://mugen87.github.io/yuka/) - A JavaScript library for developing Game AI

## Graphics

- [three-mesh-bvh](https://github.com/gkjohnson/three-mesh-bvh) ![][threejs-badge] - A BVH implementation to speed up raycasting and enable spatial queries against three.js meshes
- [three-bvh-csg](https://github.com/gkjohnson/three-bvh-csg) ![][threejs-badge] - A flexible, memory compact, fast and dynamic CSG implementation on top of three-mesh-bvh
- [@react-three/csg](https://github.com/pmndrs/react-three-csg) ![][r3f-badge] - Constructive solid geometry for React, a small abstraction around three-bvh-csg
- [THREE.MeshLine](https://www.npmjs.com/package/three.meshline) ![][threejs-badge] - Mesh replacement for THREE.Line. Instead of using GL_LINE, it uses a strip of triangles billboarded

### Optimization

- [react-three-offscreen](https://github.com/pmndrs/react-three-offscreen) ![][r3f-badge] - render your react-three-fiber scene with an offscreen canvas in a web worker

### Post Processing

- [@react-three/postprocessing](https://github.com/pmndrs/react-postprocessing) ![][r3f-badge] - A postprocessing wrapper for @react-three/fiber. Save you hundreds of LOC for a straight forward effects-chain. It is faster than three/examples/jsm/effectcomposer,  actively maintained, has better effects
- [three.js Realism Effects](https://github.com/0beqz/realism-effects) ![][threejs-badge] - A collection of the following effects for three.js (SSGI, Motion Blur, TRAA, TAA, SVGF)
- [three.js Screen Space Reflections](https://github.com/0beqz/screen-space-reflections) ![][threejs-badge] - Implements performant Screen Space Reflections in three.js
- [N8AO](https://n8python.github.io/n8ao/) (SSAO) ![][threejs-badge] - An efficient and visually pleasing implementation of SSAO with an emphasis on temporal stability and artist control
- [R3F-Ultimate-Lens-Flare](https://ultimate-lens-flare.vercel.app/) ![][r3f-badge] - A EffectComposer Effect (Lens Flare) for React Three Post Processing. Adds the optical aberration caused by the dispersion of light entering the lens through its edges

## Material / Shader

- [Drei](https://github.com/pmndrs/drei) - [Shader](https://github.com/pmndrs/drei#shaders) ![][r3f-badge] - Easily add reflections and/or blur to any mesh. It takes surface roughness into account for a more realistic effect. This material extends from THREE.MeshStandardMaterial and accepts all its props
- [enhanceShaderLighting](https://github.com/0beqz/enhance-shader-lighting) ![][threejs-badge] - Better lighting in three.js. Make your PBR material look more realistic. Give the user a lot of options to tweak lighting so that a certain combination of settings will give a decent looking result
- [Custom Shader Material (CSM)](https://github.com/FarazzShaikh/THREE-CustomShaderMaterial) ![][threejs-badge] - Extend Three.js standard materials with your own shaders! It Supports both Vanilla and React!
- [Three Landscape](https://github.com/nwpointer/three-landscape) ![][r3f-badge] - A growing collection of React-three-fiber compatible abstractions for rendering high quality, large scale landscapes scenes. I've been researching how AAA games render terrain and am replicating any browser compatible techniques here
- [Shader Composer](https://github.com/hmans/composer-suite/tree/main/packages/shader-composer) ![][threejs-badge] - A library for authoring Three.js shaders with JavaScript. It offers a lean, functional API that makes shader composition straight-forward and fun, while allowing for simple, low-friction reusability of your favorite shader functions

### Visual Shader Editor

- [NodeToy](https://nodetoy.co/) ![][threejs-badge] ![][r3f-badge] - The most powerful material editor on the web. Built for ThreeJS & React-Three-Fiber. Create, fork and publish shader graphs with the world using an intuitive and easy to use tool built for all
- [Babylon NME (Node Material Editor)](https://nme.babylonjs.com/)  ![][babylon-badge] - Shader-based materials editor for Babylon.js
- [lamina](https://github.com/pmndrs/lamina) ![][r3f-badge] - An extensible, layer based shader material for ThreeJS. Built on top of three-custom-shader-material (CSM) and any effects that are achieved by lamina can be done with CSM in a predictable and performant manner albeit at a lower level
- [Alma](https://www.alma.sh/) - Generative Graphics Creator

## Assets

### GLTF & KTX2

- [Drei](https://github.com/pmndrs/drei) - [GLTF](https://github.com/pmndrs/drei#gltf) ![][r3f-badge] - A convenience component that will load a gltf file and clone the scene using drei/Clone. That means you can re-use and mount the same gltf file multiple times
- [gltfjsx](https://github.com/pmndrs/gltfjsx) ![][r3f-badge] - A small command-line tool that turns GLTF assets into declarative and re-usable react-three-fiber JSX components
- [glTF-Transform](https://gltf-transform.donmccurdy.com/) - glTF 2.0 SDK for JavaScript and TypeScript, on Web and Node.js. Provides fast, reproducible, and lossless control of the low-level details in a 3D model
- [glTFast](https://github.com/atteneder/glTFast) - Enables use of glTF asset files in Unity (import / export)
- [gltfpack](https://github.com/zeux/meshoptimizer/tree/master/gltf) - A tool that can automatically optimize glTF files to reduce the download size and improve loading and rendering speed
- [glTF Pipeline](https://github.com/CesiumGS/gltf-pipeline) - Content pipeline tools for optimizing glTF assets by the Cesium team

### USD

- [Asset Explorer](https://asset-explorer.needle.tools/) - Contains glTF models and their USDZ counterparts. This page is targeted at implementers, developers, and designers working with these file formats. A clear goal is to allow you to download files for a specific usecase and check if your target viewer/platform supports what you want it to support

### Avatar

- [three-vrm](https://github.com/pixiv/three-vrm/) ![][threejs-badge] - Use VRM (a file format for handling 3D humanoid avatar data for VR applications. It is based on glTF2.0) on three.js

## Audio

- [Howler.js](https://howlerjs.com/) - Audio library for the modern web. It defaults to Web Audio API and falls back to HTML5 Audio. This makes working with audio in JavaScript easy and reliable across all platforms
- [Tone.js](https://tonejs.github.io/) - A Web Audio framework for creating interactive music in the browser. Aims to be familiar to both musicians and audio programmers creating web-based audio applications. Offers common DAW (digital audio workstation) features. Provides high-performance building blocks to create your own synthesizers, effects, and complex control signals

## Debug

- [Immersive Web Emulator](https://github.com/meta-quest/immersive-web-emulator) - A browser extension that assists WebXR content creation. It enables developers to responsively run WebXR apps on a desktop browser without the need of an XR device. Inspired by the official WebXR Emulator Extension by Mozilla Reality and our previous efforts of extending it for better functionality, designed and rebuilt from the ground up
- [LogXR](https://github.com/felixtrz/logxr) - A debugging utility that makes it easy to view console logs in WebXR experiences. Currently, LogXR only supports Three.js, with support for Babylon.js coming soon
- [Spector.js](http://spector.babylonjs.com/) ![][babylon-badge] - A complete engine agnostic JavaScript framework for exploring and troubleshooting your WebGL scenes with ease
- [R3F-Perf](https://github.com/utsuboco/r3f-perf) ![][r3f-badge] - Easily monitor the performances of your @react-three/fiber application
- [three-perf](https://github.com/TheoTheDev/three-perf) ![][threejs-badge] - Vanilla Three.js port of r3f-perf(opens in a new tab)
- [stats-gl](https://github.com/RenaudRohlinger/stats-gl) - WebGL Performance Monitor tool
- [stats.js](https://github.com/mrdoob/stats.js/) ![][threejs-badge] - JavaScript Performance Monitor. Provides a simple info box that will help you monitor your code performance
- [Drei](https://github.com/pmndrs/drei) - [PerformanceMonitor](https://github.com/pmndrs/drei#performancemonitor) ![][r3f-badge] - Collect the average fps over time
- [webgpu-avoid-redundant-state-setting](https://github.com/greggman/webgpu-avoid-redundant-state-setting) - Check for and avoid redundant state setting
- [@react-three/test-renderer](https://github.com/pmndrs/react-three-fiber/tree/master/packages/test-renderer) ![][r3f-badge] - A React testing renderer for threejs in node

[threejs-badge]: https://badgen.net/badge/eco/three.js/?color=blue
[r3f-badge]: https://badgen.net/badge/eco/react-three/?color=cyan
[aframe-badge]: https://badgen.net/badge/eco/a-frame/?color=pink
[babylon-badge]: https://badgen.net/badge/eco/babylon.js/?color=orange
[rust-badge]: https://badgen.net/badge/eco/rust/?color=red
[wasm-badge]: https://badgen.net/badge/eco/wasm/?color=purple
[unity-badge]: https://badgen.net/badge/eco/unity/?color=black
[webgpu-badge]: https://badgen.net/badge/eco/webgpu/?color=green

## Learning Resources

### WebXR

- [MDN Tutorials](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API#guides_and_tutorials) - A great resource to learn how to comprehend WebXR and the underlying 3D and VR/AR graphics concepts
- [WebXR Samples](https://immersive-web.github.io/webxr-samples/) - Created to give developers a set of simple, fun, readable apps that demonstrate various aspects of using the WebXR API. Designed to focus on API use rather than the details of how the WebGL rendering is done
- [W3C standards and explainers](https://immersive-web.github.io/)

#### Case Studies

- [Project Flowerbed: A WebXR Case Study](https://developer.oculus.com/blog/project-flowerbed-a-webxr-case-study/) - At [Connect ‘22](https://metaconnect.com/en-us/program/fbc029/?intern_source=devblog&intern_content=project-flowerbed-a-webxr-case-study), Meta unveiled [Project Flowerbed](https://flowerbed.metademolab.com/) to demonstrate best practices for developers building high-quality WebXR experiences. Now, as an [open source project](https://github.com/meta-quest/ProjectFlowerbed), it’s even easier for developers to learn about our architecture, asset pipeline, and game mechanics
- [Slow Roads](https://web.dev/slow-roads/) - How Slow Roads intrigues gamers and developers alike, spotlighting the surprising capabilities of 3D in the browser. Discover the potential of WebGL with the infinite, procedurally-generated scenery of this casual driving game. [Slow Roads](https://slowroads.io/) is a casual driving game with an emphasis on endlessly procedurally generated scenery, all hosted in the browser as a WebGL application.
- [SUMMER AFTERNOON](https://www.awwwards.com/summer-afternoon.html) - The memories of those summer days in our childhood when time seemed to pass slowly often evoke a strong sense of nostalgia for many of us. [Summer Afternoon](https://summer-afternoon.vlucendo.com/) is a personal project in which my initial goal was to practice creating 3D environments like those found in video games and other immersive experiences. Shortly after starting to work on it, I realized that my true goal with the experiment had transformed and was no longer just to practice a specific technical area, but also to convey a feeling of calmness and nostalgia to visitors
- [Above Paradowski WebXR Mini-Golf](https://paradowski.com/stories/above-par-adowski-webxr-mini-golf) - Taking [WebXR putt putt](https://aboveparadowski.com/) from prototype to polished product on par with native Quest 2 games
- [Making PuttClub.io](https://www.etherealengine.com/blog-posts/making-puttclub-io-social-webxr-games-in-full-body-vr) - Social WebXR Games in Full Body VR. [The VR game](https://www.puttclub.io/) was developed to showcase the capabilities of Ethereal Engine, and serves as a key driving force in developing what we believe to be the most powerful web based immersive engine available today
- [Building with WebXR at the Presence Platform Hackathon](https://developer.oculus.com/blog/webxr-presence-platform-hackathon-meta-quest/) - Five of these developer teams built WebXR apps that ran directly inside the Meta Quest Browser, without having to install anything

#### Performance Optimization

- [MDN - WebXR performance guide](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API/Performance)
- [Meta Quest - WebXR Performance Optimization](https://developer.oculus.com/documentation/web/webxr-perf-workflow/)
  - [Project Flowerbed - Performance & Optimization](https://developer.oculus.com/documentation/web/webxr-perf-workflow/)
- [AFrame - Performance Best Practices](https://aframe.io/docs/1.4.0/introduction/best-practices.html#performance)
- [Wonderland Engine - How We Profile WebXR/WebGL Apps](https://wonderlandengine.com/news/profiling-webxr-applications/)

### 3D Engine / Framework

- [R3F Journey](https://journey.pmnd.rs/)
- [Three.js Journey](https://threejs-journey.com/) - The Best Way to Learn Three.js. In 71 hours of video, this course will teach you the secrets to create the coolest WebGL websites with Three.js whether you are a beginner or an advanced developer
- [Discover three.js](https://discoverthreejs.com/) - A complete introduction to the web as a platform for 3D graphics using the three.js WebGL library, from one of the core three.js developers. Designed to get you started on your journey of creating modern, professional-quality 3D web applications in the shortest time possible
- [Threejs 零基础入门](http://www.webgl3d.cn/pages/4a14ce/)

### Graphics API, Computer Graphics

- [LearnOpenGL](https://learnopengl.com/) - Show you all there is to modern OpenGL in an easy-to-understand fashion with clear examples, while also providing a useful reference for later studies
- [Web3D Survey](https://web3dsurvey.com) - Solves a common problem that 3D graphics web developers face: which API features can I use reliably? We solve this problem by collecting web graphics API capabilities and features widely across the web and then presenting that data back on this website so 3D graphics web developers can make informed decisions and reliable experiences.
- [WebGL2 Fundamentals](https://webgl2fundamentals.org/) - WebGL2 from the ground up. No magic. Entirely new, discarding the old out of date ideas and bringing you to a full understanding of what WebGL really is and how it really works
- [Introduction to WebGPU - CIS 565 GPU Programming Fall 2022](https://youtu.be/Hm2_bH_8j3k) - Covering the WebGPU graphics API. Covers a wide range of WebGPU topics, including API overview, comparison with WebGL, best practices, and more
- [WebGPU — All of the cores, none of the canvas](https://surma.dev/things/webgpu/)
- [MDN - WebGPU API](https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API)
- [WebGPU Explainer](https://gpuweb.github.io/gpuweb/explainer/)
- [WebGPU Fundamentals](https://webgpufundamentals.org/) - Teach you the very fundamentals of WebGPU
- [WebGPU Samples](https://webgpu.github.io/webgpu-samples/) - A set of samples demonstrating the use of the WebGPU API
- [WebGPU Best Practices](https://toji.dev/webgpu-best-practices/) - Focused on the most effective patterns for working with specific parts of the API, especially if you are a developer that’s familiar with WebGL or one of the native APIs
- [The Book of Shaders](https://thebookofshaders.com/) - A gentle step-by-step guide through the abstract and complex universe of Fragment Shaders
- [Shader School](https://github.com/stackgl/shader-school) - An introduction to GLSL shaders and graphics programming that runs in your web browser
- [GAMES101: 现代计算机图形学入门](https://sites.cs.ucsb.edu/~lingqi/teaching/games101.html)

### Game

- [Web Game Dev](https://www.webgamedev.com/) - A work-in-progress collection of resources on techniques and tools around JavaScript game development, which apply to 2D and 3D games, and to visual experiences that are not games
- [Red Blob Games](https://www.redblobgames.com/) -  I make interactive visual explanations of math and algorithms, using motivating examples from computer games
