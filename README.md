# Proyecto OpenGL – Escena 3D Interactiva

Este proyecto consiste en la creación de una **escena 3D** desarrollada con **Learning OpenGL**, integrando múltiples librerías y técnicas avanzadas para renderizado en tiempo real. El objetivo fue aprender y aplicar los fundamentos del pipeline gráfico moderno, desde la carga de modelos hasta la implementación de texturas y luces dinámicas.

---

LINK DE DESCARGA DRIVE: https://drive.google.com/drive/folders/14Y-eEVP03dRgulf46stDNilf02SL0i-B?usp=sharing

---

## 🚀 Características principales

* **Skybox**: implementación de un entorno cúbico que envuelve la escena con texturas para simular un ambiente realista.
* **Carga de modelos complejos**: se utilizó **Assimp** para importar modelos con múltiples vértices y mallas.
* **Iluminación avanzada**:

  * Luz direccional.
  * Focos tipo *flashlight* controlados por la cámara.
  * Puntos de luz distribuidos en la escena.
* **Texturas múltiples**:

  * **Diffuse map** para el color base.
  * **Specular map** para reflejos.
  * **Emissive map** para simular objetos que emiten luz.
* **Reproducción de audio 3D** con **irrKlang**, sincronizando sonidos con eventos en la escena.

---

## 🛠️ Librerías y herramientas utilizadas

1. **GLFW** – Manejo de ventanas, inputs y contexto de OpenGL.
2. **GLAD** – Cargador de funciones de OpenGL moderno.
3. **GLM** – Librería matemática para transformaciones (vectores, matrices, proyecciones, etc.).
4. **Assimp** – Importación de modelos en diferentes formatos (OBJ, FBX, etc.).
5. **stb\_image** – Carga de texturas en múltiples formatos (JPG, PNG, etc.).
6. **irrKlang** – Motor de audio para efectos de sonido y música de fondo.
7. **KHR (Khronos Group extensions)** – Soporte de extensiones gráficas y estandarización de OpenGL.

---

## 🎮 Controles

* `W, A, S, D` → Movimiento de la cámara.
* `Mouse` → Rotación de la cámara.
* `X` y `C` → Activar/desactivar la linterna (spotlight).
* `ESC` → Salir del programa.

---

## 🔊 Audio

Con **irrKlang** se integró sonido 3D:

* Música ambiental de fondo.
* Sonidos de la linterna.

---

## 📦 Compilación e instalación

### Dependencias

* OpenGL 3.3+
* Compilador C++17

---

## 📸 Resultados

La escena final incluye:

* Un **skybox inmersivo**.
* Modelos complejos con texturas realistas.
* Sistema de luces dinámicas que reaccionan al movimiento.
* Sonido ambiental sincronizado con la experiencia visual.

---

## 📚 Referencias

* [LearnOpenGL](https://learnopengl.com/)
* [GLFW](https://www.glfw.org/)
* [GLM](https://github.com/g-truc/glm)
* [Assimp](https://github.com/assimp/assimp)
* [stb\_image](https://github.com/nothings/stb)
* [irrKlang](http://www.ambiera.com/irrklang/)
* [KHRonos Group](https://www.khronos.org/opengl/)

---

¿Quieres que te prepare este README también en **inglés técnico**, como se suele usar en GitHub, o prefieres dejarlo solo en español?



