# Dos Cundinamarcas, en datos

Pieza de datos del **Observatorio Amaru** sobre la salud pública de Cundinamarca: aseguramiento (EPS intervenidas, régimen subsidiado vs. contributivo), estado de la red hospitalaria pública y la distancia entre hospitales. Está hecha para que cualquiera la lea y saque su propia conclusión a partir de los datos.

## Contenido del repositorio

- **`index.html`** — la pieza completa. Es autocontenida: el logo va incrustado y los gráficos (mapa de distancias y comparativo por provincia) son SVG en el propio archivo. Solo carga las tipografías desde Google Fonts (CDN).
- **`README.md`** — este archivo.

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo, `amaru-cundinamarca-salud`).
2. Sube `index.html` y `README.md` a la rama principal (`main`).
3. En el repositorio: **Settings → Pages**.
4. En **Build and deployment → Source**, elige **Deploy from a branch**.
5. En **Branch**, selecciona `main` y la carpeta `/ (root)`. Guarda.
6. Espera 1–2 minutos. La pieza quedará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

> Si quieres una URL más corta (`https://TU-USUARIO.github.io/`), nombra el repositorio exactamente `TU-USUARIO.github.io`.

## Fuentes de los datos

Cuenta de Alto Costo (2023); DANE (población 2025 y aseguramiento por régimen); Superintendencia Nacional de Salud (liquidación de Convida, 2022; intervención de EPS); Así Vamos en Salud (cobertura y cartera hospitalaria, 2025–2026); Consejo de Estado (suspensión del Decreto 0182 de 2026); El Tiempo (hospitales en riesgo y pagos de EPS, 2026); Resolución 1020 de 2026 (MinSalud); Ley 1797 de 2016 (nombramiento de gerentes de ESE); DAFP (índice MIPG 2025); Gobernación de Cundinamarca. Distancias entre hospitales calculadas en línea recta sobre su ubicación real; por carretera son mayores.

## Nota

Elaborado en ejercicio del control social. Los datos provienen de fuentes oficiales publicadas; las preguntas planteadas son abiertas y no imputan responsabilidad a persona o entidad alguna. Establecer responsabilidades corresponde a los organismos de control. Las entidades mencionadas pueden solicitar aclaración o rectificación en condiciones de equidad (art. 20 de la Constitución).
