<div align="center">

# 🌀 fractol

### Explore the beauty of fractals in C

A small interactive fractal explorer built with **C** and **MiniLibX** as part of the 42 curriculum. Choose a fractal, zoom into its details, and experiment with colors and iteration depth.

[![Language](https://img.shields.io/badge/language-C-00599C?style=for-the-badge&logo=c)](https://en.wikipedia.org/wiki/C_(programming_language))
[![School](https://img.shields.io/badge/42-Kocaeli-00BABC?style=for-the-badge)](https://42kocaeli.com.tr/)

<br>

| 🌀 Mandelbrot | ✨ Fractal detail |
|:---:|:---:|
| <img src="assets/mandelbrot-preview.png" alt="Mandelbrot fractal in vivid blue and cyan tones" width="390"> | <img src="assets/julia-fractal-detail.jpg" alt="Close-up of a fractal with deep teal and cyan details" width="390"> |

### 🎬 Watch fractol in action

<video src="assets/fractol-demo.mp4" controls width="780" poster="assets/mandelbrot-preview.png">Your browser does not support embedded video. [Watch the demo](assets/fractol-demo.mp4).</video>

[▶️ Open the demo video](assets/fractol-demo.mp4)

</div>

## ✨ Fractals to explore

- **Mandelbrot** — the classic set, rich with intricate boundaries.
- **Julia** — explore a family of shapes controlled by complex parameters.
- **Celtic Mandelbrot** — a striking variation of the Mandelbrot set.
- **Burning Ship** — a distinctive fractal with flame-like structure.

## 🚀 Build and run

> This project uses the macOS version of MiniLibX and links against AppKit and OpenGL.

```bash
make
./fractol mandelbrot
```

Choose another fractal:

```bash
./fractol julia
./fractol julia -0.6 0.6
./fractol celtic_mandelbrot
./fractol burning_ship
```

## 🎮 Controls

| Action | Control |
| --- | --- |
| Zoom in / out | Mouse wheel |
| Move around | Arrow keys |
| Change fractal | `1` Mandelbrot · `2` Julia · `3` Celtic Mandelbrot · `4` Burning Ship |
| Change color palette | `C` |
| Increase / decrease detail (iterations) | `+` / `-` |
| Reset view | `R` |
| Lock / unlock Julia mouse interaction | `Space` |
| Quit | `Esc` |

## 🧰 Makefile commands

```bash
make        # Build the program and its bundled libraries
make clean  # Remove object files
make fclean # Remove object files and the executable
make re     # Clean and rebuild
```

## 👩‍💻 About

Created by **Sedef Akkaya** as a 42 School graphics project.

- GitHub: [@sakkayaa](https://github.com/sakkayaa)
- LinkedIn: [Sedef Akkaya](https://www.linkedin.com/in/sedef-akkaya-0a5580228/)
