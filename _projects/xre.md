---
title: "XRe"
excerpt: "Harnessing the power of OpenXR and DirectX11, XRe provides a robust foundation for rendering 3D models, tracking movement, and creating interactive virtual experiences, ensuring seamless compatibility across various XR devices."
collection: projects
daterange: "06/2022 - Today"
orderkey: 0
---

**A Work-in-Progress XR Engine Built on OpenXR and DirectX11**

XRe is an experimental project designed to build a basic XR engine from scratch using OpenXR and DirectX11. Currently a work in progress, XRe serves as a learning tool for diving deeper into XR development and mastering the intricacies of OpenXR and DirectX. While it's not yet intended for direct use in XR development, the project provides valuable hands-on experience in creating immersive VR and AR applications.

### Features

XRe includes the following core functionalities:

- **Full Rendering Loop:** A dedicated rendering loop with separate methods for updating the simulation and rendering the scene, using predicted render times.
- **Model Definition & Loading:** Support for defining models from vertices and loading models from `.obj` files, enabling the creation of complex 3D objects.
- **Rendering Capabilities:** XRe can render text, flat bitmaps, simple lines, and more, allowing for diverse visual elements within virtual environments.
- **Movement & Controller Tracking:** The engine tracks controllers and supports interactions like grabbing and manipulating objects, as well as basic hand tracking for more intuitive user engagement.
- **Object Manipulation & Teleportation:** Users can grab and move objects, teleport to different locations in the scene, and use aim tracking to highlight intersections between the user’s aim and the scene.
- **Shaders & Lighting:** XRe includes a variety of shaders, such as ambient lighting and textured model shaders, adding depth and realism to the rendered environment.

Although still in its early stages, XRe offers a solid foundation for experimenting with XR technologies and is built with broad compatibility through OpenXR and DirectX11.

### Open source codebase

XRe is available as an open-source project under the MIT license, making it freely accessible for those interested in exploring XR development with OpenXR and DirectX. You can find the code on the [XRe GitHub repository](https://github.com/Adrian-Hirt/xre).

### Screenshots

<img src="{{"/images/projects/xre_screenshot_mr_portal_1.png" | relative_url }}" alt="Screenshot from Windows MR portal" style="display: block;">
*Screenshot from Windows MR portal, showcasing a very basic scene rendered in XRe. Note the tracked controllers represented as cubes, with the right controller in the `grabbing` state, as highlighted by the red color.*

<img src="{{"/images/projects/xre_hand_tracking.jpg" | relative_url }}" alt="Hand tracking in XRe" style="display: block;">
*Visualization of the tracked hand joints in XRe, leveraging the XR_EXT_hand_tracking extension from OpenXR. Grabbing objects with hands is supported as well.*