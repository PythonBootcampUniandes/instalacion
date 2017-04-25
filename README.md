# Guía de instalación
Guía e instrucciones de instalación del software requerido para el Python Bootcamp Uniandes

Para la realización del Bootcamp se aconseja la instalación de Anaconda. A continuación se hace una descripción del proceso de instalación en los diferentes sistemas operativos (**Partiendo de que no existe una distribución previa de Python instalada**):

## Windows

**1.** Como paso inicial al proceso de instalación se recomienda verificar que su nombre de usuario en Windows no tenga espacios ni caracteres como tildes, comas, apóstrofes o eñes. Esto debido a que se pueden generar errores de codificación.

**2.** Descargar la versión apropiada (32 o 64 bits) de Anaconda asociada a la versión 3.x de Python. En caso de no estar seguro de la versión de Windows instalada puede descargar la versión de 32 bits sin problema. [Aquí encuentra la página de descarga](https://www.continuum.io/downloads#windows)

**3.** Luego de finalizada la descarga del instalador, de doble clic sobre el mismo (archivo `.exe`), acepte el contrato de licencia y de siguiente dejando los valores por defecto donde se requiera:

**Pantalla Inicial:**

![ini](/../dalthviz-guia-instalacion/capturas/windowsInicial.png?raw=true)

**Licencia:**

![lic](/../dalthviz-guia-instalacion/capturas/windowsLicencia.png?raw=true)

**Preferencias de instalación (usuario):**

![pref](/../dalthviz-guia-instalacion/capturas/windowsPref.png?raw=true)

**Nota:** Se recomienda que la instalación se realice solo para el usuario actual para evitar problemas con los permisos de administrador posteriormente.

**Preferencias de instalación (ubicación):**

![dir](/../dalthviz-guia-instalacion/capturas/windowsDir.png?raw=true)

**Preferencias de instalación (variables de entorno):**

![path](/../dalthviz-guia-instalacion/capturas/windowsPath.png?raw=true)

**Instalación completa y finalización:**

![com](/../dalthviz-guia-instalacion/capturas/windowsComp.png?raw=true)

![fin](/../dalthviz-guia-instalacion/capturas/windowsFinish.png?raw=true)

**4.** Finalizada la instalación verfique que tanto `Spyder` como `Jupyter Notebook` están instalados. Para esto puede dirigirse al menu de inicio

**Spyder**

![spyder](/../dalthviz-guia-instalacion/capturas/spyder.png?raw=true)

![spyderini](/../dalthviz-guia-instalacion/capturas/spyderIni.png?raw=true)

![spyderini2](/../dalthviz-guia-instalacion/capturas/spyderIni2.png?raw=true)


**Jupyter Notebook**

![notebook](/../dalthviz-guia-instalacion/capturas/notebook.png?raw=true)

![notebookini](/../dalthviz-guia-instalacion/capturas/notebookIni.png?raw=true)

![notebookini2](/../dalthviz-guia-instalacion/capturas/notebookIni2.png?raw=true)


## MacOS

**1.** Descargar la versión gráfica del instaldor de Anaconda asociada a la versión 3.x de Python. [Aquí encuentra la página de descarga](https://www.continuum.io/downloads#osx)

**2.** Luego de finalizada la descarga del instalador, de doble clic sobre el mismo (archivo `.pkg`), acepte el contrato de licencia y de siguiente dejando los valores por defecto.

**4.** Compruebe que tanto `Spyder` como `Jupyter Notebook` estan instalados corriendolos desde una terminal:

```
spyder
```

```
jupyter notebook
```

## Linux

**1.** Descargar la versión apropiada (32 o 64 bits) de Anaconda asociada a la versión 3.x de Python. En caso de no estar seguro de la versión de linux instalada puede descargar la versión de 32 bits sin problema. [Aquí encuentra la página de descarga](https://www.continuum.io/downloads#linux)

**2.** Desde una terminal ubicada en el directorio en donde el instalador se descargó, ejecute el siguiente comando:

```
bash <Nombre_del_instalador_descargado>.sh
```

Por ejemplo, de haber descargado la versión `4.3.1` para linux de 32 bits, el comando a ejecutar sería el siguiente:

```
bash Anaconda3-4.3.1-Linux-x86.sh
```

**3.** Siga los pasos del instalador con los valores por defecto.

**4.** Compruebe que tanto `Spyder` como `Jupyter Notebook` estan instalados corriendolos desde una terminal:

```
spyder
```

```
jupyter notebook
```

## Referencia

[Documentación de conda para instalación](https://conda.io/docs/install/full.html)
