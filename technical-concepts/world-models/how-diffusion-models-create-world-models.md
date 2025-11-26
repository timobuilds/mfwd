# How Diffusion Models Create World Models?

Diffusion models learn world models implicitly through their training process:

1. **Training Phase:** The model sees millions of images/3D scenes and learns statistical patterns
2. **Latent Space:** The model develops an internal representation that captures world structure
3. **Generation Phase:** When creating new content, it samples from this learned world model
4. **Conditioning:** Additional inputs (text, depth, navmesh) guide the world model's output
