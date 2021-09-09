#GRUPO: SC AWS 
![image.png](https://i.ibb.co/CKvw9TW/logo-aws.png)
#Metodologia.
Comenzamos nuestra arquitectura con el usuario que ingresa al CHAT CAMPUS mediante 
la web en su ordenador, este chat recibe la información mediante el API Gateway, 
componente cuya principal función es la de habilitar la conexión entre los servicios
y los clientes, trabajando en su back-end mediante Amazon S3, GitHub y Visual Studio Code.
Luego seguimos con Amazon Lex, que es un chat bot donde los usuarios (estudiantes) podrán 
realizar sus preguntas para acceder a los diferentes pabellones, ubicación (GPS) e información 
específica, el agente virtual de texto les va a ofrecer una experiencia instantánea para 
los usuarios ya que estos necesitan respuestas rápidas y precisas a cualquier hora del día y
puedan solucionar problemas o encontrar la información que estaban buscando con urgencia.
## Table Contenido.
1. [Introducción](#introduccion)
2. [Información General](#informacion general)
3. [Herramientas e Instalciones](#herramientas e instalaciones)
4. [Collaboration](#collaboration)
5. [FAQs](#faqs)
### Introducción
***
Implementar una web Responsive donde todos los alumnos puedan atraves de un chat 
comunicarse en diferentes áreas y así estar enterados de acontecimientos, eventos 
que se den en la universidad, también implementar un GPS para cada alumno y así 
poder registrarlos y ponerles asistencia utilizando un sensor que sea reconocido 
por un celular, utilizando los servicios de AWS Amazon. 


## Descripción
***
El usuario que ingresa al CHAT CAMPUS mediante la web en su ordenador, este chat recibe
la información mediante el API Gateway,componente cuya principal función es la de habilitar
la conexión entre los servicios y los clientes, trabajando en su back-end mediante Amazon S3,
GitHub y Visual Studio Code.
Luego seguimos con Amazon Lex, que es un chat bot donde los usuarios (estudiantes) podrán 
realizar sus preguntas para acceder a los diferentes pabellones, ubicación (GPS) e información 
específica, el agente virtual de texto les va a ofrecer una experiencia instantánea para 
los usuarios ya que estos necesitan respuestas rápidas y precisas a cualquier hora del día y
puedan solucionar problemas o encontrar la información que estaban buscando con urgencia.

* [Arquitectura - Miro](https://miro.com/app/board/o9J_l09mz1w=/)
* [Planner](https://tasks.office.com/usmp.pe/es-PE/Home/Planner/)
* [Azure DevOps](https://dev.azure.com/)
## Installation
***
A little intro about the installation. 
```
$ git clone https://example.com
$ cd ../path/to/the/file
$ npm install
$ npm start
```
Side information: To use the application in a special environment use ```lorem ipsum``` to start
## Collaboration
***
Give instructions on how to collaborate with your project.
> Maybe you want to write a quote in this part. 
> It should go over several rows?
> This is how you do it.
## FAQs
***
A list of frequently asked questions
1. **This is a question in bold**
Answer of the first question with _italic words_. 
2. __Second question in bold__ 
To answer this question we use an unordered list:
* First point
* Second Point
* Third point
3. **Third question in bold**
Answer of the third question with *italic words*.
4. **Fourth question in bold**
| Headline 1 in the tablehead | Headline 2 in the tablehead | Headline 3 in the tablehead |
|:--------------|:-------------:|--------------:|
| text-align left | text-align center | text-align right |