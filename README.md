# Cliente DNS

**En la siguiente imagen se muestra cómo está configurado el Servidor DNS y cómo está configurado el cliente utilizando una imagen Alpine.**

**Además muestra cómo el cliente tiene como DNS a dicho servidor**

![ Configuración del Compose ](./imagenes/cliente.png)

**Por defecto Alpine tiene el comando Ping. Para instalar el dig se utiliza el siguiente comando:**

    apk add --update bind-tools

![ Ping desde Alpine ](./imagenes/ping_alpine.png)

**En el documento "asircastelao.int" podemos ver una tabla con una lista de direcciones**

![ asircastelao ](./imagenes/castelao.png)

**Ahora con el comando dig podemos comprobar si cliente resuelve con el dns configurado**

![ Dig con IP ](./imagenes/dig_ip.png)

![ Dig sin IP ](./imagenes/dig_noip.png)

**hola**