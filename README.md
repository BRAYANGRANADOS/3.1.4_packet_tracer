# 3.1.4_packet_tracer
## 3.1.4 Packet Tracer - Who Hears the Broadcast
![descarga](https://github.com/BRAYANGRANADOS/3.1.4_packet_tracer/assets/97776616/f6c3775a-7182-4223-b129-d2ffc1650301)

### PREGUNTAS DE INTRODUCION
> [!NOTE]
> &#9312; Mencione, al menos, tres otras aplicaciones que estén disponibles para utilizar.
> 
> &#9313; g.	Haga clic en Capture/Forward (Capturar/Adelantar) dos veces. ¿Qué sucedió con el paquete?

### RESPUESTAS DE INTRODUCION
> [!IMPORTANT]
> &#9312; R// DNS, FINGER, FTP, HTTP, HTTPS, IMAP, NETBIOS, PING, POP3, SFTP, SMTP, SNMP, SSH, TELNET, TFTP y OTHER.
> 
> &#9313; R// El paquete se envía al switch y, luego, se transmite por difusión a todas las computadoras que 
pertenecen a la misma VLAN y, en este caso, la VLAN 10.

### PREGUNTAS DE REFLEXION
> [!NOTE]
> &#9312;	Si un equipo en la VLAN 10 envía un mensaje de difusión, ¿qué dispositivos lo reciben?
>
> &#9313; Si una computadora en la VLAN 20 envía un mensaje de difusión, ¿qué dispositivos lo reciben?
>
> &#9314; Si una computadora en la VLAN 30 envía un mensaje de difusión, ¿qué dispositivos lo reciben?
>
> &#9315; ¿Qué le sucede a una trama enviada desde un equipo en la VLAN 10 hacia un equipo en la VLAN 30?
>
> &#9316; ¿Qué puertos del switch se encienden si una computadora conectada al puerto 11 envía un mensaje de unidifusión a una computadora conectada al puerto 13?
>
> &#9317; ¿Qué puertos del switch se encienden si una computadora conectada al puerto 2 envía un mensaje de unidifusión a una computadora conectada al puerto 23?
>
> &#9318; Desde el punto de vista de los puertos, ¿cuáles son los dominios de colisiones en el switch?
>
> &#9319; Desde el punto de vista de los puertos, ¿cuáles son los dominios de difusión en el switch?

### RESPUESTA DE REFLEXION
> [!IMPORTANT]
> &#9312; R// Todas las terminales en la VLAN 10.
> 
> &#9313; R// Todas las terminales en la VLAN 20.
>
> &#9314; R// Todas las terminales en la VLAN 30.
>
> &#9315; R// Se descarta, porque no están en la misma VLAN.
>
> &#9316; R// Los puertos 11 y 13.
>
> &#9317; R// El paquete se descartará.
>
> &#9318; R// Cada puerto es su propio dominio de colisiones.
>
> &#9319; R// Cada VLAN es su propio dominio de difusión.
