# Flappy Bird (Demo en Unity)

Demo de **Flappy Bird** hecho con **Unity y C#** para aprender las mecánicas principales del desarrollo de videojuegos: física, entrada del jugador, colisiones, generación de objetos y puntaje.

> Proyecto de aprendizaje · Estado: Demo ⚒️

🔗 **[Jugar en vivo](https://damianenriquez680.github.io/flappy_bird_unity/)**

---

## Descripción

El proyecto sigue un tutorial de Flappy Bird y sirve como introducción práctica a Unity. El objetivo no es el juego en sí, sino entender cómo se construye uno: cómo se mueve un personaje con físicas, cómo se detectan colisiones y cómo se conectan los scripts con los objetos de la escena.

Todo el arte (pájaro, cola, nube y tubo) lo dibujé yo en Photoshop, con un estilo propio.

---

## Controles

| Acción | Tecla |
|--------|-------|
| Saltar / aletear | `Barra espaciadora` |

---

## Mecánicas que practica

- **Físicas 2D:** movimiento del pájaro con `Rigidbody2D` y gravedad.
- **Entrada del jugador:** lectura de la barra espaciadora desde un script en C#.
- **Colisiones:** detección de choques con los tubos.
- **Generación de objetos:** aparición de tubos durante la partida.
- **Interfaz (UI):** texto en pantalla con el puntaje.
- **Scripts en componentes:** conexión de scripts con objetos de la escena desde el Inspector.

---

## Cómo jugarlo

Directamente en el navegador con el enlace de arriba, o abriendo el proyecto en Unity:

```bash
git clone https://github.com/damianenriquez680/flappy_bird_unity.git
```

Abre la carpeta desde **Unity Hub** y carga la escena principal.

---

## Arte

Sprites hechos en Photoshop con formas vectoriales:

- `birdbody`: cuerpo del pájaro
- `birdwingup` / `birdwingdown`: las dos posiciones de la cola
- `cloud`: nube del fondo
- `pipe`: tubo (el de arriba es el mismo sprite volteado)

---

## Tecnologías

- Unity
- C#
- Photoshop (arte)

---

## Autor

**Damian Enriquez** — [github.com/damianenriquez680](https://github.com/damianenriquez680)
