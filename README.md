#Docker Kubernetes notes

Notas de cursos y prácticas con Docker y Kubernetes.


### Arquitectura global de Docker

El <code><b>Docker Host</b></code> se encuentra alojado en la máquina donde se instaló Docker. Las capas del Docker Host son los siguientes:
<b>
    - Docker CLI - Client.
    - REST API.
    - Docker Daemon - Server.
</b>

Haciendo uso del Cliente podemos administrar los <code><b>Contenedores</b></code>, <code><b>imágenes</b></code>, <code><b>Volúmenes</b></code>, <code><b>Redes</b></code> y más.

<br>

#### Imágenes

<i>¿Qué es una imágen?</i>
Una imágen se puede entender como un paquete. Contiene toda la <b>configuración necesaria</b> para que funcione un servicio.

<br>

Las imágenes tienen capas.

1. La primera capa suele ser la capa <b>FROM</b>. Esta capa hace referencia al sistema operativo. 

2. En la siguiente capa se encuentra la capa <b>RUN</b>. indica qué se va a hacer después de tener el sistema operativo. 

3. La tercera capa es la <b>CMD</b>. Comando que suele activar o inicializar el servicio instalado.

Estas capas se definen en el <code><b>Dockerfile</b></code>.

Ejemplo de achivo dockerfile:
<img src="images/001 - dockerfile example.png">


<br>


#### Contenedores

Un contenedor se puede entender como una capa adicial de Ejecución. 








#### DevOps

Devops = Development + Operation.
Personas + Procesos + Tecnología.

<img src="images/002 - Devops.webp" style="border: 1px solid black; border-radius:5px">