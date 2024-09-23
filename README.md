# Trabajo Despliege de aplicaciones web: [Github](https://github.com/)

##### Hecho por Ramon Viñuales Lazaro

## Que hay en este documento?

1. Que es Github?
2. Funciones Github
3. Pasos a seguir para conseguir diferentes acciones
4. Conclusiones
5. Bibliografia

## Que es [Github](https://github.com/)?

![imagen Github](https://i.blogs.es/bd50eb/github_logo/1024_2000.png)

[Github](https://github.com/) es una de las principales plataformas para crear proyectos, caraterizado por sus funciones colaborativas, que ayudan a que todos puedan aportar su granito de arena para mejorar el código.

 [Github](https://github.com/) utiliza un sistema de control de versiones _**GIT**_ donde los desarroyadores pueden administrar su proyecto, ordenando el código de cada una de las nuevas versiones que sacan de sus aplicaciones para evitar confusiones. 
 
 Así, al tener copias de cada una de las versiones de su aplicación, no se perderán los estados anteriores cuando se va a actualizar.
 
 Ademas el sistema permite comparar el código de un archivo para ver las diferencias entre las versiones, restaurar versiones antiguas si algo sale mal, y fusionar los cambios de distintas versiones.
 
 Tambien permite trabajar con distintas ramas de un proyecto, como la de desarrollo para meter nuevas funciones al programa o la de producción para depurar los bugs.

## Funciones [Github](https://github.com/)

 Algunas de las funciones mas inportantes para la gestion de nuestros repositorios son:

* **git add nombre_del_archivo** _(cambiando _nombre_del_archivo_ por el nombre del archivo)_ Se utiliza para agregar cambios en archivos al área de preparación "_staging area_" de Git antes de hacer un commit.
  
 * **git commit -m "Example"** _(cambiando _Example_ por el mensaje que le queramos poner al subir los nuevos cambios)_  Se utiliza para guardar los cambios realizados en el proyecto en el repositorio local Git.
   
 *  **git push origin main** _(cambiando  _main_ por la rama donde quieres subir los cambios del repositorio local y _origin_ por el nombre del repositorio remoto)_ Se utiliza para subir los _commits_ realizados en tu repositorio local al repositorio remoto.
   
 *  **git pull origin main** _(cambiando  _main_ por la rama donde quieres subir los cambios del repositorio local y _origin_ por el nombre del repositorio remoto)_ Se utiliza para actualizar tu repositorio local con los cambios que se han realizado en el repositorio remoto.
   

## Pasos a seguir para conseguir diferentes acciones

A continuación, te detallo los pasos que debes seguir para realizar las acciones más importantes en GitHub:

##### 1. Crear y gestionar repositorios
* Crea una cuenta en GitHub: Si no tienes una, regístrate en github.com.
* Crea un nuevo repositorio:
  * Inicia sesión y haz clic en el botón "New" en la página de inicio.
  * Introduce el nombre del repositorio, agrega una descripción (opcional) y decide si será público o privado.
  * Selecciona opcionalmente si deseas agregar un archivo README, un archivo .gitignore o una licencia.
  * Haz clic en "Create repository".
  
##### 2. Control de versiones y gestión de commits
* Clona el repositorio:
  * Copia la URL del repositorio y, en la terminal, escribe: _git clone URL_DEL_REPOSITORIO_.
* Realiza cambios y haz commits:
  * Agrega o modifica los archivos necesarios.
  * Utiliza _git add ._ para agregar los cambios al área de preparación.
  * Haz un commit con git commit -m "Mensaje del commit".
* Envía los cambios al repositorio remoto:
  * Utiliza git push origin nombre_de_la_rama para enviar los cambios a GitHub.
    
##### 3. Colaborar mediante pull requests
* Haz un fork del repositorio: Si deseas contribuir a un proyecto que no es tuyo, haz clic en "Fork" en la página del repositorio.
* Clona el repositorio forkeado y crea una nueva rama:
  * _git checkout -b nombre_de_tu_rama_
* Realiza los cambios y súbelos a tu repositorio forkeado.
* Crea un pull request:
  * En la página de tu repositorio, haz clic en "Compare & pull request".
  * Describe los cambios que has realizado y haz clic en "Create pull request".

##### 4. Gestionar issues y proyectos
* Crear un issue:
  * En la página del repositorio, haz clic en la pestaña "Issues" y luego en "New issue".
  * Introduce un título y una descripción detallada del problema o sugerencia.
  * Asigna etiquetas, personas y hitos, si es necesario.
* Gestionar proyectos:
  * Haz clic en la pestaña "Projects" y luego en "New project".
  * Selecciona un tipo de tablero (kanban o personalizado) y organiza las tareas mediante tarjetas que representan issues, pull requests u otras tareas.
 
    
##### 5. Automatizar tareas con GitHub Actions
* Configura GitHub Actions:
  * En la página del repositorio, haz clic en la pestaña "Actions".
  * Selecciona un flujo de trabajo predefinido o crea uno nuevo mediante la creación de un archivo .yml.
* Personaliza el archivo de workflow:
  * Edita el archivo _.github/workflows/nombre_del_archivo.yml_ para definir las tareas que se ejecutarán de forma automática, como ejecutar pruebas, compilar el proyecto o desplegarlo.
* Sube el archivo y GitHub Actions se ejecutará automáticamente según las condiciones definidas en el workflow.
Siguiendo estos pasos, podrás aprovechar al máximo todas las funcionalidades y acciones importantes de GitHub para gestionar y colaborar en tus proyectos de programación.

## Conclusiones

GitHub es una plataforma que permite almacenar, gestionar y colaborar en proyectos de programación utilizando el sistema de control de versiones Git. Facilita el trabajo en equipo, el seguimiento de cambios y la automatización de tareas en proyectos de software.

## Bibliografia
* [Xataka](https://www.xataka.com/basics/que-github-que-que-le-ofrece-a-desarrolladores)
* [Github](https://docs.github.com/es/get-started/start-your-journey/about-github-and-git)
* [Hostinger](https://www.hostinger.es/tutoriales/que-es-github)
* [Chat GPT](https://openai.com/chatgpt/)
 
