# Aplicación Ionic: Galería de fotos (Ionic Angular y Capacitor)

## URL 
* Para la creacion de de aplicacion vamos a guiarnos en el URL: (https://ionicframework.com/docs/angular/your-first-app)

* El repositorio está alojado en GitHub por lo cual esta alojado en esta URL: (https://github.com/Elsnight/Camara.git)

* Dirección del apk : (https://drive.google.com/drive/folders/1yVxX5yPoCYLpJ8KKSfYk_BSmLvbyjEY1)

## Cómo funciona

Después de que el usuario navega a la pestaña 2 (Fotos), puede tocar o hacer clic en el botón de la cámara para abrir la cámara del dispositivo. Después de tomar o seleccionar una foto, se almacena permanentemente en el sistema de archivos del dispositivo. Cuando el usuario vuelve a abrir la aplicación en otro momento, las imágenes fotográficas se cargan desde el sistema de archivos y se muestran nuevamente en la galería. El usuario puede tocar una foto para que se le presente la opción de eliminar la foto.

## Resumen de características
* Marco de aplicación: [Angular] (https://angular.io)
* Componentes de la interfaz de usuario: [Ionic Framework](https://ionicframework.com/docs/components)
  * Botón de cámara: [Botón de acción flotante (FAB)](https://ionicframework.com/docs/api/fab)
  * Visualización de la galería de fotos: [Grid](https://ionicframework.com/docs/api/grid)
  * Cuadro de diálogo Eliminar foto: [Hoja de acción](https://ionicframework.com/docs/api/action-sheet)
* Tiempo de ejecución nativo: [Condensador] (https://capacitor.ionicframework.com)
  * Tomar fotos: [API de la cámara] (https://capacitor.ionicframework.com/docs/apis/camera)
  * Escribir una foto en el sistema de archivos: [API del sistema de archivos](https://capacitor.ionicframework.com/docs/apis/filesystem)
  * Almacenamiento de metadatos de la galería de fotos: [API de almacenamiento] (https://capacitor.ionicframework.com/docs/apis/storage)

## Estructura del proyecto
* Tab2 (Fotos) (`src/app/tab2/`): interfaz de usuario de la galería de fotos y lógica básica.
* PhotoService (`src/app/services/photo.service.ts`): Lógica que encapsula las API de condensadores, incluida la cámara, el sistema de archivos y el almacenamiento.

## Como correr

> Nota: Se recomienda encarecidamente seguir la [guía del tutorial](https://ionicframework.com/docs/angular/your-first-app), que profundiza más, pero esta es la forma más rápida de ejecutar el aplicación

0) Instale Ionic si es necesario: `npm install -g @ionic/cli`.
1) Clona este repositorio.
2) En una terminal, cambie el directorio al repositorio: `cd photo-gallery-capacitor-ng`.
3) Instale todos los paquetes: `npm install`.
4) Ejecutar en la web: `ionic serve`.
5) Ejecutar en iOS o Android: Consulte [aquí](https://ionicframework.com/docs/building/running).
