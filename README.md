# ANTEPROYECTO

El proyecto consiste en utilizar un router mikrotik para implementar acciones de seguridad y alta disponibilidad. Instalaremos Winbox en el equipo servidor y 
realizaremos configuraciones en el mikrotik.
Una vez realicemos los cambios en el cliente y en el mikrotik para que haya acceso a internet realizaremos :

### Amarre IP/MAC por ARP
Es una de las medidas de seguridad más básicas y consiste en tener una lista de IP Y MAC registradas en el servidor, de esa manera un instruso con una IP o MAC
distintas a las que estan registrados no tendra internet y no tendra respuesta ninguna.

### Ancho de banda
Vamos a asignar un ancho de banda específico para cada cliente, para que no puedan sobrepasar el límite establecido.

### WebProxy
Almacenara los elementos de las páginas que nuestros clientes visitaron, así dichos elentos saldrán de nuestro disco duro y no de internet así ahorramos ancho de banda
y se mejoraría la velocidad de navegación. También podremos bloquear páginas y redirreccionarlas.

### WebProxy Transparente
Asi se obliga a los clientes a pasar por el WebProxy sin que se den cuenta y sin tocar su navegador.

### Liberar Velocidad de WebProxy(Full Caché)
Se utiliza para acceder a mayor velocidad a páginas que el cliente haya accedido anteriormente.

### Hostpot (Portal Cautivo)
Permite capturar el tráfico http de nuestros clientes y redireccionarlo para autentificarlo, una vez que es autenticado puede acceder a todos los servicios de internet con normalidad.

## Planificación temporal

Tengo que investigar todos los apartados para realizarlos correctamente. En encontrar el mikrotik, que puede proporcionarmelo el instituto, prepararlo y la configuración
básica puedeo tardar un o dos días.
En el Amarre IP/MAC por ARP, Ancho De Banda WebProxy y Hotspot tardaría mínimo 2 días en cada cosa (posiblemente más) porque tengo que investigar y comprobar que 
funciona correctamente.
