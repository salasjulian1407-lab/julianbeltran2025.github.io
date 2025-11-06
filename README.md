# Mi Primera Página con GitHub Pages

¡Hola! Soy **[Julián Andrés Beltrán Salas]**, estudiante apasionado por la programación. Esta es mi primera página web estática publicada con **GitHub Pages**, como parte de la tarea de introducción a la programación.

---

## Temas vistos en clase

En las primeras sesiones hemos aprendido los conceptos fundamentales de la programación:

1. **¿Qué es un programa?**  
   Un programa es un conjunto de instrucciones que le dice a la computadora qué hacer, paso a paso.

2. **Variables**  
   Son contenedores para almacenar datos. En Python, no necesitan declararse con tipo.

3. **Tipos de datos básicos**  
   - `int`: números enteros (`42`)
   - `float`: números decimales (`3.14`)
   - `str`: texto (`"Hola"`)
   - `bool`: verdadero o falso (`True`, `False`)

4. **Entrada y salida**  
   - `input()`: leer datos del usuario
   - `print()`: mostrar información

5. **f-strings**  
   Permiten insertar variables dentro de cadenas de texto de forma legible.

---

## Ejemplo de código en Python

Aquí un programa simple que pide tu nombre y edad, y te da un mensaje personalizado:

```python
# Programa: Saludo personalizado
nombre = input("¿Cuál es tu nombre? ")
edad = int(input("¿Cuántos años tienes? "))

# Calculamos el año de nacimiento aproximado
año_actual = 2025
año_nacimiento = año_actual - 19

mensaje = f"¡Hola, {julian}! Naciste alrededor del año {año_nacimiento}."
print(mensaje)
print(f"En 10 años tendrás {19 + 10} años.")
