# Tamagochi Pokémon

Este es un programa en **Java** que simula un **Tamagochi Pokémon**, permitiendo al usuario interactuar con su Pokémon a través de un menú de opciones.

## 🛠 Características
- El usuario puede **nombrar** a su Pokémon.
- Se pueden realizar varias acciones:
  - **Entrenar**: Aumenta la felicidad pero reduce la energía.
  - **Comer**: Recupera energía.
  - **Descansar**: Recupera toda la energía.
  - **Jugar**: Aumenta la felicidad.
  - **Recibir daño**: Reduce la vida del Pokémon.
- El estado del Pokémon se actualiza y se muestra en cada turno.
- Si la **vida llega a 0**, el juego termina.

## 📂 Estructura del Proyecto
```
📦 tamagochi
 ┣ 📜 Main.java       // Clase principal que ejecuta el juego
 ┣ 📜 Tamagochi.java  // Clase que modela al Pokémon Tamagochi
 ┗ 📜 README.md       // Documentación del proyecto
```

## 🚀 Instalación y Ejecución
1. **Clona este repositorio** en tu máquina local:
   ```sh
   git clone https://github.com/tu-usuario/tamagochi-pokemon.git
   ```
2. **Compila el código** en la terminal:
   ```sh
   javac tamagochi/*.java
   ```
3. **Ejecuta el juego**:
   ```sh
   java tamagochi.Main
   ```

## 🎮 Cómo Jugar
1. Introduce el nombre de tu Pokémon.
2. Selecciona una acción del menú ingresando el número correspondiente.
3. Administra la energía, felicidad y vida de tu Pokémon.
4. El juego termina si decides salir o si la vida del Pokémon llega a 0.

## 📌 Mejoras Futuras
- Implementar **niveles de experiencia** y evolución.
- Agregar más tipos de interacciones (como batallas entre Pokémon).
- Guardar el estado del Pokémon para continuar en futuras partidas.

## 🤝 Contribución
Si deseas mejorar este proyecto, ¡las contribuciones son bienvenidas! Haz un **fork**, crea una nueva rama y envía un **pull request**. 😊

## 📜 Licencia
Este proyecto se distribuye bajo la licencia **MIT**.
