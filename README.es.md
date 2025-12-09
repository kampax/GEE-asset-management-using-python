# Google Earth Engine - Asset Management usando Python

Debido a la dificultad que encontré en el manejo de assets en Google Earth Engine (GEE), he organizado una colección completa de herramientas para gestionar assets en Google Earth Engine (GEE), incluyendo operaciones de copia y eliminación de imágenes, tablas, colecciones y estructuras de carpetas completas.

## Descripción

Este toolkit proporciona funciones optimizadas para realizar operaciones comunes de gestión de assets en Google Earth Engine:

- Copiar imágenes, tablas y colecciones individuales
- Copiar estructuras de carpetas completas de forma recursiva
- Eliminar assets individuales o en lote
- Eliminar estructuras completas con todas sus dependencias
- Migrar datos entre cuentas de usuario y proyectos
- Crear backups y reorganizar estructuras de datos

## Características

- **Operaciones parametrizadas**: Define tus rutas de usuario y proyecto una sola vez al inicio
- **Funciones recursivas**: Maneja estructuras complejas automáticamente
- **Feedback visual**: Mensajes de progreso y barras de estado con tqdm
- **Seguro por diseño**: Código de eliminación comentado para prevenir borrados accidentales

## Requisitos Previos

### Cuenta de Google Earth Engine
- Debes tener una cuenta activa en [Google Earth Engine](https://earthengine.google.com/)
- Asegúrate de tener permisos adecuados para leer y escribir en las rutas de assets que usarás

## Limitaciones y Consideraciones

### Cuotas y Límites de GEE

- **Límites de API**: GEE limita el número de operaciones por minuto
- **Almacenamiento**: Cada cuenta tiene límites de almacenamiento
- **Operaciones simultáneas**: No realizar demasiadas operaciones en paralelo

### Recomendaciones

1. **Prueba con datos pequeños primero**: Antes de operaciones masivas
2. **Haz backups**: Siempre antes de eliminar datos importantes
3. **Verifica permisos**: Asegúrate de tener acceso a origen y destino
4. **Monitorea el progreso**: Usa las funciones con feedback visual
5. **Paciencia con grandes volúmenes**: Las operaciones pueden tomar tiempo


### Recursos Oficiales de GEE

- [Documentación oficial de Earth Engine](https://developers.google.com/earth-engine)
- [Guía de gestión de assets](https://developers.google.com/earth-engine/guides/asset_manager)
- [Foro de la comunidad](https://groups.google.com/g/google-earth-engine-developers)
- [API Reference](https://developers.google.com/earth-engine/apidocs)

