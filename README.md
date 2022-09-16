
<h1 align="center">Herramienta #OSINT para la obtención de relaciones en Facebook</h1>

## Descripción:

RelationsFB es una herramienta #OSINT que muestra y descarga (en Formato .CSV) las relaciones de un perfil de Facebook con solo ingresar el FBID (Identificación de Facebook); solo si los propietarios de este perfil lo tiene de modo público. La herramienta permite elegir el tipo de relación que deseas obtener según la opción seleccionada por el investigador.

## Características:

* Muestra el nombre registrado según el tipo de relación que desee obtener del objetivo.
* Muestra el FBID según el tipo de relación que desee obtener del objetivo.
* Muestra el enlace del perfil según el tipo de relación que desee obtener del objetivo.
* Muestra el enlace de la imagen del perfil según el tipo de relación que desee obtener del objetivo.

## Método de instalación:

**NOTE**: Python 3 and pip3 is required

```bash
git clone https://github.com/Manuelq059/RelationsFB && cd RelationsFB
pip3 install -r requirements.txt
```

## Uso:

`python3 RelationsFB.py -i FBID `

En el "FBID" digitar el número de identificación de Facebook del Objetivo.

## A continuación digitar según la lista que desee obtener:

* 1 - Lista de todos sus amigos (All for Friends).
* 2 - Lista de todos sus seguidores (Followers).
* 3 - Lista de todos los el objetivo sigue (Following)
* 4 - Lista de todos los que viven en su ciudad natal (Hometown)
* 5 - Lista de todos los que viven en su ciudad actual (For current city)
* 6 - Lista de amistades recientes (For recent friendship)
* 7 - Lista de amistades del colegio (friends of high school)

En la carpeta de la herramienta se crea un archivo en formato .CSV con el número de identificación FBID.

## Ejemplos de uso:

```bash
# python3 main.py -i FBID make HTML and PDF reports
python3 RelationsFB.py -i 4 

# 1 - Amigos | 2 - Seguidores | 3 - Siguiendo | 4 - Amigos de ciudad natal | 5 - Amigos ciudad actual | 6 - Amistades recientes| 7 - Amistades de colegio. 
 Digite número ==>1

```
#### 4 es la identificación de Facebook de [Mark-Zuckerberg](https://www.facebook.com/4)

## Resultados:
<p align="center">
  <img src="https://subir-imagen.com/images/2022/09/16/tedd1.jpg" width=500 />
</p>
<p align="center">
  <img src="https://subir-imagen.com/images/2022/09/16/tedd2.jpg" width=500 />
</p>
<p align="center">
  <img src="https://subir-imagen.com/images/2022/09/16/tedd3.jpg" width=500 />
</p>

<p align="center">
  <img src="https://subir-imagen.com/images/2022/09/16/tedd4.jpg" width=500 />
</p>

NOTA: Herramienta desarrollada por [Eriys](https://github.com/Eriys)
