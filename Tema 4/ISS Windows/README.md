# ISS Windows - Christian Moreno #

# Primer PDF #

  - Instalamos el servicio ISS en nuestro servidor

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/1.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/2.png)

  - Comprobamos el acceso a nuestro servidor web desde el servidor.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/3.png)

  - En el panel de configuración de ISS seleccionamos nuestro sitio web y habilitamos la autenticación básica.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/4.png)

  - Entramos a nuestro servidor web desde un cliente. En este caso windows 7.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/5.png)

  - Ahora con un nombre de dominio.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/6.png)

  - Creamos un nuevo host para acceder desde el al servidor web "serverwin-christi".

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/7.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/8.png)

  - En la ruta especificada creamos una pequeña página web para que se muestre en nuestro servidor. Comprobamos desde el servidor y cliente.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/9.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/10.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/11.png)

  - Ahora comprobamos la página entrando con un nombre de dominio.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/12.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/13.png)

  - Creamos carpetas organizadas dentro de la dirección anterior y una pequeña página. Comprobamos en cliente y servidor.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/14.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/15.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/16.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/17.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/18.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS/19.png)


# Segundo PDF #

  - Creamos el directorio independiente donde se va ha alojar los archivos de la página.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS%202/1.png)

  - En el panel de configuración del ISS agregamos un nuevo sitio web.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS%202/2.png)

  - Especificamos la ruta del sitio web y el nombre del sitio web, debe ser dentro de nuestro dominio.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS%202/3.png)

  - Creamos el alias "serv" para poder entrar al sitio web que acabamos de crear.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS%202/3%2C5.png)

  - Ahora según vi en foros, hay que añadir al usuarui "IUSR" al sitio web para que nos deje verla.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS%202/4.png)

  - Creamos el html de la página en la carpeta especificada.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS%202/5.png)

  - Comprobamos la página en servidor y el cliente.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS%202/6.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS%202/7.png)


# Tercer PDF #

  - Dentro de la carpeta de la páctica anterior creamos otra y dentro distintos directorios de carpetas. Cada una con su Index.html
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS%203/2.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS%203/3.png)

  - En el panel del ISS creamos nuevos hosts virtuales.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS%203/4.png)

  - Seleccionamos la ruta de los archivos y el alias.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS%203/5.png)

  - Ahora en el sitio web habilitamos la opción de Examen de directorios, para que muestre los directorios.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%204/ISS%20Windows/IMG/ISS%203/6.png)


## En este momento a la hora de conectar con cualquier página me salía error 500, después de varias horas consultando en foros, decidí crear todo desde cero y me volvió a dar el mismo problema, no supe resolver este problema y por lo tanto no pude realizar al 100% este último PDF ##



