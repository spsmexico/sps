1. ¿Es posible desplegar de forma automática el artefacto guardado en
packages utilizando Github Actions?

Sí. Por medio de otra acción para SCP.
Lista de acciones:
	Utilicé: appleboy/scp-action@master
	Ya que te permite utilizar SCP para deployment en servidor remoto.		
La llave SSH se debería guardar en los "secrets" del repositorio.

2. ¿En qué ayudaría utilizar la acción de cache?

En aumentar la velocidad de nuestro workflow.
Debido a que no se tendrían que descargar las mismas dependencias cada que
compilemos nuestra aplicación.







