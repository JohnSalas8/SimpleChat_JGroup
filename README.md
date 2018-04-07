# SimpleChat_JGroup
Práctica de Chat Prt3 CD

##1. Descargar el archivo SimpleChat_JGroup y descomprimirlo

##2. Entrar a SimpleChat_JGroup y descomprimir el .jar

> jar xf *.jar

Se van a descomprimir algunos archivos después de la operación anterior.

###NOTA:
Hay que cambiar en la linea 53 del código:

	channel.connect("TALI");

"TALI" es el nombre del canal al cual se va conectar. Pueden cambiarselo pero los que se vayan a conectar al mismo canal deben tener ese nombre.

##3. Compilar Simplechat.java

> javac SimpleChat.java

##4. Ejecutar SimpleChat.java

> java SimpleChat -Djgroups.bind_addr=IP_MULTICAST -Djava.net.preferIPv4Stack=true
