# Jake Davies 👨🏻‍💻 

I'm a PhD student who's interested in computer architecture, high performance computing, and deep learning. Knowledgable about parallel systems, including CPU and GPU architectures, and my work focuses on the compilation stack for RISC-V accelerators. 

<br>

# 🛠️ Recent Projects

## 🤖 Deep Reinforcement Learning for NES Super Mario Bros. 🎮

Implemented RainbowDQN with CUDA acceleration (via PyTorch) to train a deep reinforcement leraning agent to play Super Mario Bros. Some experiments we ran:

- Which methods yielded the most significant performance?
- How well do agents generalise across levels? (via transfer learning)
- What is the best transfer learning approach? (one level specialist, vs generalist)
- What are the best hyperparameters for our agent (coordinate descent approach)

<br>

We collected metrics for each of these, using frames (~steps) as our measure of time, which is more rigourous than episodes (which can vary in step length).
Some of our video demos and results are shown below:

<!-- [![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=jakedves&repo=deep-reinforcement-learning&theme=tokyonight)](https://github.com/jakedves/deep-reinforcement-learning) -->

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/jakedves/jakedves/blob/main/assets/full.gif">
          <img src="https://github.com/jakedves/jakedves/blob/main/assets/full.gif" alt="Full Game Performance">
        </a>
        <br>
        Full Game Performance
      </td>
      <td align="center">
        <a href="https://github.com/jakedves/jakedves/blob/main/assets/multi-1.gif">
          <img src="https://github.com/jakedves/jakedves/blob/main/assets/multi-1.gif" alt="Multi-level Training 1">
        </a>
        <br>
        Multi-level Training 1
      </td>
      <td align="center">
        <a href="https://github.com/jakedves/jakedves/blob/main/assets/multi-3.gif">
          <img src="https://github.com/jakedves/jakedves/blob/main/assets/multi-3.gif" alt="Multi-level Training 2">
        </a>
        <br>
        Multi-level Training 2
      </td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/user-attachments/assets/2deb3f63-3bf0-4d7c-98e0-7b12ceb615ea">
          <img width="516" height="383" src="https://github.com/user-attachments/assets/2deb3f63-3bf0-4d7c-98e0-7b12ceb615ea" alt="Graph comparing agent training progressions" />
        </a>
        <br>
        Comparing agents (training)
      </td>
      <td align="center">
        <a href="https://github.com/user-attachments/assets/5bcee030-1f60-434a-b764-fb524a68528c">
          <img width="516" height="383" src="https://github.com/user-attachments/assets/5bcee030-1f60-434a-b764-fb524a68528c"  alt="Graph comparing agent level completions" />
        </a>
        <br>
        Comparing agents (level completion)
      </td>
      <td align="center">
        <a href="https://github.com/user-attachments/assets/bd05f7c9-2bba-4d2a-9ff1-5286a4aaf71f">
          <img width="516" height="383" src="https://github.com/user-attachments/assets/bd05f7c9-2bba-4d2a-9ff1-5286a4aaf71f"  alt="Graph comparing transfer learning approaches" />
        </a>
        <br>
        Comparing transfer learning approaches
      </td>
    </tr>
  </table>
</div>
<br>

## 💡 Advanced Raytracer

Raytracer built from scratch in C++, with the following features:

- Global Lighting (reflections/refraction)
- Accelerated Raytracing (Bounding Boxes, multithreading parallelism)
- Quadratic Surfaces (Cones, ellipses, curved surfaces in general)
- Constructive Solid Geometries to combine surfaces
- PolyMesh rendering (`.obj` file parser that constructed triangles, see the teapot in the image)
- Phong material colouring, with photon mapping support
- Global illumination by generating and querying a photon map ([see paper](https://link.springer.com/chapter/10.1007/978-3-7091-7484-5_3))

<!-- [![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=jakedves&repo=advanced-raytracer&theme=tokyonight)](https://github.com/jakedves/advanced-raytracer) -->

<p align="center">
  <img src="https://github.com/jakedves/raytracing-coursework/assets/75232368/217beff7-61fc-4363-817e-da2755a192ba" alt="Description" width="400">
</p>
<p align="center">Final render with photon mapping</p>
</div>

<br>

<!-- images come from: https://rahuldkjain.github.io/gh-profile-readme-generator/ -->
## Languages and Tools
I'm pretty happy using any languages, with my main experience being in:

- C, C++
- Python
- Swift
- Java

<!-- [![Top Langs](https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=jakedves&theme=dracula&hide=c%23,hlsl,cmake,shaderlab,makefile)](https://github.com/jakedves/github-readme-stats) -->
