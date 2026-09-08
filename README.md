# Pepe - El Arquero 🏹

Juego de plataformas 2D desarrollado en Unity (C#) para la asignatura de *Ingeniería de Videojuegos*. El proyecto destaca por la aplicación práctica de patrones de diseño de software para la optimización de código y arquitectura de videojuegos.

---

## Autores

* **Sara Gallego Trigal**
* **Rodrigo Hervada Llahosa**
* **Enrique Tamajón Castilla**

---

## Patrones de Diseño Implementados

* **Object Pool:** Reutilización de flechas disparadas por el personaje.
* **State:** Máquina de estados para el menú de pausa y la IA del enemigo (patrulla / persecución).
* **Observer:** Gestión de recogida de monedas, sistema de daño e interfaz de vida.
* **Component:** Desacoplamiento de las mecánicas del jugador (salto, disparo, etc.).
* **Dirty Flag:** Guardado eficiente del estado de la partida en los *checkpoints*.
* **Prototype:** Clonación de instancias de objetos (monedas, flechas y trampas).
* **Game Loop:** Gestión de físicas (`FixedUpdate`) y cámara (`LateUpdate`) en Unity.

---

## Tecnologías

* **Motor:** Unity Engine
* **Lenguaje:** C#
