# INTELIGENCIA ARTIFICIAL
***Integrantes y colaboradores:***
- Bradon Ramírez Vilegas.
- Alvaro Prado Bracamontes.
-  Sergio Raziel  Sanchez Cortez.
-  Hernández León Juan Armando.

>## En este documento se abordan los conceptos de esta semana relacionados con la **INTELIGENCIA ARTIFICIAL**

- ## **Hardware**

Conjunto de elementos físicos o materiales que constituyen una computadora o un sistema informático.

![](https://s1.significados.com/foto/hardware.jpg)

- ## **Software**

Conjunto de programas y rutinas que permiten a la computadora realizar determinadas tareas.

![](https://lh3.googleusercontent.com/proxy/IOLq1LigW3LCLnR0Ci4Knbzg6wq3zRaBRE6WhYkTmtau1ykiscJhWWYJ---C_ZSXdjx2T47IP0IT3t2CnCHn3KIMEMcck9GjOeY5i7-8HPgxYF7f1gIoxmnL)

- ## **¿Cómo funciona el internet?**

Internet es la columna vertebral de la Web, la infraestructura técnica que la hace posible. En lo más básico, Internet es una gran red de computadoras que se comunican simultáneamente.

### **Una simple red**

Cuando dos ordenadores necesitan comunicarse, tienes que vincularlos, ya sea físicamente (por lo general con un cable de Ethernet) o de forma inalámbrica (por ejemplo por WiFi o sistema de Bluetooth). Todos los ordenadores modernos pueden soportar cualquiera de este tipo de conexiones.

![A a B](https://media.prod.mdn.mozit.cloud/attachments/2014/08/22/8441/ea681a48c79629e6a2a9540515fa70d7/internet-schema-1.png)

La red no se limita a dos ordenadores, se pueden conectar tantos como se deseen aunque siendo más complicado cada vez. Por ejemplo, para conectar diez ordenadores, se necesitarían 45 cables y unos nueve conectores por ordenador.

![Multiple red](https://media.prod.mdn.mozit.cloud/attachments/2014/08/22/8443/563aefd8abf5018a8768564687c5bdeb/internet-schema-2.png)

Para resolver este problema, cada ordenador en una red está conectado a una pequeña computadora especial llamada enrutador o router (en inglés). Este enrutador cumple una función: tal como hace un señalizador en una estación de tren, el router se encarga de asegurar que el mensaje enviado desde un ordenador emisor llegue al destino correcto. Para que el ordenador B reciba un mensaje desde el ordenador A, este debe enviarlo primero al router, quien a su vez lo remite al ordenador B asegurándose que dicho mensaje no sea entregado a otro ordenador C.  

Una vez que agregamos un enrutador al sistema, nuestra red de 10 ordenadores solo requiere 10 cables: un enchufe para cada ordenador y un enrutador con 10 enchufes.

![Conexión](https://media.prod.mdn.mozit.cloud/attachments/2014/08/22/8445/961f9b7a5cd49e58f23745680f328530/internet-schema-3.png)

### **Una red de redes**

Hasta aquí todo es más o menos simple, pero ¿qué sucede al conectar cientos, miles, millones de ordenadores entre sí?. Por supuesto un solo enrutador no puede escalar tanto, pero, si lees cuidadosamente, dijimos que un enrutador es como un pequeño ordenador, entonces ¿qué nos impide conectar dos enrutadores a la vez?. Nada: hagámoslo.

![Routers](https://media.prod.mdn.mozit.cloud/attachments/2014/08/22/8447/18611ed10de3e11e38f8a99246e536c6/internet-schema-4.png)

Conectando ordenadores a enrutadores y luego enrutadores entre sí, podemos escalar infinitamente.

![](https://media.prod.mdn.mozit.cloud/attachments/2014/08/22/8449/54e24828741ca7a790ccbbfb5600b586/internet-schema-5.png)

Una red así se acerca mucho a lo que llamamos Internet, pero hay algo que nos falta. Construimos esa red para nuestros propios propósitos. Hay otras redes ahí fuera: tus amigos, tus vecinos, cualquiera puede tener su propia red de ordenadores. Pero no es posible instalar cables entre tu casa y el resto del mundo, así que ¿cómo puedes manejar esto? Bueno, ya hay cables conectados a tu casa, por ejemplo, la energía eléctrica y el teléfono. La infraestructura telefónica ya conecta tu casa con cualquier persona en el mundo, así que es el cable perfecto que necesitamos. Para conectar nuestra red a la infraestructura telefónica, necesitamos un equipo especial llamado modem. Este modem convierte la información de nuestra red en información manejable por la infraestructura telefónica y viceversa.

![](https://media.prod.mdn.mozit.cloud/attachments/2014/08/22/8451/4a71df9d5b0961e113c099b78e476ea7/internet-schema-6.png)

Entonces estamos conectados a la infraestructura telefónica. El siguiente paso es enviar el mensaje desde nuestra red a la red que queremos llegar. Para lograr eso, conectaremos nuestra red a un proveedor de servicios de internet (ISP de sus siglas en inglés Internet Service Provider). Un ISP es una empresa que gestiona algunos enrutadores especiales interconectados, que también pueden acceder a enrutadores de otros ISP. Así, el mensaje de nuestra red es llevada a través de la red de redes de ISP, hasta la red de destino. Internet consiste en toda esta infraestructura de redes.

![](https://media.prod.mdn.mozit.cloud/attachments/2014/08/22/8453/62b5d675e5881278ab3aec994f4fb9f4/internet-schema-7.png)

### **Encontrando ordenadores**

Si deseas enviar un mensaje a una computadora, debes especificar a cuál. Es por ello que todo ordenador conectado a una red cuenta con una dirección única que lo identifica, llamada “dirección IP” o Protocolo de Internet(IP de sus siglas en inglés Internet Protocol). Esta dirección está compuesta por una serie de cuatro números separados por puntos, por ejemplo: 192.168.2.10.

Para los ordenadores es un identificador simple, pero los humanos tienen mayor dificultad a la hora de recordar y memorizar este tipo de dirección. Con el propósito de convertir esta serie numérica en algo que podamos asociar con mayor facilidad a la dirección IP se utiliza lo que conocemos como nombre de dominio. Por ejemplo, google.com es el nombre de dominio utilizado para sustituir la dirección IP 173.194.121.32. Así, usar un nombre de dominio es la manera más fácil para nosotros de identificar un ordenador a través de Internet.

![](https://media.prod.mdn.mozit.cloud/attachments/2014/08/21/8405/edb9541101a98f8fec92d5ec5d921670/dns-ip.png)

### **Internet y la web**

Como puedes notar, cuando navegamos por la web con un navegador, normalmente utilizamos el nombre de dominio para llegar a un sitio web. ¿Significa eso que Internet y la Web son la misma cosa? No es tan simple. Como vimos, Internet es una infraestructura técnica que permite que miles de millones de ordenadores estén conectadas entre sí. Algunos de estos ordenadores, llamados servidores web son capaces de enviar mensajes inteligibles a los navegadores. Por tanto Internet es una infraestructura, mientras que la Web es un servicio construido sobre dicha infraestructura. Cabe señalar que existen otros servicios soportados por Internet, como es el correo electrónico e IRC.

- ## **Frontend y Backend**

Descubre comunicación nos dice:

![](https://descubrecomunicacion.com/wp-content/uploads/2019/07/forndend-backend-post2.jpg)

Son dos partes fundamentales de la programación de una aplicación web. 

### **Frontend**

Es la parte de una aplicación que interactúa con los usuarios, es conocida como el lado del cliente. Básicamente es todo lo que vemos en la pantalla cuando accedemos a un sitio web o aplicación: tipos de letra, colores, adaptación para distintas pantallas(RWD), los efectos del ratón, teclado, movimientos, desplazamientos, efectos visuales… y otros elementos que permiten navegar dentro de una página web. Este conjunto crea la experiencia del usuario. Debe ser una interface sencilla de usar, atractiva y funcional.

Un desarrollador frontend debe conocer los siguientes lenguajes de programación: HTML5, CSS3, JavaScript, Jquery, Ajax.

![](https://descubrecomunicacion.com/wp-content/uploads/2019/07/frondend-programing-language.jpg)

### **Backend**

es todo con lo que el usuario se encuentra directamente en la web o aplicación, entonces cuando hablamos de “Back end” nos referimos al interior de las aplicaciones que viven en el servidor y al que a menudo se le denomina “el lado del servidor”.

El back end del sitio web consiste en un servidor, una aplicación y una base de datos. Se toman los datos, se procesa la información y se envía al usuario.  Los desarrolladores de Front end y Back end suelen trabajar juntos para que todo funcione correctamente.

Un desarrollador Back end debe tener amplios conocimientos de los siguientes lenguajes: frameworks y los tipos de base de datos. No siendo necesario conocer todos los lenguajes pero sí entender y saber trabajar con algunos de ellos.

ASP.NET , PHP, Python, Ruby, Node.js, Java, MySQL, SQL Server, PostgreSQL, Oracle, MongoDB.

![](https://descubrecomunicacion.com/wp-content/uploads/2019/07/backend-database.jpg)

### **Full Stack**

Por otro lado, un desarrollador Full Stack es el encargado de manejar cada uno de los aspectos relacionados con la creación y el mantenimiento de una aplicación web. Para ello es fundamental que el desarrollador Full Stack tenga conocimientos en desarrollo Front-End y Back-End además de manejar diferentes sistemas operativos y lenguajes de programación.
