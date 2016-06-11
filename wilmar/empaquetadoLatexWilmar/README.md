# Proyecto Final Tendencias de Ingeniería de Software
#MCIC Maestría en Ciencias de la Información y las Comunicaciones
# Estudiante de Maestría Wilmar Diaz Rodriguez  wilmardiazr@gmail.com
# Mayo de 2016
Proyecto lateTextStudio, R Studio, Knitr 
Este Proyecto se requiere tener instalado los siguientes programas 
*R versión R-3.3.0
*R-Studio versión 0.99.893
*MikeTex  versión miktex-2.9.5872
*TextStudio versión texstudio-2.10.8
En el programa R-Studio se requieren algunos paquetes los cuales podrá instalar para su facilidad
Ejecutando dentro de r-stuido las siguientes instrucciones
install.packages("xtable ", dependencies = TRUE)
install.packages("ggplot2", dependencies = TRUE)
install.packages("MASS", dependencies = TRUE)
install.packages("knitr", dependencies = TRUE)
install.packages("stargazer ", repos="http://cran.r-project.org", dependencies = TRUE) 
#algunos paquetes puede que no sean compatibles con la versión que se tiene instalada de R sin embargo se puede poner como repositorio el repos="http://cran.r-project.org” y de esta manera se podrá descargar e instalar.
install.packages("jsonlite", repos="http://cran.r-project.org")
En el programa Miktex se requiere  algunos paquetes adicionales para que funcionen las librerías para esto en la instalación se le puede dar click en la opción instalar al vuelo de esta forma el instalara las librerías siempre y cuando estén disponibles de lo contrario será requerido ir de forma manual y descargar el paquete en el MiKTeX Package Manager (Admin) que sirve para instalar paquetes de forma manual. 

Así mismo la plantilla es una contribución de los estudiantes de maestría Leonel Muñoz Cedano leoneling@gmail.com y el ingeniero Raul Alejandro Buitrago Castellanos <raulhabits@gmail.com>
Adicionalmente para poderlo ejecutar se requiere que se configure adecuadamente  los entornos de desarrollo de Rstudio así como el Rstudio. El documento "Integración de RStudio con TexStudio.pdf"  que se encuentra en la misma carpeta que fue proveído por el profesor Jose Nelson Pérez Castillo <jnperezcourse@gmail.com>

En el proyecto se encuentra: como principal el archivo main.rnw el cual contiene el codigo reproducible.
Este archivo hace llamda a otro archivo .rnw que realiza la solucion a las preguntas de forma dinamica
y el dataset si se quiere correr de manera local para esto hay que cambiar la linea"json_file <- "http://servicedatosabiertoscolombia.cloudapp.net/v1/Departamento_Administrativo_de_la_Presidencia/situaciondesminadohumanitario?$format=json"
por
json_file <- "../DataSet/Desminado_Humanitario_Colombia.txt"



