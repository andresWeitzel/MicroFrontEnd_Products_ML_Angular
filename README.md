# MicroFronEnd_Products_ML_Angular
Aplicación Web MicroFrontEnd para la gestión de Productos de ML implementada con Angular, Angular Material, Bootstrap, Html5, Scss, Highcharts, Git y Otras Tecnologías.
* [Repositorio Microdb_MercadoLibre_Productos_Mysql](https://github.com/andresWeitzel/Microdb_MercadoLibre_Productos_Mysql)
* [Repositorio Api Rest Microservice_Mercadolibre_Products_AWS](https://github.com/andresWeitzel/Microservice_Mercadolibre_Products_AWS)
* [Api Doc ML Productos](https://developers.mercadolibre.com.ar/es_ar/publica-productos)



<br>

## Índice 📜

<details>
 <summary> Ver </summary>
 
 <br>
 
### Sección 1) Descripción, configuración y tecnologías.

 - [1.0) Descripción del Proyecto.](#10-descripción-)
 - [1.1) Ejecución del Proyecto.](#11-ejecución-del-proyecto-)
 - [1.2) Configuración del proyecto desde cero](#12-configuración-del-proyecto-desde-cero-)
 - [1.3) Tecnologías.](#13-tecnologías-)
 - [1.4) Comandos útiles para Angular-cli.](#14-comandos-útiles-para-angular-cli)

### Sección 2) Endpoints y Ejemplos 
 
 - [2.0) EndPoints y recursos.](#20-endpoints-y-recursos-)
 - [2.1) Ejemplos.](#21-ejemplos-)
 
### Sección 3) Prueba de funcionalidad y Referencias
 
 - [3.0) Prueba de funcionalidad.](#30-prueba-de-funcionalidad-)
 - [3.1) Referencias.](#31-referencias-)
	 

<br>

</details>



<br>

## Sección 1) Descripción, configuración y tecnologías. 


### 1.0) Descripción [🔝](#índice-) 

<details>
  <summary>Ver</summary>

 <br>

### 1.0.0) Descripción General


 ### 1.0.1) Descripción Arquitectura y Funcionamiento
 

<br>

</details>


### 1.1) Ejecución del Proyecto [🔝](#índice-)

<details>
  <summary>Ver</summary>
<br>
 
* Instalamos la última versión LTS de [Nodejs(v18)](https://nodejs.org/en/download)
* Instalamos la cli de angular de forma global si es que no está aún instalado.
```git
npm install -g @angular/cli
```
* Una vez creado un entorno de trabajo a través de algún ide, clonamos el proyecto
```git
git clone https://github.com/andresWeitzel/MicroFrontEnd_Products_ML_Angular
```
* Nos posicionamos sobre el proyecto
```git
cd 'nombreProyectoSinComillas'
```
* Instalamos todas las dependencias necesarias
```git
npm i
```
* Ejecutar la base de datos
* Ejecutar la api rest
* Ejecutar el proyecto
```git
ng serve 
```
* La app se deploya en http://localhost:4200/
<br>

</details>


### 1.2) Configuración del proyecto desde cero [🔝](#índice-)

<details>
  <summary>Ver</summary>
 
 <br>
 
  
* Creamos un entorno de trabajo a través de algún ide, luego de crear una carpeta nos posicionamos sobre la misma o la abrimos con vsc
```git
cd 'projectName'
```
* Instalamos la última versión LTS de [Nodejs(v18)](https://nodejs.org/en/download)
* Instalamos la cli de angular de forma global.
```git
npm install -g @angular/cli
```
* Creamos la app (nos apareceran unas opciones de config, aceptamos crear routing y para estilos elegimos scss)
```git
ng new 'nombreProyectoSinComillas'
```
* Usaremos [git](https://www.hostinger.com.ar/tutoriales/instalar-git-en-distintos-sistemas-operativos) como control de versiones. Nos posicionamos en la app e inicializamos git
```git
git init
```
* Creamos el repositorio en github (sin readme) y agregamos la url del repositorio creado (ej: la siguiente)
```git
git remote add origin https://github.com/andresWeitzel/MicroFrontEnd_Products_ML_Angular
```
* Traemos los cambios del remoto, agregamos los nuevos cambios en local, commitiamos y los subimos al repo.
```git
git pull origin master
git add *
git commit -m "Create Angular app"
git push origin
```
* Ejecutamos la app inicial
```git
ng serve
```
* Ya tenemos una app funcional con una estructura inicial definida por Angular. La aplicación queda deployada en http://localhost:4200/
* `Aclaración` : El resto de las modificaciones aplicadas sobre la plantilla inicial, no se describen por temas de simplificación de doc. Para más info consultar el tutorial de [Creación Angular App](https://docs.angular.lat/tutorial/toh-pt0) para el uso de componentes, rutas, etc.


<br>

</details>




### 1.3) Tecnologías [🔝](#índice-)

<details>
  <summary>Ver</summary>


 <br>
	
</br>


| **Plugin** | 
| -------------  |
| |


</br>

| **Extensión** |              
| -------------  | 
| Prettier - Code formatter |

<br>

</details>



### 1.4) Comandos útiles para Angular-cli [🔝](#índice-)

<details>
  <summary>Ver</summary>
<br>

* Creación de módulos con routing (páginas) 
```git
ng g m pages/products/products-list --module app --route products-list
```
* Creación de componentes con modulo
```git
ng g c components/navbar --module app
ng g m components/navbar --module app
```


<br>

</details>


<br>

## Sección 2) Endpoints y Ejemplos. 


### 2.0) Endpoints y recursos [🔝](#índice-) 

<details>
  <summary>Ver</summary>

<br>

</details>




### 2.1) Ejemplos [🔝](#índice-) 

<details>
  <summary>Ver</summary>
<br>


<br>

</details>



<br>


## Sección 3) Prueba de funcionalidad y Referencias. 


### 3.0) Prueba de funcionalidad [🔝](#índice-) 

<details>
  <summary>Ver</summary>

<br>

<br>

</details>


### 3.1) Referencias [🔝](#índice-)

<details>
  <summary>Ver</summary>
 
 <br>

#### Documentación

#### Herramientas 
* [Fondos de pantallas unsplash](https://unsplash.com/it)



<br>

</details>


