# WORKSHOP-3
Juan David Martinez Lopez

Cristian Rosales

Santiago Barrera

Parte 1

Ipconfig: Es un comando de Windows el cual es muy útil para obtener información rápida de los ajustes principales de la red TCP/IP en el cual cubre los adaptadores e interfaces de red existentes.

Ping: Esta comprueba la conectividad a otro equipo TCP/IP esto lo hace mediante el protocolo de mensajes de control de internet, su principal función es la de solucionar problemas de conectividad, facilidad de acceso y resolución de nombres

Tracert: El comando tracert o también conocido como Traceroute es usado para gravar un ruta de intenet entre tu PC y una destinación especifica de computador 

Netstat: Muestra el estado de la red y las estadísticas del protocolo.

Telnet: Se usa para comunicarse con un servicio que esté corriendo telnet.

Net: Un comando que deja configurar los ajustes de red, para actualizar o para arreglar una red.

Route: Un comando que permite configurar el enrutamiento del sistema

Arp: se usa para modificar la traucción de direcciones que usa el adaptador.

Nbtstat: se usa para dignosticar problemas en el netBIOS usando un protocolo tcp

Netsh: un comando que muestra o deja modificar la configuración de red que esté usando el dispositivo.

Get: trae todos los comandos que están instalados en el dispositivo

Parte 2

a.Un administrador de red digitael comando de red mostrado en la Figura 1. ¿Qué significa la dirección de red que se encuentra entre los corchetes?

![A](https://user-images.githubusercontent.com/98998448/189466015-53f20bf7-69b2-45eb-9b77-dc48885b2a22.png)

Lo que se encuentra entre corchetes es una dirección ip de la red local la cual es la dirección ip privada de nuestro router.
	
b.Un administrador de red digita el comando de red mostrado en la Figura 2. ¿Qué quiere decir Tiempo de espera agotado para esta solicitud?

![B](https://user-images.githubusercontent.com/98998448/189466096-1f1494a1-b764-47bf-896a-935f46ef4055.png)

   Esto significa que no se ha podido establecer contacto con el host de destino. Esto se puede dar cuando realizamos ping a un sitio o equipo que no es accesible.
	
c.Un administrador de red digita el comando de red mostrado en laFigura 3. Explique el significado de: (1) bytes=32, (2)tiempo=7ms, y (3)TTL=64.

![C](https://user-images.githubusercontent.com/98998448/189466144-c0f7b3b2-a73d-454a-aeb7-9361dc1e8249.png)

   1. Nos esta informado que el tamaño de los paquetes enviados es de 32.

   2. El tiempo que se demora en enviar y recibir respuesta del host destinatario.
   
   3. El TTL nos esta informado el tiempo de vida de cada salto que se hace hasta llegar al host.
	
d.Un administrador de red digita el comando de red mostrado en la Figura 4. ¿Qué direcciones IP y físicas se muestran en la figura? ¿Qué significa direccionamiento dinámico?

![D](https://user-images.githubusercontent.com/98998448/189466159-f71da93f-f151-4b54-82c7-5f6ebadf05c5.png)

   Se muestran dos direcciones ip una es nuestra direccion ip y la otra hace referencia a la de la puerta de enlace y ademas nos muestra que tiene un direccionamiento dinamico lo cual significa que esta actualizando las tablas de direccionamiento de manera automatica

e.Un administrador de red digita el comando de red mostrado en la Figura 5. Explique los términos Destino de red, Máscara de red, Puerta de acceso, Interfaz, Métrica.

![E](https://user-images.githubusercontent.com/98998448/189466171-843b9e6d-712d-478e-ad3d-b93896184470.png)

Mascara de red
La máscara de red es un conjunto de bits los cuales se usan para delimitar una red de ordenadores para así por dividir la red en subredes

Métrica
El valor que se le asigna a una ip para una interfaz de red determinada


f.Un administrador de red digita el comando de red mostrado en la Figura 6. ¿Para qué sirve esa información? ¿Realiza la misma función de netstat –p TCP?

![F](https://user-images.githubusercontent.com/98998448/189466176-6613dad6-e71d-4fdb-9c15-ab75547a21c4.png)

  En este caso esa informacion nos muestra de manera superficial el estado de las conexiones actuales en nuestra red lo cual tiene como diferencia entre el netstat –p TCP que este en vez de mostarlo de manera estandar este lo muestra de manera enfocada hacia el protocolo tcp
  
g.Un administrador de red digita el comando de red mostrado en la Figura 7. ¿Qué significa Traza? ¿Qué indica el número de saltos? ¿Qué significa el <1 ms en cada salto? ¿Para qué se realiza una Traza?¿En qué momento es útil utilizar el comando Tracert?

![G](https://user-images.githubusercontent.com/98998448/189466183-096af651-8959-4500-9d11-f6a06a96ba98.png)

1.	¿Qué significa Traza?
La pista de los paquetes que viene de un host

2.	¿Qué indica el número de saltos?
Nos indica el máximo de saltos que hará el tracert siendo en este caso teniando un max de 30 saltos entre los cuales se usan 3

3.	¿Qué significa el <1 ms en cada salto? 
Es el tiempo mínimo medio y máximo entre cada salto

4.	¿Para qué se realiza una Traza?
Nos ayuda a determinar la ruta a un destino mediante el envió de paquetes de datos

5.	¿En qué momento es útil utilizar el comando Tracert?
Nos ayuda a determinar problemas en redes internas externas o en camino hacia un sitio web ya que este nos proporciona la información que trazan los paquetes de datos y así podemos determinar en donde está el problema, que origina el problema, de que dispositivo es el problema y como se podría solucionar el problema

Parte 3

Ping: determina si un host es accesible

traceroute: se usa para rastrear paquetes y verificar el correcto flujo de información.

whois: brinda información de un dominio consultado.

Nmap: se utiliza para determinar que sistemas se encuentran en línea.

iperf: abrir conexión entre dos hosts y enviar datos.

Nslookup: obtener dominios y direcciones IP iwconfig: configurar interfaces inalámbricas
