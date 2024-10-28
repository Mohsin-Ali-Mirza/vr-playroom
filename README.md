# vr_playroom

<img src="/images/video_sample.gif"/>

## Project Overview
The VR Playroom is an immersive space designed to explore foundational VR concepts through hands-on experimentation with Unity. This project integrates locomotion, object interaction, and user interface elements to create a dynamic, engaging environment.

### Locomotion and Rotation:
- **Snap Turning:** Provides stationary rotation through the `Snap Turn Provider` component for a comfortable, anchored VR experience.
- **Continuous Turning:**  Enables fluid, continuous rotation with the `Continuous Turn Provider` for a more natural and immersive feel.

### Teleportation Zones:
- **Areas:** Designated zones (e.g., a rug) where users can teleport seamlessly using the `Teleportation Area` component.
- **Anchors:** Targeted teleportation points on mats, preset with specific directions to ensure users face the right way upon arrival.

### Grabbable Objects:
- **XR Grab Interacterable:** Enhanced interaction through the `XR Grab Interactable` component and Rigidbody integration, allowing objects to be manipulated realistically.
- **XR Ray Interactor:** Facilitates distant interaction, enabling users to grab and interact with objects beyond immediate reach.

### Sockets:
Attachable and interactive elements like hats can be easily placed on hooks or equipped directly onto the user’s VR avatar, adding to the interactive experience.

### User Interface and Feedback
- **Custom Reticles:** Provides enhanced visual feedback for teleportation by customizing reticles to improve user orientation and destination clarity.
- **Fade Canvas:** Added a fade-in/fade-out canvas effect during teleportation to reduce motion-induced dizziness, providing a more comfortable experience.
