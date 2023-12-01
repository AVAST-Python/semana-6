

# Introducción a Python

## Semana 6
<!-- .element style="text-align:center" -->

![alt text](./img/logo2.png) <!-- .element style="margin-left: auto; margin-right: auto; display: block" -->

---

# Nueva forma de trabajo


- ¿Cuánto queréis dedicarle?
- Diferentes "grupos":
    1) Nivel básico
    2) Nivel avanzado
    3) Temas concretos

---

# Temas comunes
- IDE
- Trabajo con repositorios
- Entornos virtuales y módulos

---

# Instalación de Visual Studio Code

![Logo Visual Studio Code](./img/vscode_logo.png) <!-- .element class="noborder center" -->

Sigue las instrucciones de tu sistema operativo:


[https://code.visualstudio.com/download](https://code.visualstudio.com/download)


---

# Manejo básico

- Abrir carpetas
- Fijar ficheros
- Ejecutar cosas
  - Terminal
  - Depuración

---

# Introducción a git

---

# Control de versiones

Qué es un repositorio de código:
- Sirve para guardar el código
- Guarda un histórico de todas las modificaciones
- Puedes modificar el código en paralelo ("ramas")
- Se puede poner online y crear un nuevo repositorio

---

# Primeros pasos con git

- Instalación de git
- Configuración de git
```bash
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
git config --global push.default simple
```
- Inicialización de repositorio:
```bash
git init
```

---

# Las áreas de trabajo

![Areas locales git](./img/git_areas_local.webp) <!-- .element class="noborder center" -->

- Areas working, staging, repository
- Movimiento simple entre áreas:
  - `git add`
  - `git commit`
  - `git checkout`
- Ver el estado:
  - `git status`
  - `git log`



---

Actividad: Crear un nuevo repositorio local





















---

# Enlaces:


- Tortuga: [https://pythonandturtle.com/turtle](https://pythonandturtle.com/turtle)
- Repl: [https://www.pythonmorsels.com/repl/](https://www.pythonmorsels.com/repl/)
- Presentaciones de las semanas anteriores:
  - [https://avast-python.github.io/semana-1](https://avast-python.github.io/semana-1)
  - [https://avast-python.github.io/semana-2](https://avast-python.github.io/semana-2)
  - [https://avast-python.github.io/semana-3](https://avast-python.github.io/semana-3)
  - [https://avast-python.github.io/semana-4](https://avast-python.github.io/semana-4)


---

# Funciones

```python
# Definición de función
def saludar(nombre):
    print('¡Hola, '+ nombre + '!')

```
<!-- .element style="font-size: 0.8em" -->

```python
# Llamada a función
saludar('Pepe')
saludar('Juan')

# Esto no haría lo que esperas:
saludar
```
<!-- .element style="font-size: 0.8em" -->

- Una función es un nombre para un conjunto de instrucciones
- Hay que definirlas primero
- Se le pueden pasar parámetros
- Podemos utilizarlas todas las veces que queramos
- Sirven para dos cosas:
  - Reutilizar código
  - Hacer el programa más claro

---

# Ejemplo

![Ejemplo 1](./img/ejemplo_s5_1.png) <!-- .element class="noborder center" -->

---

# Ejercicio 1

![Ejercicio 61](./img/ejercicio_s5_1.png) <!-- .element class="noborder center" -->

¿Qué cosas podríamos definir como funciones en cada dibujo?

---

# Ejercicio 3

![Ejercicio 62](./img/ejercicio_s5_2.png) <!-- .element class="noborder center" -->

¿Qué cosas podríamos definir como funciones en cada dibujo?
¿Qué parámetros necesitan?

