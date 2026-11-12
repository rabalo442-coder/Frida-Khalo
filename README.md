# 🏛️ Museo Inmersivo Frida Kahlo — Noche de los Museos

Una experiencia web inmersiva e interactiva inspirada en la Casa Azul de Coyoacán, diseñada para explorar las obras maestras y el universo íntimo de Frida Kahlo.

## ✨ Características Inmersivas

- **Atmósfera & Estética Fanzine:** Paleta de colores auténtica (Azul Casa Azul, Terracota oaxaqueño, Grana Cochinilla y tonos papel artesanal) con efecto de reflector que sigue el cursor.
- **Sala 01 — El Refugio de la Cama (POV Interactivo):**
  - Vista en primera persona desde el lecho de Frida mirando hacia el dosel.
  - Espejo superior con reflejo dinámico y puntos de interés (hotspots) para examinar el atril, el espejo y sus pigmentos.
  - Movimiento por arrastre de ratón y soporte táctil en móviles.
- **Sala 02 — Las Dos Fridas (Dualidad e Identidad):**
  - Presentación comparativa entre la Frida amada de traje tradicional y la Frida europea con el corazón expuesto.
  - Generador de audio de latidos cardíacos mediante **Web Audio API** (sin dependencias ni enlaces caídos).
- **Sala 03 — La Columna Rota (Examen Clínico-Artístico):**
  - Visor interactivo con pines numéricos que revelan los 4 pilares de la obra: la columna jónica, los clavos, el corsé ortopédico y las lágrimas blancas.
- **Sala 04 — Muro de Reflexiones / Fanzine Colectivo:**
  - Libro de visitas en vivo que permite a cada usuario dejar sus impresiones con persistencia en `localStorage`.
- **Motor de Audio Autónomo:**
  - Acordes ambientales sintetizados en tiempo real y narración curatorial con voz en español (`SpeechSynthesis`).

---

## 🚀 Cómo subirlo a GitHub y desplegarlo en Vercel

### Paso 1: Subir a GitHub
1. Ve a [GitHub](https://github.com) y crea un nuevo repositorio (por ejemplo: `museo-frida-kahlo`).
2. Abre tu terminal en esta carpeta (`museo-frida-kahlo`) y ejecuta:
```bash
git init
git add .
git commit -m "feat: Museo Inmersivo Frida Kahlo"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/museo-frida-kahlo.git
git push -u origin main
```
*(También puedes simplemente arrastrar los archivos directamente en la web de GitHub en "Upload files")*.

### Paso 2: Desplegar en Vercel (Totalmente Gratis)
1. Entra a [Vercel](https://vercel.com) e inicia sesión con tu cuenta de GitHub.
2. Haz clic en **"Add New..."** -> **"Project"**.
3. Selecciona tu repositorio `museo-frida-kahlo`.
4. Deja la configuración por defecto (como es un proyecto HTML estático no requiere pasos de compilación) y haz clic en **Deploy**.
5. ¡Listo! Vercel te dará una URL pública con HTTPS (ej. `museo-frida-kahlo.vercel.app`) en menos de 30 segundos.
