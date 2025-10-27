# **Git**

Es esencial para los programadores saber utilizar git 

#### **Que es git**

- Es el sistema distribuido de control de versiones mas utilizado en todo el mundo el cual permite trabajar en grupo el cual tiene un historial de todo lo que se ha hecho en el proyecto.

#### Usos
- Historial de todo el trabajo que hemos realizado el equipo en el poryecto.
- Nos permite almacenar codigo.
- Trabajar en equipo.
- Podemos saber si se introdujo el error 
  
### **Terminos**

#### Git 
- Es un sistema de control de versiones
### Repositorio: 
- Es todo proyecto que esta siendo seguido por git.
### Commit: 
- Es cada uno de los cambios registrados en el historial de git cada uno de los desarrolladores tienen que decirle a git lo que han hecho para que los demas puedan verlo.
### Ramas: 
- En git todo se trabaja por ramas donde la master es la principal cada vez que se quiera trabajar en alguna caracteristica nueva o hacer algo se puede sacar una rama secundaria la cual permite trabajar en un ambiente aislado ya que es una copia del proyecto pero separada, si algo sale mal no compromete el proyecto y si sale bien se integra esta al proyecto principal.
#### Clon:
  - Es una copia exacta del repositorio cuando hay un nuevo integrante en el proyecto este debe es clonar el repositorio en su equipo local.
#### Fork:
  -  Proyecto diferente que se crea apartir de otro, cada vez que algo sea un fork de otro es que se baso en otro proyecto.
#### Merge:
- Es cuando se una alguna rama secundaria en la cual el resultado fue exitoso debe ser integrada se hace un merge que fusiona las ramas.
  
>### **El creador**

>  -  El creador de linux tambien es el creador de git al cual inicio por que sistema de versionamiento empezo a ser de paga y este no queria pagar ya que linux es open source.

### **Integridad de datos**

Git agrega un check sum a cada uno de los archivos y commits asi hay la seguridad total de que cada uno de los desarrolladores de un proyecto tengan los mismos datos.

### Como se trabaja con git

1. Se debe crear el repositorio con (git init) si es un repositorio nuevo o (git clone) si es para un proyecto que ya existe  se debe escribir el comando y la url del proyecto y asi este se clona y se crea una copia en su equipo local.
2. Cada vez que el programador haga cambios debe hacer commits pues cada uno representa una funcionalidad especifica por ejemplo cambio en interfaz o un arreglo
> Estos cambios no van directamente al repositorio sino que hay un area de preparacion con el comando (git add) no se envian directamente al repositorio hasta estar completamente seguro de que los cambios se han realizado en todos los archivos necesarios y se utiliza para esto el comando (git-commit) ya con todos los commits hablando de lo que se realizo en cada uno.
3. Se deben tener 2 ramas una llamada master la cual es la principal y la rama dev que es la que debemos de usar los desarrolladores que no somos lideres de desarrollo del proyecto

### Herramientas

La herramienta mas importante para trabajar con git es la terminal o la linea de comandos, no se puede aprender git con una interfaz grafica ya que aunque estos son para agilizar trabajo tienen algunas limitaciones y la mayoria de desarrolladores trabajan en el terminal, no se aprendera si se utiliza desde el principio.

### Repositorios en la nube 

Cuando hay un equipo distribuido con mucha distancia se deben usar repositorios en la nube lo cual serian ramas remotas las cuales suelen ser llamadas origin Github es una empresa que da un servicio en la nube y git es la tecnologia que esta por debajo realmente no son lo mismo y no es obligatorio el guardar los repositorios en este hay mas empresas que prestan este servicio dependera de lo que deseen los desarrolladores o la empresa.

### Ides y editores

Git esta integrado en gran variedad de ides y editores de codigo por ejmeplo VS Code, Intellij Idea y atom.



