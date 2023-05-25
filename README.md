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