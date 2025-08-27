📚 BookFinder - Buscador de Libros
Una aplicación móvil híbrida desarrollada con Ionic que permite buscar libros, ver detalles y gestionar una lista de favoritos.

✨ Características
🔍 Búsqueda en tiempo real de libros usando Google Books API

📖 Vista de detalles completa con información del libro

❤️ Sistema de favoritos con almacenamiento local

📱 Interfaz responsive optimizada para móviles

🎨 Diseño moderno con animaciones fluidas

🛠️ Tecnologías Utilizadas
Ionic Framework (v6+)

Angular (v13+)

Ionic Storage (para persistencia de datos)

Google Books API

Capacitor (para build nativo)

📦 Instalación
Prerrequisitos
Node.js (v14 o superior)

npm o yarn

Ionic CLI: npm install -g @ionic/cli

Pasos de instalación
Clona el repositorio:

git clone <url-del-repositorio>
cd bookfinder
Instala las dependencias:

npm install
Instala las dependencias nativas necesarias:
npm install @ionic/storage-angular
Ejecuta la aplicación en modo desarrollo:
ionic serve
📱 Build para Dispositivos
Android

ionic capacitor add android
ionic capacitor copy android
ionic capacitor run android
iOS

ionic capacitor add ios
ionic capacitor copy ios
ionic capacitor run ios
🧩 Componentes Principales
BooksService
Servicio que gestiona:

Conexión con Google Books API

Almacenamiento local de favoritos

Estado de la aplicación

HomePage
Página principal con:

Barra de búsqueda con sugerencias

Lista de resultados

Estados de carga y error

DetailsPage
Página de detalles que muestra:

Información completa del libro

Botón para añadir/eliminar de favoritos

Metadatos (fecha publicación, editorial, etc.)

FavoritesPage
Página que muestra:

Lista de libros guardados como favoritos

Opción para eliminar favoritos individualmente

Mensaje cuando no hay favoritos

🔌 API Utilizada
La aplicación utiliza la Google Books API para:

Búsqueda de libros por término

Obtención de detalles completos

Imágenes de portadas

💾 Almacenamiento
Los favoritos se guardan localmente usando @ionic/storage-angular, que provee:

Persistencia de datos entre sesiones

Soporte para múltiples motores de almacenamiento

API simple basada en clave-valor
📞 Soporte
Si encuentras algún problema o tienes preguntas:

Revisa la documentación de Ionic

Busca en los issues existentes

Abre un nuevo issue con detalles del problema

🔄 Próximas Mejoras
Sincronización con Firebase para multi-dispositivo

Modo offline para ver favoritos sin conexión

Recomendaciones basadas en favoritos

Compartir libros en redes sociales

Sistema de valoraciones y reseñas

<img width="512" height="828" alt="image" src="https://github.com/user-attachments/assets/105f3bde-5c31-40ad-b8dd-405547b8358c" />

<img width="395" height="832" alt="image" src="https://github.com/user-attachments/assets/4a2beb5d-4dbd-4eb1-8743-1a894dec3fa4" />
<img width="395" height="832" alt="image" src="https://github.com/user-attachments/assets/521b1e5e-9b8e-47c2-a092-184f48426e38" />
<img width="395" height="832" alt="image" src="https://github.com/user-attachments/assets/4010c2d2-aea4-4d45-b738-ab408e3b24c2" />



