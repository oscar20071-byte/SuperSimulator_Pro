# SuperSimulator_Pro

Simulador de fútbol independiente, desarrollado como aplicación web estática para GitHub Pages.

## Ejecutar
Abre \`index.html\` en un navegador moderno. No requiere instalación ni servidor.

## Publicar con GitHub Pages
1. En el repositorio, abre **Settings → Pages**.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Selecciona la rama \`main\` y la carpeta \`/ (root)\`.
4. Guarda los cambios y espera a que termine la publicación.

## Funciones
- Crear y eliminar clubes.
- Añadir jugadores con posición, dorsal y media individual.
- Calcular la media del club desde su plantilla.
- Simular partidos y registrar goleadores.
- Crear ligas y copas eliminatorias.
- Consultar clasificaciones y estadísticas.
- Guardar datos en el navegador y exportar/importar copias JSON.

## Importante
Los datos se guardan localmente en el navegador; no se sincronizan automáticamente entre usuarios. Esta versión no incluye autenticación real ni roles administrativos seguros. No introduzcas contraseñas, tokens ni claves privadas en el código frontend.

## Archivos
- \`index.html\`: estructura de la aplicación.
- \`styles.css\`: diseño responsive.
- \`app.js\`: lógica de clubes, competiciones y simulación.
