# SimpleChat_JGroup
Práctica de Chat Prt3 CD

Descargar la version 3 de JGroups descomprimir el .jar y agregar lo que este dentro de esa carpeta al mismo nivel que el .java del archivo SimpleChat.

> javac SimpleChat.java


> java SimpleChat -Djgroups.bind_addr=IP_MULTICAST -Djava.net.preferIPv4Stack=true


Hay que cambiar en la linea 53 del código:

	channel.connect("TALI");

"TALI" es el nombre del canal al cual se va conectar. Pueden cambiarselo pero los que se vayan a conectar al mismo canal deben tener ese nombre.
