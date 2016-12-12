# conky
conky configuration example weather

# Instalación del conky

	#Para cualquier distro común de linux

	:$ sudo aptitude install conky-all

	#Para el resto

	(...)

#agregar archivos de configuración:

Copiar el contenido de la carpeta .conky y el archivo .conkyrc a la carpeta /home/[user]/ 	

	:$ cp -r conky/.conky /home/[user]/
	:$ cp -r conky/.conkyrc /home/[user]/

#Correr el conky

	:$ conky

#Para modificar la vista del conky.

	Modificar el archivo .conkyrc, agregando o quitando contenido. 

#Para modificar Temperatura buscar woeid de tu ciudad aqui:

	http://woeid.rosselliot.co.nz/

	La Temperatura esta en Celsius y es la de Argentina Buenos Aires.

	y modificar el .conkyrc en la parte de weather
