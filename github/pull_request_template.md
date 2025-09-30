Configuración de Proyectos de Software con Git y GitHub
Clase 37 de 42 • Curso de Git y GitHub

git add.git commit y el mensaje que diga
nueva plantilla. Con este mensaje, si escribiera bien

Play

Regresa 15 segundos

Adelanta 15 segundos
Current Time 
1:59
/
Duration 
10:39

Mute
1x
Playback Rate

Subtitles

Picture-in-Picture

Fullscreen
¿Dudas? Obtén respuesta inmediata


Recursos

Comentarios

Clases
Comentarios


Escribe tu comentario o pregunta

Más votados
Nuevos
Favoritos
Samuel Soto Hoyos
Samuel Soto Hoyos

student
•
hace 10 meses
•
editado

### Descripción del cambio
Por favor, proporciona una descripción detallada de los cambios realizados en este PR.

### ¿Cuál es el contexto de este cambio?
Explica el contexto y por qué se necesita este cambio.

### ¿Cómo se probaron estos cambios?
Describe los pasos que tomaste para probar que los cambios funcionan como se espera.

### ¿Existen tickets relacionados?
Víncula cualquier ticket o issue relacionado con este PR.

### Captura de pantalla (si aplica)
Si los cammbios afectan a la interfaz de usuario, por favor adjunta capturas de pantalla.

### Checklist
- [ ] He seguido las convenciones de estilo de código de este repositorio.
- [ ] He añadido pruebas unitarias para los cmabios que lo requieren.
- [ ] Todos los tests pasan correctamente.
- [ ] He documentado adecuadamente los cambios en el código.

### Otros comentarios
Agrega cualquier otra información relevante aquí.

48

Responder

Reportar
Alexis Dorado Muñoz
Alexis Dorado Muñoz

student
•
hace 7 meses
Gracias por tu aporte


1
Jean Grober
Jean Grober

student
•
hace 17 horas
Genial! Gracias


1
Sara María Mejia Sánchez
Sara María Mejia Sánchez

student
•
hace 8 meses
Hola

Les comparto el markdown de pull_request_template.md, el cual obtuve usando ChatGPT


### **Descripción del Cambio**  
Por favor, proporciona una descripción detallada de los cambios realizados en este PR.

### **¿Cuál es el contexto de este cambio?**  
Explica el contexto y por qué se necesita este cambio.

### **¿Cómo se probaron estos cambios?**  
Describe los pasos que tomaste para probar que los cambios funcionan como se espera.

### **¿Existen tickets relacionados?**  
Vincula cualquier ticket o issue relacionado con este PR.

### **Capturas de Pantalla (si aplica)**  
Si los cambios afectan a la interfaz de usuario, por favor adjunta capturas de pantalla.

### **Checklist**  
- [ ] He seguido las convenciones de estilo de código de este repositorio.  
- [ ] He añadido pruebas unitarias para los cambios que lo requieren.  
- [ ] Todos los tests pasan correctamente.  
- [ ] He documentado adecuadamente los cambios en el código.

### **Otros Comentarios**  
Agrega cualquier otra información relevante aquí.

9

Responder

Reportar
Alexis Dorado Muñoz
Alexis Dorado Muñoz

student
•
hace 7 meses
Gracias por tu aporte


1
Abraham Siso
Abraham Siso

student
•
hace 7 meses
Hola tengo un error que no me deja avanzar y no se como solucionarlo```js pip3 install -r requirements.txt error: externally-managed-environment

× This environment is externally managed ╰─> To install Python packages system-wide, try apt install python3-xyz, where xyz is the package you are trying to install.


If you wish to install a non-Debian-packaged Python package,
create a virtual environment using python3 -m venv path/to/venv.
Then use path/to/venv/bin/python and path/to/venv/bin/pip. Make
sure you have python3-full installed.

If you wish to install a non-Debian packaged Python application,
it may be easiest to use pipx install xyz, which will manage a
virtual environment for you. Make sure you have pipx installed.

See /usr/share/doc/python3.12/README.venv for more information.
note: If you believe this is a mistake, please contact your Python installation or OS distribution provider. You can override this, at the risk of breaking your Python installation or OS, by passing --break-system-packages. hint: See PEP 668 for the detailed specification. ````pip3 install -r requirements.txt`

error: externally-managed-environment

× This environment is externally managed

╰─> To install Python packages system-wide, try apt install

    python3-xyz, where xyz is the package you are trying to

    install.

    

    If you wish to install a non-Debian-packaged Python package,

    create a virtual environment using python3 -m venv path/to/venv.

    Then use path/to/venv/bin/python and path/to/venv/bin/pip. Make

    sure you have python3-full installed.

    

    If you wish to install a non-Debian packaged Python application,

    it may be easiest to use pipx install xyz, which will manage a

    virtual environment for you. Make sure you have pipx installed.

    

    See /usr/share/doc/python3.12/README.venv for more information.

note: If you believe this is a mistake, please contact your Python installation or OS distribution provider. You can override this, at the risk of breaking your Python installation or OS, by passing --break-system-packages.

hint: See PEP 668 for the detailed specification.


5

Responder

Reportar
Diego Fernando Enriquez Bernal
Diego Fernando Enriquez Bernal

student
•
hace 7 meses
Hola, pudiste solucionarlo?

Tengo el mismo error


4
Diego Felipe Sánchez Gómez
Diego Felipe Sánchez Gómez

student
•
hace 6 meses
Es necesario crear un entorno virtual de python

primero se debe instalar el paquete para realizar entornos virtuales en python:

sudo apt install python3.12-venv

Una vez instalado, el paquete se crea un entorno virtual de python donde instalaremos los paquetes específicos del cada proyecto, para el caso del ejemplo requirements.txt

python3 -m venv .venv

Luego se activa el entorno virtual source .venv/bin/activate

y por último en el entorno virtual creado se instalan los paquetes requeridos python3 -m pip install -r requirements.txt


9

Ver una respuesta más
Diego Andrés Lopez Rodriguez
Diego Andrés Lopez Rodriguez

student
•
hace un año
Y recuerden amigos... siempre trabajen con su propia rama 😉


5

Responder

Reportar
Andres David Caicedo Marquez
Andres David Caicedo Marquez

student
•
hace 7 meses
Estoy repitiendo el curso, pero Fredy tenia una clase de Alias, muy buenas para acortar comandos, no se si lo han visto muy innecesario y no querian hacer el curso muy largo, pero siento que es importante.

Si un comando de Git es muy largo y lo usas frecuentemente, puedes crear un alias para acortarlo.

🔹 1. Crear un alias en Git

Ejecuta este comando para definir un alias en la configuración global de Git:

------------------------------------------------------------------------------------------------------

sh

Copiar

Editar

git config --global alias.shortcut 'comando-largo'

Ejemplo:

Si siempre usas

------------------------------------------------------------------------------------------------------

sh

Copiar

Editar

git log --oneline --graph --decorate --all

Puedes crear un alias más corto:

------------------------------------------------------------------------------------------------------

sh

Copiar

Editar

git config --global alias.lg "log --oneline --graph --decorate --all"

Y luego ejecutarlo simplemente con:

------------------------------------------------------------------------------------------------------

sh

Copiar

Editar

git lg

------------------------------------------------------------------------------------------------------


3

Responder

Reportar
Yeider Estiben Gonzalez Ramirez
Yeider Estiben Gonzalez Ramirez

student
•
hace 3 meses
Hola estaba intentando ejecutar este código me daba error uvicorn app:app --reload

Intenten este código a mi me funciono

python3 -m uvicorn app:app --reload


2

Responder

Reportar
Rodrigo Rios Contreras
Rodrigo Rios Contreras

student
•
hace 8 días
Por si no tienen instalado python sudo apt install python3-pip


2

Responder

Reportar
SANTIAGO ALBERTO BOLIVAR CARDENAS.
SANTIAGO ALBERTO BOLIVAR CARDENAS.

student
•
hace un mes
Que buen video, Gracias Profesor, Gracias Platzi.


2

Responder

Reportar
David Agudelo
David Agudelo

student
•
hace 6 meses
No pude desde la terminal (uso Bash y PowerShell), pero si pude desde la terminal de VsCode.

Con tan solo 3 simples pasos:

"Ejecutar archivo de python en terminal"
desde la terminal de VsCode fui a la carpeta de API
cd API
uvicorn app:app --reload



2

Responder

Reportar
Jean Grober
Jean Grober

student
•
hace 17 horas
Para aquellos que les dio error al ejecutar el comando python les recomiendo descargar desde su pagina oficial python agregar su extensión en Visual studio code y cuando nuevamente pongan el comando les pedirá crear un entorno especial para python ahi simplemente yo elegí crear un entorno global Python y lo solucione.


1

Responder

Reportar
Ronaldo Jiménez
Ronaldo Jiménez

student
•
hace un mes


from fastapi import FastAPI

app = FastAPI()

@app.get("/teams")
def read_teams():
    return {"teams": ["Real Madrid", "Barcelona", "Liverpool"]}

@app.get("/players")
def read_players():
    return {"players": ["Ronaldo", "Falcao", "Messi"]}

1

Responder

Reportar
Ronaldo Jiménez
Ronaldo Jiménez

student
•
hace un mes
Actualización desde fastapi 0.111.0, se instala con:

pip install fastapi[standard]

Y para correr el proyecto se ahce con el comando: fastapi dev app.py (nombre del fichero)


1

Responder

Reportar
Ronaldo Jiménez
Ronaldo Jiménez

student
•
hace un mes
https://fastapi.tiangolo.com/


1
Oscar Hincapié
Oscar Hincapié

student
•
hace 3 meses
El comienzo se entiende, ya me pierdo cuando hace lo de los archivos no entiendo el resto


1

Responder

Reportar
Brian Blanco
Brian Blanco

student
•
hace 6 meses
tuve problemas al querer correr el servidor con uvicorn, lo solucione actualizando la version de pip y creando un entorno virtual para este proyecto.


1

Responder

Reportar
Jose Luis Bedoya
Jose Luis Bedoya

student
•
hace un año
muy util! no Sabía que se podía crear plantillas para prss


1

Responder

Reportar
Manuel Alejandro Arteaga Ontiveros
Manuel Alejandro Arteaga Ontiveros

student
•
hace un año
Una disculpa. Pero no me aparece el texto en los recursos de la clase ):


1

Responder

Reportar
Jose Luis Bedoya
Jose Luis Bedoya

student
•
hace un año
no hay texto en esta clase!


1
Yorgen Omar Marciales Parada
Yorgen Omar Marciales Parada

student
•
hace un año
El pull request es fundamental en el desarrollo colaborativo porque permite revisar, discutir y aprobar cambios antes de integrarlos al código principal. Fomenta la comunicación entre los miembros del equipo y ayuda a evitar conflictos en el código, asegurando que las contribuciones sean de alta calidad. Además, facilita la documentación de cambios y la trazabilidad del proyecto en GitHub.


1

Responder

Reportar

### **Descripción del Cambio**  
Por favor, proporciona una descripción detallada de los cambios realizados en este PR.

### **¿Cuál es el contexto de este cambio?**  
Explica el contexto y por qué se necesita este cambio.

### **¿Cómo se probaron estos cambios?**  
Describe los pasos que tomaste para probar que los cambios funcionan como se espera.

### **¿Existen tickets relacionados?**  
Vincula cualquier ticket o issue relacionado con este PR.

### **Capturas de Pantalla (si aplica)**  
Si los cambios afectan a la interfaz de usuario, por favor adjunta capturas de pantalla.

### **Checklist**  
- [ ] He seguido las convenciones de estilo de código de este repositorio.  
- [ ] He añadido pruebas unitarias para los cambios que lo requieren.  
- [ ] Todos los tests pasan correctamente.  
- [ ] He documentado adecuadamente los cambios en el código.

### **Otros Comentarios**  
Agrega cualquier otra información relevante aquí.