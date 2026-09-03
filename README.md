# App Malaria — presentación de avance

Presentación de tres slides sobre el avance de **App Malaria**, una aplicación Android
de vigilancia epidemiológica para el registro de casos de malaria en zonas rurales sin
conexión (Chocó, Colombia).

**Ver la presentación:** https://yustes1704.github.io/app-malaria/

Se navega con las flechas ← → del teclado, o con los controles del pie de página.

## Contenido

| Slide | Tema |
|---|---|
| 1 | Qué es la aplicación y en qué estado va el cronograma |
| 2 | El flujograma clínico de ocho pasos y las pantallas de captura |
| 3 | Cómo funciona la sincronización offline con el servidor |

## Sobre los datos de las capturas

Las capturas de pantalla son de la aplicación real corriendo, pero **todos los datos de
paciente y de evaluador que aparecen son ficticios**, creados para probar la aplicación.
No corresponden a ninguna persona.

## Detalles técnicos

Una sola página, sin dependencias ni proceso de construcción: `index.html` lleva las
capturas incrustadas en base64 y solo pide las tipografías a Google Fonts. Se puede
abrir directamente desde el disco.
