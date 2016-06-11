# Proyecto
Proyecto latex TextStudio, R Studio, Knitr 

Para que este proyecto de investigación sea reproducible en cualquier equipo debe tener
en cuenta las siguientes condiciones:

1) El Software de TeXstudio 2.8.8 (hg 4828+:0a999280f5cb+) Usando Qt Version 5.3.1, compilado con Qt 5.3.1 R

2) El Software de R debe ser de x64 versión 3.2.3

3) El Software de RStudio debe ser Versiónn 0.99.879 – © 2009-2016 RStudio, Inc.

4) En el sofwarte de RStudio debe haber instalado previamente los siguientes paquetes de librerias:
install.packages("xtable")
install.packages("ggplot2")
install.packages("knitr")
install.packages("stargazer")
install.packages("MASS")

5) Realizar los pasos como se encuentra en el documento : Integración de RStudio con TexStudio.pdf

6)Modificar la siguiente línea de código de los archivos exploratorio.Rnw y solucionQuestions.Rnw que se encuentran dentro de la carpeta codigoR
	datos <- read.csv2("E:/Dctos_Leonel/Docs_Maestria/GitHub/Proyecto/DataSet/HispanosSinNA.csv")   
	por la ruta absoluta en cual usted a colocado los archivos

7) Abrir text Studio y compilar el documento.


