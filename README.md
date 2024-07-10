# Proyecto de Marca Creativa en Python 🚀

Este proyecto en Python le pide a un amigo que responda dos preguntas con una sola palabra cada una. Luego, las palabras se combinan y se muestran en la pantalla para formar una marca creativa y original, que puede resultar cómica. Además, el nombre de la marca se imprimirá entre comillas y en dos líneas utilizando saltos de línea en el código.

## 📋 Instrucciones

1. **Instalación:**
    No se requiere instalación especial, solo necesitas tener Python instalado en tu sistema.

2. **Uso:**
    - Ejecuta el script en tu terminal o cualquier entorno de desarrollo que prefieras.
    - Responde las dos preguntas con una sola palabra cada una.
    - Observa cómo las palabras se combinan para formar un nombre creativo.

## 📝 Código

```python
# Código para crear una marca creativa
def crear_marca_creativa():
    print("Responde a las siguientes preguntas con una sola palabra cada una:")
    palabra1 = input("¿Cuál es tu animal favorito? ")
    palabra2 = input("¿Cuál es tu color favorito? ")
    
    marca_creativa = palabra1 + palabra2
    print(f'La nueva marca creativa es:\n"{marca_creativa}"')

if __name__ == "__main__":
    crear_marca_creativa()
