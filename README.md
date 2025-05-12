# 💡 OpenGL Shader Program in C++

A collection of custom **OpenGL shaders** written in C++, covering key visual effects such as **lighting**, **texturing**, and **post-processing**. This project demonstrates how shaders interact with the GPU pipeline to enhance visual fidelity in real-time rendering.

---

## 🎯 Purpose

To learn and demonstrate how to write and use **GLSL shaders** in an OpenGL rendering pipeline, including vertex, fragment, and post-process shaders for basic lighting and screen-space effects.

---

## 🧠 Features

- 🧱 **Vertex and Fragment Shader Setup**
- 🌄 **Basic Diffuse Lighting**
- 🖼️ **Texture Mapping**
- 💫 **Post-Processing Effects** (e.g., grayscale, inversion)
- 📐 **MVP Transformations** (Model-View-Projection)
- 📊 **Uniforms and Attributes** passed from CPU to GPU

---

## 🛠️ Technologies Used

- **C++17**
- **OpenGL 3.3+**
- **GLSL (OpenGL Shading Language)**
- **GLFW** – Window and input management
- **GLEW / GLAD** – OpenGL function loader
- **STB Image** – Image loading for textures
- **GLM** – Math library for matrices and vectors

---

## 📁 Project Structure

```plaintext
/OpenGLShaderProgram/
│
├── shaders/
│   ├── basic.vert       # Vertex shader
│   ├── basic.frag       # Fragment shader
│   ├── postprocess.frag # Post-processing shader
│
├── textures/
│   ├── brick.jpg        # Sample texture
│
├── main.cpp             # OpenGL setup and rendering logic
├── Shader.hpp/.cpp      # Shader class for loading and compiling GLSL
├── Mesh.hpp/.cpp        # Basic mesh abstraction
├── README.md
