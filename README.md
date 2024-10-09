
# Space Invaders

Este proyecto es una implementación del clásico juego *Space Invaders* utilizando tecnologías web como **HTML**, **CSS**, y **Canvas**. El objetivo es recrear la experiencia del juego original con una interfaz moderna y adaptable a diferentes dispositivos.

## Descripción

En Space Invaders, el jugador controla una nave espacial que se mueve horizontalmente en la parte inferior de la pantalla. El objetivo es disparar a los invasores alienígenas que se acercan desde la parte superior antes de que lleguen al jugador. Cada invasor eliminado otorga puntos, y el juego se vuelve progresivamente más difícil a medida que avanzas en los niveles.

### Funcionalidades

- **Movimiento del jugador**: El jugador puede mover la nave hacia la izquierda y la derecha usando las teclas de flecha.
- **Disparo**: La nave puede disparar proyectiles para destruir a los invasores presionando la tecla de espacio.
- **Enemigos**: Los invasores alienígenas se mueven en formación, y su velocidad aumenta a medida que son destruidos.
- **Detección de colisiones**: El juego detecta cuando los proyectiles impactan a los invasores o cuando un invasor alcanza al jugador.
- **Puntuación**: Se mantiene un puntaje en pantalla que aumenta cada vez que un invasor es eliminado.

## Tecnologías Utilizadas

- **React + Vite**: Estructura y elementos del juego.
  
This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
- **Canvas**: Lienzo en el que se renderizan los gráficos del juego, incluyendo los invasores, la nave y los proyectiles.

## Cómo Jugar

1. **Mover la nave**: Usa las teclas de flecha izquierda y derecha para mover la nave.
2. **Disparar**: Presiona la tecla espacio para disparar a los invasores.
3. **Ganar puntos**: Elimina a los invasores para ganar puntos. El juego termina si los invasores llegan a la nave o si los destruyes a todos.

## Instalación

Para correr el juego localmente, sigue estos pasos:

1. Clona este repositorio:

   ```bash
   git clone https://github.com/JordanAyuzo/space-invaders.git
