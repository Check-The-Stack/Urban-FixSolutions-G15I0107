# Preparativos - Frontend

## Semana 1

### ✅ Setup del proyecto frontend con Vite + React
- `packageManager`: pnpm
- Dependencias: react, react-router-dom, axios, tailwindcss, postcss, autoprefixer, vite
- Tailwind configurado con content paths y directivas `@tailwind` en `index.css`
- `.env` con `VITE_API_URL=http://localhost:3001`

### ✅ Definir la estructura de rutas
- `/login` y `/register` → público
- `/cliente/*` → solo `CLIENTE`
- `/tecnico/*` → solo `TECNICO`
- `/admin/*` → solo `ADMIN`
- `ProtectedRoute` valida autenticación y rol
