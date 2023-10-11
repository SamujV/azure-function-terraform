# Azure Function Terraform
El objetivo de esta practica es crear un recurso Azure Function de forma automatizada y desplegar el código de ejemplo.
## terraform Init
Con el comando `terraform init` se descarga el provider que se va a ocupar, el cual esta definido en el código.

![Terraform Init](./images/init.png)
## terraform Validate
Con este comando nos aseguramos de que la sintaxis de los archivos .tf sean correctos.

![Terraform Validate](./images/validate.png)
## terraform Plan
Este comando nos permite ver los recursos que se van a crear una vez aplicado el código.

![Terraform Plan](./images/plan.png)
## terraform Apply
Con este comando desplegamos los recursos definidos en el código.

![Terraform Apply](./images/apply1.png)
![Terraform Apply](./images/apply2.png)
Al finalizar se obtiene la url de la función que desplegamos, la cual se definió en el archivo outputs.tf.
## URL
Validamos la ruta 
![url](./images/url1.png)

Obtenemos las respuestas esperadas.
![url](./images/url2.png)

## Resource Group
Vemos el recurso creado en Azure.
![Resource Group](./images/rg.png)
## terraform Destroy
Este comando nos permite eliminar los recursos que creamos desde el código.
![Terraform Destroy](./images/destroy1.png)

![Terraform Destroy](./images/destroy2.png)