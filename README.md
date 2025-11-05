# Portafolio — Página estática

Página simple en HTML/CSS para mostrar tus experiencias como administrador/manager/desarrollador en servidores.

Archivos principales:
- `index.html` — Página principal.
- `styles.css` — Estilos.

Cómo abrir en Windows (PowerShell):

- Doble clic en `index.html` para abrir en tu navegador por defecto.
- O desde PowerShell puedes ejecutar:

```powershell
Start-Process index.html
```

Siguientes pasos recomendados:
- Rellenar las descripciones por servidor.
- Añadir imágenes o iconos de los servidores.
- Si quieres publicar en GitHub Pages, crea un repositorio y sube estos archivos.

Nota: ya apliqué el enlace de invitación para `nexgeneration` (https://discord.gg/Kjbt7aUGJq). También puedes reemplazar el placeholder `assets/nexgeneration.svg` por la imagen real que adjuntaste (recomiendo nombrarla `assets/nexgeneration.png` o `assets/nexgeneration.jpg`).

Pasos rápidos para publicar en GitHub Pages (PowerShell):

1. Inicializa el repo local si aún no lo has hecho (desde la carpeta del proyecto):

```powershell
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO-NAME.git
git push -u origin main
```

2. Habilitar GitHub Pages desde la configuración del repo: en GitHub, ve a Settings → Pages y selecciona la rama `main` y carpeta `/ (root)`.

Opcional: crear un workflow para desplegar automáticamente en `gh-pages` (puedo agregar uno si quieres).

Archivos de imagen esperados por la página (puedes arrastrar/soltar en `assets/` con estos nombres):

 - `assets/nexgeneration.svg` (ya existe)
 - `assets/la_cueva_de_quillo.png`  ← imagen 1 que indicaste
 - `assets/illuminati.gif`         ← imagen 2 (GIF)
 - `assets/redcraft.png`           ← imagen 3
 - `assets/el_sotano_de_imkodo.png`← imagen 4
 - `assets/thecrafting.png`        ← imagen 5
 - `assets/el_bitsonico.png`       ← imagen 6
 - `assets/profile.gif`            ← avatar GIF (última imagen que me mandaste)

Si quieres, puedo añadirlas yo ahora: confirma y guardaré cada adjunto en la ruta correspondiente y actualizaré la referencia (ya están referenciadas en `index.html`).

Asunción sobre orden: he ordenado los servidores de más importante a menos importante así:
1. `nexgeneration` (Fundador + Developer)
2. `La cueva de quillo` (Administrador)
3. `ILLUMINATI` (Administrador)
4. `Redcraft` (Administrador)
5. `El BitSonico Community` (Manager + Developer)
6. `El sotano de ImKodo` (Manager)
7. `TheCrafting community` (Manager)

Si quieres otro criterio de orden (por antigüedad, por impacto o por horas dedicadas), dime y lo ajusto.