# VOIP Linux   Sergio y Christian #

Lo primero que tenemos que hacer es descargarnos la ISO de FreePBX e instalarlo.

Seguimos los pasos de la instalación con normalidad.


![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/1.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/2.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/3.png)

Establecemos una contraseña para la cuenta de Root

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/4.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/5.png)

Con esto ya lo tenemos instalado.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/6.png)

Lo siguiente es poner esta máquina en red interna con el cliente para que se comuniquen entre ellas. Luego nos vamos al navegador del cliente y ponemos la IP del FreePBX

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/7.png)

Una vez configuramos los datos necesarios, tenemos que darle a siguiente.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/8.png)

Ahora le damos a Administración para poder llegar hasta el panel de control.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/9.png)


En este proceso le damos a siguiente siempre, no debería dar problemas.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/10.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/11.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/12.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/13.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/14.png)

Con todo esto llegaremos al panel de control.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/15.png)

Para agregar los usuarios nos tenemos que ir a Applications > Add Extension > + Add New SIP [chan_pjsip] Extension

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/16.png)

Una vez dentro solo tenemos que configurarlo tal y como se ve a continuación:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/17.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/18.png)

Debemos crear 2:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/19.png)

Una vez hemos creado los usuarios tenemos que descargarnos ZoiPer para ver si funciona todo correctamente.

Una vez instalado entramos con unos de los usuarios que hemos creado.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/20.png)

Le ponemos la dirección del servidor

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/21.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/22.png)

Ahora para poder hacer que funcione con el teléfono debemos cambiar las tarjetas de red a adaptador puente para que tengan la misma red que el telefono.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/23.png)

Descargamos la Aplicación en el teléfono e iniciamos sesión con el otro usuario.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/zoi1.jpg)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/zoi2.jpg)

Ahora vamos a llamar al usuario 10 desde el telefono.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/zoi3.jpg)

Observamos que el recibimos la llamada en el usuario 10 en la máquina virtual.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/24.png)

Ahora llamamos desde la máquina virtual al movil y como se puede apreciar en la parte superior de mi teléfono, recibimos la llamada correctamente.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%209/VOIP%20Linux/IMG/zoi4.jpg)


