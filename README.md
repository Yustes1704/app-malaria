# App Malaria — presentaciones

**App Malaria** es una aplicación Android de vigilancia epidemiológica para el registro
de casos de malaria en zonas rurales sin conexión.

Este repositorio publica dos presentaciones sobre ella. Las dos se navegan con las flechas
← → del teclado, o con los controles del pie de página.

## 1. Avance del proyecto — 3 slides

https://yustes1704.github.io/app-malaria/

Para un público que ya conoce el proyecto: en qué estado va y cómo se ve la aplicación.

| Slide | Tema |
|---|---|
| 1 | Qué es la aplicación y en qué estado va el cronograma |
| 2 | El flujograma clínico de ocho pasos y las pantallas de captura |
| 3 | Cómo funciona la sincronización offline con el servidor |

## 2. Cómo se construye una app — 8 slides

https://yustes1704.github.io/app-malaria/como-se-hizo/

Para un público sin formación técnica: qué hace falta para llevar un dato tomado en
campo hasta un servidor. Cada término técnico va acompañado de su equivalente en la
práctica clínica.

| Slide | Tema |
|---|---|
| 1 | De la vereda al servidor |
| 2 | Una app no es una pantalla: son tres piezas |
| 3 | Los primeros dos meses no se escribe código |
| 4 | El formato del dato, lo más parecido a una historia clínica |
| 5 | Se dibuja antes de construir |
| 6 | La app tenía que funcionar sin señal |
| 7 | Cómo llega el caso al servidor |
| 8 | Un año, y la mitad no es programar |

## Sobre los datos de las capturas

Las capturas de pantalla son de la aplicación real corriendo, pero **todos los datos de
paciente y de evaluador que aparecen son ficticios**, creados para probar la aplicación.
No corresponden a ninguna persona.

## Detalles técnicos

Cada presentación es una sola página, sin dependencias ni proceso de construcción:
el `index.html` lleva las capturas incrustadas en base64 y solo pide las tipografías a
Google Fonts. Se pueden abrir directamente desde el disco.
