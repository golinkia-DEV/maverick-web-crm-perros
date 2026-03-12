# Despliegue del proyecto

## Subir a GitHub

1. Crea un repositorio nuevo en [GitHub](https://github.com/new) (p. ej. `web-crm-perros` o `mi-web-crm-perros`).
2. En la carpeta del proyecto ejecuta:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/web-crm-perros.git
git push -u origin main
```

(Sustituye `TU_USUARIO` y el nombre del repo por los tuyos.)

## Desplegar en Vercel

### Opción A: Desde la web (recomendado)

1. Entra en [vercel.com](https://vercel.com) e inicia sesión.
2. **Add New** → **Project** → importa el repositorio de GitHub.
3. Vercel detectará el framework (Vite, React, etc.). Pulsa **Deploy**.

### Opción B: Desde la terminal

```bash
npm i -g vercel
vercel login
vercel --prod
```

Responde a las preguntas (nombre del proyecto, carpeta raíz). La URL de producción quedará en `https://tu-proyecto.vercel.app`.

---

Carpeta del proyecto: `/app/salida_fabrica/proyectos/web-crm-perros`
