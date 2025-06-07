# Color Cloud Visualization in VR
## What
An immersive web-based 3D visualization tool that transforms real-time color data from a video into dynamic point clouds in multiple color spaces: RGB, CIEXYZ, CIExyY, and CIELAB. The application allows users to:

- Switch between color spaces interactively

- View the original video alongside the corresponding 3D color cloud

- Interact with the scene in VR/MR using Meta Quest controllers, including grabbing and moving the video plane

## How
- Used Three.js to render 3D scenes and integrate WebXR for VR/MR support

- Wrote custom GLSL shaders to:

- Sample color data from a video texture

- Convert RGB to XYZ, xyY, and LAB color spaces

- Render color points as particles with realistic depth and point sizing

- Designed different shaders for both main color cloud and its corresponding "shadow" projection

- Enabled real-time interaction using GUI (via lil-gui) and Meta Quest controller events

- Built an HTMLMesh GUI panel that is interactable inside VR

- Used a live video texture as input, sampled at regular intervals to create a 3D point cloud

## Results
- Achieved real-time, immersive visualization of color data from a video across four color models

- Provided both direct and density-based visual modes

- Enabled VR interaction for exploring color space representations spatially

- Gained hands-on experience in shader programming, 3D color theory, and XR interaction systems

- Final outcome: an educational and exploratory tool that bridges computer graphics, color science, and XR interaction design
