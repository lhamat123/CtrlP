# LHAMAT Ctrl+P 🖨️

Gestor de impresoras — datos en GitHub, sin backend ni Supabase.

## Setup en 3 pasos

### 1 — Subir a GitHub
1. Crea repo `lhamat-ctrlp` en tu cuenta
2. Sube `index.html`, `data.json`, `README.md`
3. Settings → Pages → Source: main → Save
4. App en: `https://lhamat123.github.io/lhamat-ctrlp/`

### 2 — Cambiar contraseña en index.html
```js
const APP_PASS = 'admin1234';  // ← cambia esto
```

### 3 — Crear Personal Access Token
GitHub → Settings → Developer settings → Fine-grained tokens → New token
- Repo: lhamat-ctrlp
- Permission: Contents → Read and write
- Copia el token (lo usas al hacer login)

## Login
Clic en 🔐 Entrar → contraseña → pega el token → listo.

## Archivos
- `index.html` — la app
- `data.json` — la base de datos
