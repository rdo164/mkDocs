# mkDocs
MkDocs documentation. <br>
## Instalación:
```
pip install mkdocs
```
Te lo instala en el WORKON_HOME, sino en la ruta en la que esta en la línea de comandos.


## Crear tu archivo mkdocs:
```
     mkdocs new nombre del proyecto
```

> Automáticamente te genera una carpeta con el nombre del proyecto y dentro de ella un **archivo.yml** para la configuración y una **carpeta docs**, **AQUÍ** IRA LA **DOCUMENTACIÓN en .MD**. Además dentro de la carpeta docs te crea un index.md
<center>

![imagen](.\images_documentación\1.png)
</center>


## Runnea el servidor
```
    mkdocs serve
```

## Configuración de .yml

Se pueden añadir temas pero hay que **instalarlos**

Las dos **únicas opciones de configuración** son:
```
- site_name: PEPAS-API
- site_url: https://example.com/
```

## Desplegarlo en Github Pages
> Hay que crear una Github Actions
dentro del directorio crear la carpeta .github
dentro de la carpeta otra carpeta llamada workflows y en esta creamos nuestro archivo .yml para conseguir el CICD.
Píldora Path
``` 
Carpeta padre/
              .git
              .github/ 
                      workflows/
                                XXXXXXXX.yml(encargado del CICD)
```

## CREAR EL CICD 

POWERSHELL en **administrador**

en el archivo .yml runs-on:[self-hosted]



## 
dentro de github pages se ha creado una nueva rama (gh-pages) para la automaticzacion de la página web

## CREAR ENTORNOS VIRTUALES CON VENWRAPPER
1. Instalar python
2. Instalar gestor de paquetes PIP
```
curl https://boootstrap.pypa.io/get-pip.py
```
3. Instalar **virtualenwrapper** (provee un entorno virtual dedicado a cada proyecto desarrollado con django)
```
pip install virtualenvwrapper-win
```
4. 
mkvirtualenv nombre_del_entorno 
