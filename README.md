# Aplicación de Colas con Socket.io
Un servidor de Websockets usando Node, Express y Socket.io

# Preparacion

## Instala todas las depencias necesarias
>npm install

## Crea variables de entorno
Crea el fichero ./.env y indica el puerto del servidor :
.env_   _   _

    PORT=8080
_   _   _   _

# Inicia 
node app


## doc
Esta aplicacion sirve para llevar las colas de atencion al cliente.

### Inicio
- Ingresar, ingresas en un escritorio para atender un nuevo numero de ticket en una colas.
- Pantalla Publica,  la pantalla donde se muestra el numero de ticket y el numero de cola en el que sera atendido.
- Crear Ticket,  Sacar un nuevo ticket para la cola

![Image text](https://github.com/CodeBAou/SocketAppCola/blob/master/md-imagen/init.png)

### Gnerar un nuevo ticket
Lanza el siguiente ticket a la pantalla publica
![Image text](https://github.com/CodeBAou/SocketAppCola/blob/master/md-imagen/generarTicket.png)

### Pantalla public
Muestra las diferentes colas y el ticket que sera atendido en cada una de ellas
![Image text](https://github.com/CodeBAou/SocketAppCola/blob/master/md-imagen/pantalla_publica.png)

### Atender un nuevo ticket
![Image text](https://github.com/CodeBAou/SocketAppCola/blob/master/md-imagen/escritorio.png)
