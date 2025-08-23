
# GifsApp

Aplicación web desarrollada con Angular para buscar, visualizar y gestionar gifs animados utilizando la API de Giphy. Permite explorar tendencias, realizar búsquedas, ver historial y navegar entre diferentes categorías de gifs.

## Características principales

- **Búsqueda de gifs:** Busca gifs animados usando palabras clave.
- **Tendencias:** Visualiza los gifs más populares del momento.
- **Historial:** Accede a búsquedas recientes y gifs vistos.
- **Componentes reutilizables:** Incluye componentes como `gif-list`, `gif-list-item`, `side-menu`, entre otros.
- **Servicios:** Integración con la API de Giphy a través de servicios Angular.

## Estructura del proyecto

```
src/
	app/
		gifs/
			components/
				gif-list/
				side-menu/
			interfaces/
			mapper/
			pages/
				dashboard-page/
				gif-history/
				search-page/
				trending-page/
			services/
		shared/
	environments/
```

## Requisitos previos

- Node.js >= 18.x
- Angular CLI >= 20.x

## Instalación

1. Clona el repositorio:
	 ```bash
	 git clone https://github.com/Cantx08/gifs-app.git
	 cd gifs-app
	 ```
2. Instala las dependencias:
	 ```bash
	 npm install
	 ```

## Servidor de desarrollo

Para iniciar el servidor local:
```bash
ng serve
```
Abre tu navegador en `http://localhost:4200/`.

## Scripts útiles

- **Construir el proyecto:**
	```bash
	ng build
	```
- **Ejecutar pruebas unitarias:**
	```bash
	ng test
	```
- **Generar componentes, servicios, etc.:**
	```bash
	ng generate component nombre-componente
	ng generate service nombre-servicio
	```

## Uso de componentes

Ejemplo de uso del componente `gif-list`:
```html
<gif-list [gifs]="gifsArray"></gif-list>
```
Donde `gifsArray` es un arreglo de objetos tipo gif definido en el componente padre.

## Personalización y extensión

Puedes agregar nuevos componentes, páginas o servicios usando Angular CLI. La estructura modular facilita la extensión de funcionalidades.

## Recursos adicionales

- [Documentación Angular](https://angular.dev/)
- [API de Giphy](https://developers.giphy.com/docs/)

---
Desarrollado por Andrés Cantuña
