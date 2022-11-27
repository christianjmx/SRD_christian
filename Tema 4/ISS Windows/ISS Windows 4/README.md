## Informe 4 ISS - Christian Moreno 

## PHP.

  - Instalar PHP.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/1.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/2.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/3.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/4.png)

  - Instalamos CGI en el servidor y continuamos la intalación.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/5.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/6.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/7.png)

  - Comprobamos que se instaló correctamente despues de añadir el fichero index.php a nuestro sitio web.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/8.png)

  - Ahora vamos a proceder a instalar el MySQL. versión 5.5.27

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/9.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/10.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/11.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/12.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/13.png)

  (ponemos una contraseña para el root)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/14.png)

  (Creamos un nuevo usuario que se llame admin)
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/15.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/16.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/17.png)

  (Nos pedirá que istalemos framework 4, aunque ya lo tenemos instalado)
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/18.png)

  - Creamos el sitio web donde alojaremos el phpMyAdmin y configuramos el servicio DNS.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/19.png)

  - Comprobamos desde el servidor.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/20.png)

  - Ahora en el servidor vamos a descargarnos e instalar  el filezilla server.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/21.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/22.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/23.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/24.png)

  - En el filezilla creamos un nuevo usuario que se llame ftpuser y escogemos la ruta de la carpeta del sitio web.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/25.png)

  - Añadimos el alias ftp en el servicio DNS.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/26.png)

  - Comprobamos desde el clienteque conecta a l página web de phpMyAdmin.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/27.png)

  - Ahora descargamos e instalamos el filezilla cliente en el cliente.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/28.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/29.png)

  - Conectamos con el servidor desde el filezilla cliente.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/30.png)

  - Descargamos drupal 6.19

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/31.png)

  - Aquí deberiamos pasar por filezilla toto el contenido de drupal al servidor, pero por X razón que comentamos en clase, no aparecian los directorios de mi máquina local en el filezilla, asique directamente copie los archivos en la carpeta del sitio web.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/32.png)

  - Creamos un usuario y una base de datos desde phpMyadmin, desde el cliente.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/33.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/34.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/35.png)

  - Ahora en la siguiente ruta que se especifica duplicamos el archivo que existe y lo renombramos y damos permisos como se indica en la captura.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/36.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/37.png)

  - Vamos a uestro sitio web y vemos que podemos seguir con la instalación del drupal.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/38.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/39.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/40.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/41.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/42.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/43.png)

  - Lo ultimo que haremos es cambiar el idioma a español, primera mente instalaremos el modulo locale.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/44.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/45.png)

  - Ahora añadiremos el nuevo lenguaje.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/46.png)

  - A continuación descargamos el lenguaje desde la página de drupal y lo importamos.

![image]()

![image]()

  - Por último vamos a configurar nuestra página utilizando un tema.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/47.png)

  - Configuramos la primera página.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/48.png)

  - Configuramos la segunda página.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/49.png)

  - Este sería el resultado de nuestro sitio web.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/50.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/ISS%20Windows%204/IMG/51.png)

