# Juego-Graficacion--Recolector-de-fresas
Recolector de fresas

A continuación, se realiza una breve descripcion de cómo  ejecutar el proyecto. 

### Requerimientos
- Visual Studio, se recomenda en la versión del 2015 o la más reciente. 
- En su ordenardor, debe tener una carpeta que incluya las librerias correspondientes a "Glut". Adjuntamos un Link donde podras encontrar la carpeta con las librerias necesarias. 
```shell
https://drive.google.com/drive/folders/1jedxwgXz8P9nIBzqZYdcXBLyPUOlVU3y?	 usp=sharing
```
### Ejecición
1. Al ejecutar el visual studio seleccionado, debemos seleccionar el proyecto "Texturas.sln"
2. Una vez abierto la solución, debemos asignar las librerias al proyecto, esto se puede hacer desde las propiedades del proyecto, en "Propiedades de configuración", seleccionamos "C/C++" y en "Directorios de inclusion adicionales", tendremos algo parecido a esto:
```shell 
	D:\PC\Documents\Semestre VI\Graficación\glutdlls37beta;%(AdditionalIncludeDirectories)
```
3. Debemos copiar la ubicacion del directorio con las librerias "Glut" y pegarla en el lugar de: 

```shell 
	D:\PC\Documents\Semestre VI\Graficación\glutdlls37beta
```
4. El paso 3 lo realizaremos en la seccion de "Vinculador" y en "Directorios de bibliotecas adicionales"

NOTA: Es importante que se realice el cambio sin modificar  **;%(AdditionalIncludeDirectories)**
 
## Sobre el Juego 
**Recolector de Fruta,** es un juego en el cual seras participe de un personaje con perspectiva en pimera persona, controlado desde tu teclado podras moverte por todo el escenario creado a base de texturas y dimensionado en 3D.

### Jugabilidad y Reglas
* Podras mover al personaje con tres teclas principales.
```shell
a: avanzar a la izquerda.
d: avanzar a la derecha.
w: avanzar adelante.
```
* Para terminar y ganar el juego, debes recoger todas las cajas de frutas dentro del juego, solo se podran recoger las fresas, entonces debes siempre tomar las cajas por la cara donde se encuentren las fresas. 
