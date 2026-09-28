# Unidad 5: Cómo conectarse a Internet

Repositorio con los entregables de las 2 rutas de aprendizaje de la Unidad 5 del curso. Ambas rutas se desarrollan sobre el mismo proyecto, Mars Photos, que va evolucionando de una ruta a la otra.

## Estructura del repositorio

```
├── Ruta1_DatosInternet/
│   └── MarsPhotosApp/       (Retrofit, corrutinas, repositorio e inyección de dependencias)
│
└── Ruta2_ImagenesInternet/
    └── LEER.txt             (misma app que la Ruta 1 — se le agrega Coil encima)
```

## Ruta 1 — Cómo obtener datos de Internet

**MarsPhotosApp**: app que se conecta a un servicio web para obtener fotos reales de la superficie de Marte tomadas por los rovers de la NASA. Cubre:
- Corrutinas de Kotlin para realizar tareas de red sin bloquear la interfaz.
- HTTP y REST, usando `Retrofit` para conectarse al servidor y obtener los datos.
- La capa de datos: un repositorio que centraliza el acceso a los datos, separándolo del ViewModel.
- Inyección de dependencias manual, para desacoplar las clases y facilitar las pruebas.

## Ruta 2 — Cómo cargar y mostrar imágenes de Internet

Continúa sobre el mismo proyecto **MarsPhotosApp** (ver `Ruta1_DatosInternet/MarsPhotosApp/`). Se le agrega:
- La biblioteca `Coil` para cargar imágenes directamente desde su URL.
- Una cuadrícula (`LazyVerticalGrid`) que muestra todas las fotos de Marte obtenidas del servidor.

## Autor

Mario Huarcaya — Ingeniería de Sistemas

## Curso

Cómo conectarse a Internet — Unidad 5