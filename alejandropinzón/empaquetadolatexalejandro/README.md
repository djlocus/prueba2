# Proyecto
Proyecto latex TextStudio, R Studio, Knitr 

Alejandro pinzón Roberto 
e-mail: alejorobert@gmail.com

Proyecto latex TextStudio, R Studio y Knitr 

Para que este documento sea reproducible se requiere de un computador con arquitectura i386 o AMD64

Este documento dinamico fue construido sobre un computador con arquitectura AMD64 y sistema operativo GNU/Debian 8 Jessie

Las versiones de cada uno de los software utilizados en la construccion del documento dinamico son las siguientes:

-> LATEX: Instalar versión completa con todos los paquetes TeXLive-full
-> TexStudio:  version 2.10.8-5.1 -> descargar desde el repositorio el paquete "texstudio"
-> R: version 3.1.1-1 -> instalar desde el repositorio el paquete "r-base"
Se deben tener instalados los siguientes paquetes:
	library(xtable)
	library(ggplot2)
	library(knitr)
	library(stargazer)
	library(MASS)
	library(graphics)
	library(histogram)
	library(lattice)
-> Rstudio version 0,99.893 -> descargar desde el repositorio el paquete "rstudio"

Si se va a reproducir el documento dinamico en un computador con sistema operativo versión Microsoft Windows se debe habilitar la siguiente línea en el preambulo del documento:

\usepackage[latin1]{inputenc} para SO windows 

y desabilitar la siguiente linea:

%\usepackage[utf8]{inputenc} %tabla de caracteres para SO linux


SI se va a reproducir el documento dinamico desde un computador con linux dejar habilitado la siguiente linea en el preambulo del documento main.Rnw

\usepackage[utf8]{inputenc} %tabla de caracteres para SO linux 
