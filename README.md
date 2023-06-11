# SFEAR

Welcome to my ThreeJS Spinning Ball project repository named Sfear! This repository contains the codebase for a simple ThreeJS site that features a spinning ball controlled by the user. This Readme file will guide you through the repository, explain how to get started with the codebase, and share some of my insights as a first-timer to ThreeJS.

## Table of Contents

- [SFEAR](#sfear)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Learnings](#learnings)

## Introduction

This ThreeJS Spinning Ball project was my introduction to ThreeJS and showcases a simple interactive scene. With this project I got a sense of how to manipulate 3D objects within a web environment.

## Features

- Interactive 3D ball spinning controlled by user input.
- Realistic shading and materials applied to the ball.
- Smooth animation and rotation effects.
- Ball Damping
- Color Change on Click

## Installation

To set up the project locally on your machine, follow these steps:

1. Clone the repository: `git clone https://github.com/Abuka-Victor/Sfear.git`
2. Navigate to the project directory: `cd Sfear`

## Usage

Once you have cloned the repository and navigated to the project directory, you can run the project locally:

1. Open the project in a code editor of your choice.
2. Open the terminal and navigate to the project directory.
3. Run `npm i`
4. Run `npm run dev`
5. Open your browser to `localhost:5173`

You should now see the spinning ball in action! Use your mouse or touchpad to interact with the ball and control its rotation.

## Learnings

As a first-timer to ThreeJS, these are my takeaways:

1. Understanding the ThreeJS Architecture: Its basically a movie set but with JavaScript code. You have primarily the scene, camera, renderer, and of course the stars of the show, the objects known as Mesh in threeJs. To make a mesh you need a geometry(Solid Object) and a material(Texture configuration or look and feel).

2. Geometry and Materials: I learned about different geometries (such as spheres, cubes, etc.) and materials (such as basic, phong, etc.) available in ThreeJS. Experimenting with different combinations can actually lead to some exciting visual effects. I tried ti have a sun set animation initially but I gave up, lol. Another time maybe.

3. User Interaction and Controls: I learned to use OrbitControls to enable user interaction and controls to manipulate objects. Apparently there are other control schemes but the one I used in this project is the OrbitControls scheme. One can also implement custom controls using mouse or touch events, but I didn't do that, at least not yet.

4. Animation and Rendering: I learnt about some animation techniques in ThreeJS, such as using the `requestAnimationFrame` loop and updating object properties over time specifically delta time which I used Gsap to do. Honestly that was more like a hack. I had to use the loop to rerender the whole canvas everytime there was a window resize (used an eventlistener for that). Sorry slow pcs. I also did some small optimizations for smoother animations like the width and height of the sphere itself I set to (64, 64) so it doesn't look like a polygon and I set the pixelratio to a 2 for smoothness and reduced pixelation.

5. Resources and Documentation: I heavily utilized the documentation and code examples available on the ThreeJS website.

If you have any questions or need assistance while working with the project, don't hesitate to reach out. Happy spinning and exploring.
