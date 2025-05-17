Prompt 1

Eres ingeniero de software y te han encargado la tarea de desplegar el backend en EC2, utilizando github actions.
Lo que tienes que hacer es:
- Pasas tests del backend.
- Generar un build del backend.
- Despliegar el backend en un EC2. 
Vamos a empezar analizando el proyecto backend para tener contexto del mismo. 
Es importante conocer las tecnologías utilizadas y los test que pueda tener para saber como ejecutarlos más adelante.
Por ahora analiza el proyecto para ver si tenemos la información suficiente para la tarea que tenemos que realizar.
A continuación seguiremos viendo que pasos tenemos que dar.

------------------------------------------------------------------------------

Prompt 2

Tu misión en este ejercicio es crear un pipeline en GitHub Actions que, tras el trigger "push a una rama con un Pull Request abierto", siga los siguientes pasos:

- Pase unos tests de backend.
- Genere un build del backend.
- Despliegue el backend en un EC2. 

Para ello, debes seguir estos pasos:

- Configurar el workflow de GitHub Actions en un archivo .github/workflows/pipeline-LBN.yml.
- Documentar los prompts utilizados para generar cada paso del pipeline:
      Tests de backend.
      Generación del build del backend.
      Despliegue del backend en EC2.

Asegúrate de que el pipeline se dispare con un push a una rama con un Pull Request abierto.

------------------------------------------------------------------------------

Prompt 3
Explícame todo lo que hace el fichero @pipeline-LBN.yml.
Quiero entenderlo bien.

------------------------------------------------------------------------------

Prompt 4

Ahora explícame donde tengo que definir las variables definidas como secrets.*

