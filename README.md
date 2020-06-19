# visual-effect-graph
**THIS PROJECT IS DROPPED OFF DUE TO LACKING OF OFFICIAL DOCUMENTATION AND HIGHER COMPLEXITY COMPARING TO PARTICLE SYSTEM**

Unity's Visual Effect Graph (VEG) playground

## Availability
- **Unity 2019.3+**: Both `High Definition Render Pipeline` and `Universal Render Pipeline` are supported
- **Unity 2018.3+**: Only `High Definition Render Pipeline` (mostly for PC, console) is supported
- **Any Unity versions older than 2018.3**: Unavailable


## Setup
- Unity 2019.4.1f1
- Universal Render Pipeline 7.3.1
- Install VEG 7.3.1 via Package Manager
- Create a new VEG via context menu
- Drag VEG into scene
- Click Edit to open VEG window
- Edit real-time


## Terms
- **Context**: Make up a chain [ Spawn -> Initialize -> Update -> (Quad) Output ]
  - Spawn:
     - When to start this chain ?
     - How many particles will be emitted ?
     - When each particle will be emitted ?
  - Initialize:
     - Max particles (Capacity) ?
     - Initial position, rotation, scale, velocity, ...
     - Lifetime
  - Update: How will particles be updated over time ?
  - (Quad) Output:
     - How to render each particles ? (mesh, material, shader, texture, color ... )
     - Facing behavior (Billboard ...)
- **Block**: Is used to customize context
- **System**: Is the chain [ Spawn -> Initialize -> Update -> (Quad) Output ]
- **Node**: Custom nodes to feed value to blocks


## References:
| Description | Link |
|-------------|------|
| Quick introduction | [Creating explosive visuals with the VEG (Unity blog)](https://blogs.unity3d.com/2018/11/27/creating-explosive-visuals-with-the-visual-effect-graph/) |
| Official tutorial | [Introduction to the VEG in Unity 2018.4](https://learn.unity.com/tutorial/introduction-to-the-vfx-graph-unity-2018-4-lts#5df0d66dedbc2a04b7d73317) |
| Official documentation | [VEG 9.0](https://docs.unity3d.com/Packages/com.unity.visualeffectgraph@9.0/manual/index.html) |
| Blocks list (Out-dated) | [VEG 6.9 - Blocks list](https://docs.unity3d.com/Packages/com.unity.visualeffectgraph@6.9/manual/Blocks.html?_ga=2.183227494.1993550350.1592187419-1989489682.1583140292) |
| Samples | [VEG Samples (Unity 2019)](https://blogs.unity3d.com/2019/03/06/visual-effect-graph-samples/) |


