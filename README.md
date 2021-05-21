# Despliegue y `rollback`

Esta práctica consiste en desplegar una aplicación que tenemos en una imagen llamada tuxotron/demoapp:v1. Luego actualizar a v2, y finalmente hacer un rollback a v1.

Lo que se pide es lo siguiente:

1. Despliegue de tuxotron/demoapp:v1, con dos réplicas.
2. Para comprobar que la aplicación está desplegada y funcionando, se pide la creación de un servicio para exponer el despliegue.
3. Depliegue de tuxotron/demoapp:v2, con dos réplicas también.
4. Usando el servicio creado en el paso 2, verificar que es ahora la versión v2 la que está activa.
5. Hacer un `rollback`
6. Comprobar que cuando accedemos al servicio de nuevo, es la versión v1 la que está activa. 

PD: tuxotron/demoapp escucha por el puerto 8080.

