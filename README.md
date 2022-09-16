# RelationsFB

RelationsFB es una herramienta #OSINT que descarga las relaciones de un perfil de Facebook con solo ingresar el FBID (Identificación de Facebook).
Siempre y cuando, si los propietarios de este perfil lo tiene de modo público. La herramienta permite elegir el tipo de relación que deseas obtener según la opción seleccionada por el investigador.

# Método de instalación:
` git clone https://github.com/Manuelq059/RelationsFB.git`
` pip3 install -r requirements.txt `

# Ejecutar.

`python3 main.py -i FBID `
En el "FBID" digitar el número de identificación de Facebook del Objetivo.

# Digitar según la lista que desee obtener.
* 1 - Lista de todos sus amigos (All for Friends).
* 2 - Lista de todos sus seguidores (Followers).
* 3 - Lista de todos los el objetivo sigue (Following)
* 4 - Lista de todos los que viven en su ciudad natal (Hometown)
* 5 - Lista de todos los que viven en su ciudad actual (For current city)
* 6 - Lista de amistades recientes (For recent friendship)
* 7 - Lista de amistades del colegio (friends of high school)

NOTA: Herramienta desarrollada por `https://github.com/Eriys`
