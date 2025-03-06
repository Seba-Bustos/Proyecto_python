# Simulación de un Edificio con Invasión Zombi

Este proyecto es una simulación en Python de un edificio donde los zombis pueden aparecer y moverse de manera aleatoria. El usuario puede avanzar los turnos y agregar más zombis a la simulación.

## Características
- Representación de un edificio con múltiples pisos y habitaciones.
- Sensores en cada habitación que detectan la presencia de zombis.
- Movimiento aleatorio de zombis entre habitaciones y pisos.
- Interacción del usuario para avanzar turnos.

## Requisitos
- Python 3.x instalado en tu sistema.

## Instalación y Ejecución
1. Clona este repositorio o descarga el archivo `simulation.py`:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   cd tu-repositorio
   ```
2. Ejecuta el script en tu terminal o consola:
   ```bash
   python simulation.py
   ```
3. Sigue las instrucciones en pantalla para interactuar con la simulación.

## Cómo jugar
1. Al iniciar, ingresa el número de pisos, habitaciones por piso y zombis iniciales.
2. Durante la simulación, elige:
   - `y` para avanzar un turno (los zombis se moverán aleatoriamente).
   - `n` para terminar la simulación.
     
## Ejemplo de salida en consola
```
¿Cuántos pisos tiene el edificio? 3
¿Cuántas habitaciones por piso? 4
¿Cuántos zombis iniciales? 2

Estado actual del edificio:
Floor 0:
  Room 0: Sensor state: normal
  Room 1: Sensor state: alert
  Room 2: Sensor state: normal
  Room 3: Sensor state: normal
...
¿Avanzar turno? (y/n/agregar zombies):
```
## Licencia
Este proyecto está bajo la licencia MIT. ¡Úsalo libremente!

---


