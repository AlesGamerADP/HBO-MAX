# HBO Max Clone

Un clon de la interfaz de HBO Max desarrollado con Flutter, que replica la experiencia de usuario de la plataforma de streaming original.

## Tecnologías Utilizadas

### Framework Principal
- **Flutter** - Framework de desarrollo multiplataforma para crear aplicaciones móviles, web y de escritorio
- **Dart** - Lenguaje de programación utilizado por Flutter

### Widgets de Flutter Utilizados

#### Layout y Estructura
- `MaterialApp` - Widget raíz que proporciona el tema Material Design
- `StatelessWidget` - Widget sin estado para componentes estáticos
- `StatefulWidget` - Widget con estado para componentes dinámicos
- `Scaffold` - Estructura básica de la pantalla con AppBar y Body
- `Container` - Widget de contenedor para layout y styling
- `Column` - Layout vertical de widgets
- `Row` - Layout horizontal de widgets
- `Stack` - Widget para superponer elementos
- `Positioned` - Posicionamiento absoluto dentro de un Stack

#### Navegación
- `BottomNavigationBar` - Barra de navegación inferior
- `PageView` - Widget para navegación por páginas deslizables
- `PageView.builder` - Constructor de páginas dinámicas
- `Navigator` - Sistema de navegación entre pantallas

#### Listas y Carouseles
- `ListView` - Lista scrollable de elementos
- `ListView.builder` - Constructor de listas dinámicas
- `SingleChildScrollView` - Scroll vertical de contenido
- `NestedScrollView` - Scroll anidado para AppBar colapsable
- `SliverAppBar` - AppBar con efectos de scroll avanzados

#### Imágenes y Medios
- `Image.network` - Carga de imágenes desde URLs
- `Image.asset` - Carga de imágenes desde assets locales
- `CachedNetworkImage` - Caché de imágenes de red (si se implementa)

#### Interacción y UI
- `GestureDetector` - Detección de gestos táctiles
- `InkWell` - Efectos de ripple en Material Design
- `FloatingActionButton` - Botón flotante
- `Icon` - Iconos de Material Design
- `Text` - Widget de texto
- `RichText` - Texto con formato avanzado

#### Responsive Design
- `LayoutBuilder` - Construcción de layout responsivo
- `MediaQuery` - Consulta de información del dispositivo
- `OrientationBuilder` - Adaptación según orientación

#### Estilos y Temas
- `Theme` - Sistema de temas de Material Design
- `ColorScheme` - Esquema de colores
- `TextTheme` - Temas de texto
- `BoxDecoration` - Decoración de contenedores
- `BorderRadius` - Bordes redondeados
- `Gradient` - Gradientes de color
- `BoxShadow` - Sombras de contenedores

#### Animaciones
- `AnimatedContainer` - Contenedor con animaciones
- `AnimatedOpacity` - Animación de opacidad
- `Hero` - Animaciones de transición entre pantallas

## Características Implementadas

### Pantallas Principales
- **HomeScreen** - Pantalla principal con contenido destacado
- **ShowDetailScreen** - Detalles de películas/series
- **PlaceholderScreen** - Pantallas de placeholder para otras secciones

### Componentes de UI
- **Carousel de Contenido Destacado** - Carrusel principal con películas destacadas
- **Carousel de Contenido** - Carruseles horizontales para diferentes categorías
- **SmartImage** - Componente inteligente para carga de imágenes
- **Navegación Adaptativa** - BottomNavigationBar para móvil, SliverAppBar para desktop

### Datos y Contenido
- **Datos de Películas** - Estructura de datos para contenido multimedia
- **Categorías** - Organización por géneros (Destacado, Popular, Acción)
- **Metadatos** - Títulos, descripciones, URLs de imágenes

## Diseño

### Paleta de Colores
- **Negro Principal** - `#000000` para fondos
- **Gris Oscuro** - `#1a1a1a` para elementos secundarios
- **Blanco** - `#ffffff` para texto principal
- **Azul HBO** - `#0066cc` para acentos (si se implementa)

### Tipografía
- **Material Design Typography** - Sistema de tipografía estándar
- **Tamaños Responsivos** - Adaptación según tamaño de pantalla

## Estructura del Proyecto

```
├── assets/
│   └── images/           # Imágenes locales
└── README.md             # Documentación del proyecto
lib/
│└── main.dart            # Archivo principal con toda la aplicación

```

## Instalación y Ejecución

### Prerrequisitos
- Flutter SDK (versión 3.0 o superior)
- Dart SDK
- Android Studio / VS Code
- Android SDK / Xcode (para desarrollo móvil)

### Pasos de Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/hbo-max-clone.git
   cd hbo-max-clone
   ```

2. **Instalar dependencias**
   ```bash
   flutter pub get
   ```

3. **Ejecutar la aplicación**
   ```bash
   flutter run
   ```

### Comandos Útiles

```bash
# Ejecutar en modo debug
flutter run

# Ejecutar en modo release
flutter run --release

# Ejecutar análisis de código
flutter analyze

# Ejecutar tests
flutter test

# Limpiar proyecto
flutter clean
```

## Plataformas Soportadas

- ✅ **Android** - Soporte completo
- ✅ **iOS** - Soporte completo  
- ✅ **Web** - Soporte completo
- ✅ **Windows** - Soporte completo
- ✅ **macOS** - Soporte completo
- ✅ **Linux** - Soporte completo

## 🔧 Configuración Adicional

### Assets
Asegúrate de tener las imágenes en la carpeta `assets/images/`:
- `avatar.jpg`
- `fastandfurious.jpg`
- `kimetsu.jpg`

### Permisos
Para desarrollo web, no se requieren permisos especiales. Para móvil, asegúrate de tener configurados los permisos de red para cargar imágenes.

## Licencia

Este proyecto es solo para fines educativos y de demostración. HBO Max es una marca registrada de Warner Bros. Discovery.

## Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## Contacto

Si tienes preguntas o sugerencias, no dudes en contactarme o abrir un issue en el repositorio.

---

**Nota**: Este es un proyecto de demostración creado con fines educativos. No está afiliado oficialmente con HBO Max o Warner Bros. Discovery.
