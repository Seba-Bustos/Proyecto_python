# Simulación de un Edificio con Invasión Zombi

Este proyecto es una simulación en Python de un edificio donde los zombis pueden aparecer y moverse de manera aleatoria. El usuario puede avanzar los turnos y rastrear la invasión mediante sensores IoT en cada habitación.

## Características
- Representación de un edificio con múltiples pisos y habitaciones.
- Sensores en cada habitación que detectan la presencia de zombis.
- Movimiento de zombis entre habitaciones adyacentes.
- Interacción del usuario para avanzar turnos y visualizar el estado del edificio.

## Requisitos
- Python 3.7 o superior instalado en tu sistema.

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

## Arquitectura del Proyecto
La simulación se estructura en varias clases principales:

- **Building**: Representa el edificio y contiene múltiples pisos.
- **Floor**: Representa un piso dentro del edificio y administra las habitaciones.
- **Room**: Representa una habitación con la capacidad de contener zombis y un sensor IoT.
- **Sensor**: Detecta la presencia de zombis y cambia su estado entre `normal` y `alert`.
- **Simulation**: Orquesta la lógica del juego, controla el movimiento de zombis y gestiona la interacción con el usuario.

## Cómo jugar
1. Al iniciar, ingresa el número de pisos, habitaciones por piso y zombis iniciales.
2. Durante la simulación, selecciona:
   - `1` para avanzar un turno (los zombis se expanden a habitaciones adyacentes).
   - `2` para mostrar el estado actual del edificio.
   - `3` para salir de la simulación.

## Ejemplo de salida en consola
```
¿Cuántos pisos tiene el edificio? 3
¿Cuántas habitaciones por piso? 4
¿Cuántos zombis iniciales? 2

--- ESTADO DEL EDIFICIO ---
Floor 0:
  Room 0: Sensor state: normal
  Room 1: Sensor state: alert
  Room 2: Sensor state: normal
  Room 3: Sensor state: normal
...
1. Avanzar turno !!NOS INVADEN LOS ZOMBIES!!
2. Mostrar estado del edificio
3. Salir
Selecciona una opción:
```

## Licencia
Este proyecto está bajo la licencia MIT. ¡Úsalo libremente!

---

