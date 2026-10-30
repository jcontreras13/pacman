# Pacman

Version del clasico Pacman hecha con Python y turtle, basada en el juego Pacman de freegames de Grant Jenks. Proyecto de la materia TC1005S Herramientas computacionales: el arte de la programacion, Tec de Monterrey.

## Requisitos

- Python 3
- tkinter (en Debian o Ubuntu: sudo apt-get install python3-tk)
- freegames

## Instalacion

    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt

## Como jugar

    python3 pacman.py

Pacman se mueve con las flechas del teclado. El objetivo es comer todos los puntos sin que te alcance un fantasma. El marcador aparece arriba a la derecha.

## Cambios realizados

- Se diseno un tablero nuevo, con todos los pasillos conectados y sin callejones sin salida.
- Los fantasmas son mas rapidos que en el juego original.
- Los fantasmas son mas listos: en cada paso eligen la direccion que mas los acerca a Pacman.
- Se ajusto la velocidad de Pacman para que el juego siga siendo ganable.

## Autores

- jcontreras13
- Dilosch03
