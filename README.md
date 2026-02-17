# CV Web de Carlos Arcas

Este repositorio contiene el **CV web estático de Carlos Arcas**, construido únicamente con **HTML + CSS**.

## Objetivo del proyecto

Crear un currículum online:
- visualmente atractivo,
- fácil de mantener,
- y optimizado para lectura por ATS/IA gracias a una estructura semántica y contenido textual real.

## Estructura del proyecto

- `index.html`: página principal del CV (entry file en GitHub Pages).
- `styles.css`: estilos del CV, incluyendo (más adelante) estilos de impresión.
- `assets/`: carpeta reservada para recursos locales futuros.

## Cómo cambiar los placeholders `TU_USUARIO`

En el proyecto encontrarás enlaces de ejemplo usando `TU_USUARIO` (por ejemplo en URLs de GitHub o LinkedIn). Para personalizarlos:

1. Abre los archivos donde aparezca `TU_USUARIO` (normalmente `index.html` y/o `README.md`).
2. Reemplaza `TU_USUARIO` por tu nombre real de usuario en cada plataforma.
3. Guarda los cambios y verifica que los enlaces funcionan correctamente.

## Publicar en GitHub Pages (Deploy from a branch)

Sigue estos pasos en tu repositorio de GitHub:

1. Ve a **Settings**.
2. En el menú lateral, entra en **Pages**.
3. En **Source**, selecciona **Deploy from a branch**.
4. En **Branch**, selecciona:
   - Rama: `main`
   - Carpeta: `/(root)`
5. Guarda la configuración.

> **Nota:** GitHub Pages utiliza `index.html` como archivo de entrada cuando está en la carpeta publicada.

## Ver el proyecto en local

Opciones recomendadas:

- **Rápido:** haz doble clic en `index.html` para abrirlo en el navegador.
- **Opcional (servidor simple):** puedes usar un servidor local para simular mejor el entorno web.

Ejemplo con Python:

```bash
python3 -m http.server 8000
```

Luego abre: `http://localhost:8000`

## Exportar a PDF

Cuando el CSS de impresión esté listo, podrás exportar el CV fácilmente:

1. Abre el CV en el navegador.
2. Pulsa **Ctrl + P** (o **Cmd + P** en macOS).
3. Elige **Guardar como PDF**.
4. Ajusta opciones de impresión si hace falta (márgenes, escala, fondos, etc.).
