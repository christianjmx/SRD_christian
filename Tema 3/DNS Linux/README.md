# DNS Linux - Christian Moreno #

- Instalamos el bind9 en el servidor.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%203/DNS%20Linux/IMG/1.png)

- Configuramos el servidor DNS es el mismo en (/etc/resol.conf)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%203/DNS%20Linux/IMG/2.png)

- Configuramos los reenviadores para hacer el servidor como cache.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%203/DNS%20Linux/IMG/3.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%203/DNS%20Linux/IMG/4.png)

- Comprobamos las resoluciones de nombres externos, tanto en el servidor como en un cliente.

(servidor)
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%203/DNS%20Linux/IMG/5.png)

- Colocamos en los DNS del cliente la IP de nuestro servidor DNS

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%203/DNS%20Linux/IMG/6.png)

- Comprobamos que resuelve desde el cliente.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%203/DNS%20Linux/IMG/7.png)

- Configuramos como DNS maestro.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%203/DNS%20Linux/IMG/8.png)

- Configuramos el archivo de busqueda directa.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%203/DNS%20Linux/IMG/9.png)

- Verificamos que el documento esté con una sintaxis correcta.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%203/DNS%20Linux/IMG/10.png)

- Configuramos la zona de busqueda inversa.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%203/DNS%20Linux/IMG/11.png)

- Verificamos que el documento esté con una sintaxis correcta.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%203/DNS%20Linux/IMG/12.png)

## Error ##

- Después de estar intentando varias configuraciones de los archivos, al intentar resolver un nombre, daba un error de NXDOMAIN constantemente. Al cual no pude encontrar solución, ya que los ficheros estaban identicos a los de otros compañeros que si les habían funcionado.











