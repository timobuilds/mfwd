# SOTA ranking



### ⚔️ World Generation Systems Comparison

Let's compare three cutting-edge approaches to world generation: WorldGen (Meta), Marble (World Labs), and Genie 2 (DeepMind).

| Aspect                | 🌍 WorldGen (Meta)           | 🔮 Marble (World Labs)     | 🎮 Genie 2 (DeepMind)         |
| --------------------- | ---------------------------- | -------------------------- | ----------------------------- |
| **Core Approach**     | Text → 3D Meshes             | Image → Gaussian Splats    | Text → Interactive Video      |
| **Input Type**        | Text prompt                  | Single image               | Text or image prompt          |
| **Output Format**     | Textured 3D meshes + navmesh | 3D Gaussian Splatting      | Interactive video stream      |
| **3D Representation** | Explicit geometry (meshes)   | Semi-implicit (Gaussians)  | Implicit (no 3D, just pixels) |
| **Scene Size**        | \~50×50 meters               | \~3-5 meter bubble         | Infinite (but 2D projection)  |
| **Generation Time**   | \~5 minutes                  | \~30 seconds               | Real-time (11 FPS)            |
| **Game Engine Ready** | ✅ Yes (native meshes)        | ❌ No (needs conversion)    | ❌ No (just video)             |
| **Editability**       | ✅ Individual objects         | ⚠️ Limited                 | ❌ None                        |
| **Navigation**        | ✅ Full navmesh               | ✅ Free camera movement     | ⚠️ Action-based only          |
| **Visual Quality**    | High (2K-4K textures)        | Very High (photorealistic) | Good (720p video)             |

<br>
