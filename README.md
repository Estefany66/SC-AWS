#Introducción:
Implementar una web Responsive donde todos los alumnos puedan atraves de un chat 
comunicarse en diferentes áreas y así estar enterados de acontecimientos, eventos 
que se den en la universidad, también implementar un GPS para cada alumno y así 
poder registrarlos y ponerles asistencia utilizando un sensor que sea reconocido 
por un celular, utilizando los servicios de AWS Amazon.
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
