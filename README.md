# conky
conky configuration example weather

# Instalación del conky

	#Para cualquier distro común de linux

	en consola->sudo aptitude install conky-all

	#Para el resto
	(...)

#agregar archivos de configuración:

Copiar el contenido de la carpeta .conky y el archivo .conkyrc a la carpeta /home/[user]/ 
(Son archivos ocultos)
	en consola->
		cp -r conky/.conky /home/[user]/
	en consola->
		cp -r conky/.conkyrc /home/[user]/

#Correr el conky

consola->conky

#Para modificar la vista del conky.
Modificar el archivo .conkyrc, agregando o quitando contenido. 

La Temperatura esta en Celsius y es la de Argentina Buenos Aires.

#Para modificar buscar woeid de tu ciudad aqui:

http://woeid.rosselliot.co.nz/

y modificar el .conkyrc en la parte de weather
