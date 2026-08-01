# 🚀 Guía para Publicar en GitHub Pages

¡Tu landing page premium para **CobroFácil** ya está lista! Sigue estos pasos para subirla a internet completamente gratis con GitHub Pages:

---

## Paso 1: Copiar el APK de la App
Para que tus usuarios puedan descargar la app directamente desde tu web:
1. Copia tu archivo APK compilado (`app-arm64-v8a-release.apk` o el que prefieras que descarguen por defecto).
2. Pégalo dentro de la carpeta `c:\Users\SistemasDaniel\Documents\cobrofacil_web\`.
3. Renómbralo exactamente a: **`app-release.apk`**.

---

## Paso 2: Crear el Repositorio en GitHub
1. Entra a tu cuenta en [GitHub](https://github.com).
2. Crea un **nuevo repositorio** público.
3. Nómbralo como quieras (por ejemplo: `cobrofacil` o `cobrofacil-web`).
4. **No** le agregues archivo README, .gitignore ni licencia (déjalo vacío).

---

## Paso 3: Subir el Código desde la Terminal
Abre tu consola/terminal en la carpeta `c:\Users\SistemasDaniel\Documents\cobrofacil_web\` y ejecuta los siguientes comandos:

```bash
# 1. Inicializar git en la carpeta
git init

# 2. Agregar todos los archivos (HTML, CSS, assets y el APK)
git add .

# 3. Confirmar la subida
git commit -m "First commit: landing page de CobroFácil"

# 4. Cambiar el nombre de la rama principal a main
git branch -M main

# 5. Enlazar con tu repositorio de GitHub (reemplaza con tu URL real)
git remote add origin https://github.com/SistemasDaniel/TU_REPOSITORIO.git

# 6. Subir los archivos a GitHub
git push -u origin main
```

---

## Paso 4: Activar GitHub Pages
Una vez subidos los archivos:
1. Entra a tu repositorio en GitHub desde el navegador.
2. Haz clic en la pestaña **Settings** (Configuración) arriba a la derecha.
3. En el menú de la izquierda, busca la sección **Pages**.
4. En **Build and deployment**, bajo **Source**, selecciona **Deploy from a branch**.
5. En **Branch**, selecciona **`main`** y la carpeta **`/ (root)`**.
6. Haz clic en **Save** (Guardar).

¡Y listo! En 1 o 2 minutos, GitHub te dará un enlace público (tipo `https://SistemasDaniel.github.io/TU_REPOSITORIO/`) donde cualquier persona del mundo podrá ver tu landing page y descargar tu aplicación móvil de forma directa. 🎉
