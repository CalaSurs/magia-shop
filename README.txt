# Magia Shop — GitHub Pages

Archivos listos para publicar en **GitHub Pages**.

## Pasos rápidos
1. Crea un repositorio público (por ejemplo `magia-shop`) en tu cuenta de GitHub.
2. Sube **index.html** y **CNAME** (este último con el texto `magia.lol`).
3. Ve a **Settings → Pages** y elige:
   - *Build and deployment* → **Source: Deploy from a branch**
   - **Branch: main** y **/ (root)**
4. Espera a que se publique y luego en la misma pantalla establece **Custom domain: magia.lol** y marca **Enforce HTTPS**.

## DNS en tu registrador (Spaceship)
Crea estos registros en la zona DNS de `magia.lol`:
- 4 registros **A** para el dominio raíz (host `@`), apuntando a:
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153
- 1 registro **CNAME** para `www` apuntando a `<tu-usuario>.github.io`

> Después de guardar, espera la propagación (minutos a horas).

## Personalización
- Edita enlaces a Discord (`https://discord.gg/magia`) directamente en `index.html`.
- Cambia textos, secciones o colores si quieres.
