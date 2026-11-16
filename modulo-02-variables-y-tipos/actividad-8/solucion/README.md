# Depuración del programa

## 1. Paréntesis de print

- **Qué esperaba**. Ver el nombre del robot.
- **Qué pasó**. Python dio un SyntaxError.
- **Por qué**. En Python 3, print necesita paréntesis.

## 2. Nombre de la variable

- **Qué esperaba**. Ver la distancia 45.
- **Qué pasó**. Python dio un NameError.
- **Por qué**. El nombre usado en print no coincide con el de la variable declarada.

## 3. Texto y booleano

- **Qué esperaba**. Ver el estado Encendido: True.
- **Qué pasó**. Python dio un TypeError.
- **Por qué**. El operador + no concatena un texto y un booleano.
