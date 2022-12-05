# Apache Linux - Christian Moreno

## Apache:

  - Instalamos el paquete de apache.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/1.png)

  - Comprobamos la carpeta raíz del sitio.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/2.png)

  - Comprobamos el acceso mediante localhost.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/3.png)

  - Añadimos un host asociada a la ip del servidor.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/4.png)

  - Reiniciamos el servicio y comprobamos que funciona con el nombre de host.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/5.png)

  - Observamos los ficheros de log.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/6.png)

## PHP:

  - Comprobamos que tengamos instalado el php.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/7.png)

  - Creamos el archivo .conf del sitio.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/8.png)

  - Reiniciamos el servicio y comprobamos que el sitio esté activo.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/9.png)

  - Añadimos un nuevo host.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/10.png)

  - Comprobamos el sitio web de php.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/11.png)


## host virtuales

  - Creamos el index del sitio web.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/12.png)

  - Añadimos un nuevo host.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/13.png)

  - Creamos y configuramos el sitio web.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/14.png)

  - Comprobamos el sitio web.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/15.png)

## Configurar sitio web seguro pagos

  - Generamos el certificado.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/16.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/17.png)

  - Comprobamos el certificado y reiniciamos el servicio.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/18.png)

  - Creamos el index de la página segura.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/19.png)

  - Modificamos el fichero de configuración del sitio seguro.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/20.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/21.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/22.png)

  - Habilitamos el modulo ssl y reiniciamos el servicio.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/23.png)

  - Añadimos un nuevo host (Cambian las IP por que seguí la práctica en mi casa)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/24.png)

  - En este punto no me dejaba reiniciar el servicio apache, dado que tenía algún tipo de fallo en el fichero de configuración del sitio web seguro, despues de pasarme horas buscando no conseguí encontrar el fallo y decidí seguir con la práctica.
  
## Acceso a carpetas seguras:
  
  - Modificamos el fichero del sitio web empleados. 

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/25.png)

  - Creamos las carpetas de los usuarios con sus respectivos index.html.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/26.png)

  - Generamos las claves de los usuarios.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/27.png)

  - Creamos el fichero .htaccess en todos los directorios de los usuarios.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/28.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/29.png)

  - Comprobamos que funciona la autentificación

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/30.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/31.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/32.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/33.png)

## Mysql y PHPMyAdmin

  - Instalamos Mysql
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/34.png)

  - Comprobamos que tenemos instalados Mysql y PHP
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/35.png)

  - Comprobamos que podemos acceder a la página de phpmyadmin.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/36.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/37.png)

## Plataforma wordpress:

  - En phpmyadmin creamos un nuevo usuario y una base de datos que se llame como el mismo.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/38.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/39.png)

  - Configuramos archivo de configuración del sitio web.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/40.png)

  - Descargamos de internet el wordpress y lo descomprimimos en la ruta del sitio web.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/41.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/42.png)

  - Creamos un nuevo host.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/43.png)

  - Entramos en la página y empezamos la instalación y configuración del wordpress.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/44.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/45.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/46.png)

  - Aquí debemos crear este archivo dentro del directorio del sitio web y copiar lo que nos indica
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/47.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/48.png)

  - Continuamos con la configuración.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/49.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/50.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/51.png)

  - Accedemos y ya estaría listo.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/52.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/Apache%20Linux/IMG/53.png)































































































