# challenge-python-03 - Decode the message

Encuentra el texto oculto

### RETO

En el archivo **main.py** lee el string del archivo **encoded.txt**. Luego, utilizando el módulo **re** (regex) de Python encuentra el texto oculto, e imprímelo en consola.

Aclaraciones:

- No necesitas instalar nada ni crear un entorno virtual, ya que todos los módulos que puedes usar vienen en el core de Python
- Utiliza Python 3 para resolver el reto
- ¡No leas las soluciones de tus compañeros! Es importante que te retes a ti mismo y pruebes tus habilidades

### Pistas

- Abre el archivo con "encoding= 'utf-8'" para evitar errores:

```python
with open('encoded.txt', 'r', encoding='utf-8') as f:
    # code
```

- El mensaje solo está formado por letras minúsculas

### Enviar solución

Debes hacer un "Fork" de este proyecto, revolver los problemas y crear un Pull Request hacia este repositorio.

### Contribuir

Si alguien quiere agregar o mejorar algo, puede hacerlo directamente en este repositorio: [challenge-python-03](https://github.com/platzimaster/challenge-python-03/)

### Licencia

challenge-python-03 se lanza bajo la licencia [MIT](https://opensource.org/licenses/MIT).
