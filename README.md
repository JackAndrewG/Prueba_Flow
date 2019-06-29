# Título del Proyecto
Prueba de integracion GitKraken con git-flow
<img src="http://icons.iconarchive.com/icons/papirus-team/papirus-apps/256/gitkraken-icon.png">
## Comenzando 🚀

_Clonar el proyecto_
```
git clone https://github.com/JackAndrewG/Prueba_Flow.git
```

### Pre-requisitos 📋
* Instalar git
* instalar Gitkraken
* instalar git-flow (en caso de no tenerlo) 

### Instalacion
_se necesita tener instalado lo siguiente:_
#### git:
_Linux:_
``` 
apt-get install git
```

_Windows:_ 
```
http://msysgit.github.com/
```

_Mac:_
```
http://sourceforge.net/projects/git-osx-installer/
```

#### GitKraken:
_Linux, Windows, Mac:_ 
```
https://www.gitkraken.com/
```

#### git-flow:
Contar con git e integrar
_Linux:_ 
```
apt-get install git-flow
```

_Windows:_  
```
git flow init
```

_Mac:_ 
```
brew install git-flow
```

### integracion GitHub

Conenctar GitHub con GitKraken: 
1. Ir a Preferences 
2. Luego a Autenthication 
3. Seleccionar GitHub.com 
4. Dar click en Connect to GitHub

## Ejecutando las pruebas ⚙️
#### Uso de ramas con GitKraken: 
_Feature_
* Nos aseguramos de que estamos sobre la rama develop
* Abrimos el menu [Git Flow](#gitflow)
* En la sección start, clic en Feature
* Se asigna un nombre a la rama
* Clic en Start Feature
* Realizamos los cambios sobre esta rama
* Cuando hayamos acabado todos los cambios previstos para esta rama cerramos esta rama

_Release_
* Nos aseguramos de que estamos sobre la rama develop
* Abrimos el menu [Git Flow](#gitflow)
* En la sección start, clic en Release
* Se asigna un nombre a la rama indicando su version
* Clic en Start Release
* Realizamos los cambios sobre esta rama
* Cuando hayamos acabado todos los cambios previstos para esta rama cerramos esta rama

_Hotfix_
* Nos aseguramos de que estamos sobre la rama master
* Abrimos el menu [Git Flow](#gitflow)
* En la sección start, clic en Hotfix
* Se asigna un nombre a la rama
* Clic en Start Hotfix
* Realizamos los cambios sobre esta rama
* Cuando hayamos acabado todos los cambios previstos para esta rama cerramos esta rama

_Finalizar una rama_
* Nos aseguramos de que estamos sobre la rama que deseamos finalizar
* Abrimos el menu [Git Flow](#gitflow)
* En la sección finish, se mostrara como sugerencia finalizar la rama sobre la que estamos trabajando
* Clic en Finish feature || realease || hotfix

<img  id="gitflow" src="/DeepinScreenshot_select-area_20190628205742.png">

### Analice las pruebas end-to-end 🔩

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

### Y las pruebas de estilo de codificación ⌨️

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

## Deployment 📦

* [Iniciar git Gitkraken
* [Ingresar con las credenciales del repositorio
* En la sección de Repository Managament tomar la opción clone
* Elegir la ruta donde se clonara el proyecto y la url del proyecto
* Abrir el proyecto clonado y hacer cambios

### Construido con 🛠️
_Mencion a las herramientas que se utilizaron para crear el proyecto_
* [GitKraKen](https://www.gitkraken.com/) - Potente y elegante interfaz gráfica multiplataforma para git desarrollada con Electron
* [GitHub](https://github.com/github) - Plataforma de desarrollo colaborativo
* [GitFlow](https://datasift.github.io/gitflow/IntroducingGitFlow.html/) - Extensiones de git que facilitan la gestión de ramas y flujos de trabajo.
* [Git](https://git-scm.com/) -  Control de versiones

## Contribuyendo 🖇️
Por favor lee el [CONTRIBUTING.md](https://gist.github.com/JackAndrewG/Prueba_Flow.git) para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

## Wiki 📖
Puedes encontrar mucho más de cómo utilizar este proyecto en nuestra [Wiki](https://github.com/JackAndrewG/Prueba_Flow/wiki)

## Versionado 📌
Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/JackAndrewG/Prueba_Flow/tags).


## Autores ✒️
* **Jackson Guzmán** - *Trabajo Inicial* - [JackAndrewG](https://github.com/JackAndrewG)
* **Jimmy Vicente** - *Implementación* - [JimmyVicente](https://github.com/JimmyVicente)
* **Albert Mora** - *Integración con GitHub y Autores* - [albert1299](https://github.com/albert1299)
* **Deiby Calva** - *Corrección de errores* - [DeibyCalva](https://github.com/DeibyCalva)
