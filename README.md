# Hack-Nocimiento
#### Conocimientos básicos para entender ciertos procedimientos
##
<!-- wp:paragraph -->
<p><strong>SMB</strong>: es un protocolo de red que sirve para compartir recursos entre nodos que utilicen Windows, pertenece al protocolo TCP. Por ejemplo, compartir una impresora en una sala con varios ordenadores conectados en su red. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>SAMBA</strong>: es una ampliación de SMB para poder ejecutarse en equipos que no sean Windows.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>FTP</strong>: es una forma de obtener y transferir archivos entre computadoras.&nbsp;<strong>FTP</strong>&nbsp;es un&nbsp;<strong>protocolo</strong>&nbsp;de red estándar utilizado para la transferencia de archivos entre un cliente y un servidor</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>RPC:</strong> La llamada a procedimiento remoto es una tecnología que regula la&nbsp;<strong>comunicación entre procesos</strong>, es decir, el intercambio de información entre procesos de sistema</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>HTTP</strong>: es el protocolo de comunicación que permite las transferencias de información a través de archivos en la <strong>W</strong>orld <strong>W</strong>ide <strong>W</strong>eb. No confundir internet con <strong>WWW</strong>.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>TCP/IP:</strong> &nbsp;es un conjunto de protocolos&nbsp;<strong>que</strong>&nbsp;permiten la comunicación entre los ordenadores pertenecientes a una red.&nbsp;<strong>La sigla TCP</strong>/<strong>IP significa</strong>&nbsp;Protocolo de control de transmisión/Protocolo de Internet. Esta formada por capas. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>UDP</strong>: de su siglas (<strong>P</strong>rotocolo de <strong>D</strong>atagramas de <strong>U</strong>suarios) &nbsp;es un protocolo&nbsp;<strong>que permite la transmisión sin conexión de datagramas</strong>&nbsp;en redes basadas en IP. Es un protocolo parecido al <strong>TCP</strong>, con las diferencias de que <em>no está orientado a conexión</em>, es decir, no nos aseguramos de que la conexión se ha establecido. Tampoco se capacita para la<em> recuperación de errores</em>. Sin embargo es mucho más rápido. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>GET</strong>: es un método de http, utilizado como dice la palabra, para <em>obtener información del servidor</em>.  Destacar que los métodos GET pueden ser indexadas por buscadores, y su contenido es visible por URL. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>POST: </strong>este método sin embargo consiste en&nbsp;<em>enviar información</em>&nbsp;desde el cliente para que sea procesada y actualice o agregue información en el servidor, como sería la carga o actualización en sí de una noticia</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Ambos métodos utilizan una petición (<strong>Request</strong>) y se nos devuelve una respuesta (<strong>Response</strong>)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>cURL:</strong> es una herramienta par interacturar con servidores web. Sirve para descargar/solicitar/etc.. archivos o peticiones a un servidor web desde la linea de comandos de la terminal.  Maneja multiples protocolos. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>TELNET</strong>: es el nombre de un protocolo de red que nos permite acceder a otra máquina para manejarla remotamente como si estuviéramos sentados delante de ella. Este protocolo está en desuso por su falta de seguridad a la hora de enviar la información. En su lugar, se usa SSH.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>SSH</strong>: es el nombre de un protocolo y del programa que lo implementa cuya principal función es el acceso remoto a un servidor por medio de un canal seguro en el que toda la información está cifrada. Tal como dice su nombre ( <strong>S</strong>ecurity<strong> SH</strong>ell )</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>PUERTOS</strong>: es un medio de comunicación para los datos. Imagina vivir en un piso con 500 viviendas. Cada número identifica una vivienda y gracias a ella podemos saber a quien va dirigido los paquetes de datos.  El rango de puertos comprende de 0 a <strong>65535</strong>. ..(<strong>2^16</strong>)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>IP</strong>: es las siglas&nbsp;de <strong>I</strong>nternet <strong>P</strong>rotocol, o protocolo de internet. Este protocolo tiene la función de establecer las comunicaciones entre todos los dispositivos que tratan de relacionarse entre sí en internet. A groso modo, es un identificador del dispositivo en la red.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>SCRIPT</strong>: es una secuencia de comandos o instrucciones que se ejecutan con la intención de automatizar una acción. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>SHELL</strong>: es una interfaz de usuario donde a través de instrucciones (dadas generalmente por comandos) podemos acceder a servicios del sistema operativo. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>ICMP</strong>: es un protocolo de control de mensajes e información operativa, indicando por ejemplo, que un host no puede ser localizado o que un servicio que se ha solicitado no está disponible. Es un servicio que está dentro del protocolo<em> IP</em></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>SOCKET</strong>: se define al socket como la conexión entre dos procesos, con la finalidad de intercambiar datos. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>ARP</strong>: es un protocolo de resolución de direcciones, ​ responsable de encontrar la dirección de hardware que corresponde a una determinada dirección <em>IP</em>.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>LFI</strong>:<strong>  L</strong>ocal<strong> F</strong>ile<strong> I</strong>nclusión, es una técnica pentesting por la cual el atacante consigue leer archivos de distintas rutas del servidor, gracias a un archivo local alojado en él, debido a un fallo de programación en la web.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>RFI</strong>: <strong>R</strong>emote <strong>F</strong>ile <strong>I</strong>nclusión, parecido al <strong>LFI,</strong> con la diferencia de que el archivo "puente" no se encuentra en la maquina local de la victima, sino que se encuentra en nuestra propia maquina. Haciendo que la victima sea la que nos pida dicho archivo, para entablar una Reverse Shell.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>RCE</strong>: <strong>E</strong>jecución <strong>r</strong>emota de <strong>c</strong>ódigo, es el acto de poder ejecutar código de forma remota en el sistema vulnerable.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>XXS</strong>: <em>Cross-Site Scripting</em>, es una técnica de hacking que consiste en la inyección de código en un campo de texto. Para conseguir que el servidor nos los ejecute como código y no como texto plano. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>DOXING</strong>: &nbsp;es un término proveniente del inglés que se utiliza para describir la práctica en Internet de investigación y publicación de información privada o identificante sobre un individuo o una organización, generalmente con el propósito de intimidar, humillar o amenazar</p>
<!-- /wp:paragraph -->
