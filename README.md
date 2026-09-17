# Actividad 4 - Juego del Tiro Parabólico (Cannon)

## Descripción

Este proyecto corresponde a la Actividad 4 de Herramientas Computacionales.

Se utilizó como base el juego Cannon de la colección Free Python Games, desarrollada por Grant Jenks.

El objetivo de la actividad fue incrementar la dificultad del videojuego y modificar su comportamiento para hacerlo más rápido e interminable.

## Modificaciones realizadas

Se realizaron las siguientes modificaciones:

1. Se incrementó la velocidad de movimiento del proyectil.
2. Se incrementó la velocidad de movimiento de los balones.
3. Los balones pueden continuar apareciendo durante el juego.
4. Los balones se reposicionan para permitir que el juego continúe.
5. El juego mantiene su funcionamiento incluso después de eliminar objetivos.

Estas modificaciones hacen que el juego sea más dinámico y aumentan progresivamente su dificultad.

## Funcionamiento

El jugador debe disparar proyectiles para intentar impactar los balones que se desplazan por la pantalla.

El movimiento del proyectil utiliza principios de tiro parabólico, considerando componentes horizontales y verticales de velocidad.

## Controles

- Clic del mouse: disparar un proyectil hacia la posición seleccionada.

## Requisitos

- Python 3
- Librería `freegames`

Instalación:

```bash
pip install freegames
