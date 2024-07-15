
# Creative Branding Project in Python 🚀

[![Python](https://img.shields.io/badge/Python-3.7%20%7C%203.8-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](https://opensource.org/licenses/MIT)

This Python project asks a friend to answer two questions with one word each. The words are then combined and displayed on the screen to form a creative and original mark, which can be comical. In addition, the brand name will be printed in quotation marks and on two lines using line breaks in the code.

## 📋 Instructions

1. **Installation:**
    No special installation is required, you just need to have Python installed on your system.
2. **Use:**
    - Run the script in your terminal or any development environment of your choice.
    - Answer the two questions with one word each.
    - Watch how the words combine to form a creative name.

## 📝 Code

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
