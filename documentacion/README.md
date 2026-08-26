# Stock de Peces de Colores

Aplicación web sencilla, sin servidor ni base de datos externa. Los datos se guardan en `localStorage` del navegador.

## Funciones
- Alta, edición y eliminación de peces.
- Registro de denominación, descripción, origen, fechas, persona y estado.
- Alta, edición y eliminación de personas.
- Asignación de peces a personas.
- Búsqueda por denominación o descripción.
- Filtro por origen: marino o río.
- Consulta de entregas y estado actual.
- Imágenes locales de ejemplo en `img/`.

## Uso
1. Abrir `index.html` en el navegador. También puede ejecutarse con VS Code + Live Server.
2. Registrar primero las personas, si se desea asignar un pez inmediatamente.
3. Registrar el pez.
4. Cuando se selecciona una persona, el sistema marca automáticamente el pez como `Entregado`.
5. Los datos permanecen guardados en el navegador utilizado.

## Estructura
```text
stock_peces/
├── index.html
├── css/
│   └── estilos.css
├── js/
│   └── app.js
├── img/
│   ├── pez-payaso.svg
│   ├── pez-betta.svg
│   ├── pez-guppy.svg
│   └── pez-generico.svg
└── documentacion/
    └── README.md
```
