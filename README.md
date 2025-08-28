# 🎮 Joló Nait

> Mini-demo 2D para aprender Godot

Un proyecto sencillo desarrollado con Godot 4.x para aprender los conceptos básicos del motor. Inspirado visualmente en Hollow Knight, este demo se centra en implementar mecánicas fundamentales de juego 2D.

## 🎯 Sobre el Juego

Un pequeño demo de una única escena donde controlas un personaje que debe esquivar enemigos que se mueven aleatoriamente. El proyecto se enfoca en implementar:

- Movimiento básico del personaje
- Colisiones simples
- Animaciones elementales
- Sistema de puntuación con HUD

> Proyecto creado con fines educativos. No afiliado a Team Cherry.

## ✨ Características

- **Jugabilidad**
  - Movimiento en cuatro direcciones (←↑↓→)
  - Enemigos con movimiento aleatorio
  - Sistema de colisiones simple
- **Visuales**
  - Animación básica de movimiento
  - Animación de muerte
  - Fondo estático
- **Audio**
  - Efecto de sonido al perder
  - Música de fondo

## 🕹️ Controles

| Acción | Tecla        |
| ------ | ------------ |
| Mover  | Flechas ←↑↓→ |
| Pausa  | Esc          |

## 🗂️ Estructura del Proyecto

```
├── art/
│   ├── walk-*.png       # Animaciones de movimiento
│   ├── death-*.png      # Animaciones de muerte
│   ├── back-*.png       # Fondos del juego
│   └── *.wav           # Efectos de sonido
├── fonts/
│   └── Xolonium-Regular.ttf
├── scenes/
│   ├── main.tscn       # Escena principal
│   ├── player.tscn     # Jugador
│   ├── mob.tscn        # Enemigos
│   └── hud.tscn        # Interfaz
└── scripts/
    ├── main.gd
    ├── player.gd
    ├── mob.gd
    └── hud.gd
```

🛣️ Roadmap / TODO

## 🎮 ¿Quieres hacer tu versión?

¡Me encantaría ver tus mejoras! Aquí algunas ideas de cómo puedes participar:

1. Haz un fork del repositorio
2. Implementa tus propias mejoras (¡sé creativo!)
   - Añade nuevos enemigos
   - Implementa power-ups
   - Mejora las animaciones
   - ¡Lo que se te ocurra!
3. ¡Etiquétame en redes o abre un issue para mostrarme tu versión!

> Usa este proyecto como punto de partida para aprender y experimentar con Godot

## 🙏 Créditos

- **Motor**: Hecho con [Godot Engine](https://godotengine.org) ❤️
- **Fuente**: [Xolonium Regular](https://fontlibrary.org/en/font/xolonium)
- **Arte y Audio**: Creados para el proyecto
  - [Sprites de personaje y enemigos](https://drive.google.com/drive/folders/1lx02_w9TFTYdR3aggI1gbXcLr69roaNV)
  - [Efectos de sonido y música de ambiente](https://www.youtube.com/watch?v=0HbnqjGirFg&t=953s&ab_channel=MindsAblaze2)
  - Fondos y elementos visuales

📜 Licencia

Código: MIT (o la que prefieras).

Este proyecto es una parodia con fines educativos. Hollow Knight es propiedad de Team Cherry.

📣 Comunidad

Comparte feedback, bugs o ideas en los issues del repo. Si haces un fork/jam con Joló Nait!, ¡etiquétame para verlo! 💬
