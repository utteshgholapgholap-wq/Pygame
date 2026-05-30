# Pygame Smooth Movement Example

A lightweight, beginner-friendly Python script demonstrating smooth, continuous 2D character movement and boundary collision using the **Pygame** library.

---

## 🚀 Features

* **Continuous Keyboard Input:** Uses keyboard polling (`pygame.key.get_pressed()`) for smooth, non-stuttering 4-way movement.
* **Smart Dynamic Fallback:** If your character image asset (`character.png`) is missing, the engine automatically generates a blue square placeholder so the program never crashes.
* **Window Boundary Locks:** The player character is cleanly restricted from moving off the edges of the window.
* **Framerate Independent Feel:** Maintained at a locked 60 FPS using `pygame.time.Clock()` to prevent CPU-based speed variance.

---

## 🛠️ Requirements

* **Python 3.x**
* **Pygame** If you don't have Pygame installed yet, run the following command in your terminal/command prompt:

```bash
pip install pygame
