# 🗼 Spectrum Kong — Fight the Interference King

**Spectrum Kong** es un juego retro arcade inspirado en Donkey Kong, creado para la comunidad WISP (Wireless Internet Service Providers).

Juegas como un técnico WISP escalando torres de telecom, esquivando barriles de competidores, tormentas de clima y multas regulatorias, mientras recolectas tokens de espectro e instalas antenas para derrotar al **Interference King**.

- 🎮 **4 niveles + boss fight** con mecánicas únicas
- 🌐 **3 idiomas**: English, Español, Português
- 🔊 **Soundtrack 8-bit** sintetizado con Web Audio API (sin archivos externos)
- 🏆 **High score** persistente con `localStorage`
- 📦 **Un solo archivo HTML** — sin dependencias, sin build-step

---

## 🎮 Cómo jugar

1. Descarga o clona este repositorio.
2. Abre `spectrum_kong.html` en cualquier navegador moderno.
3. Empieza a subir torres y lucha contra la interferencia.

### Controles

- **Flechas / WASD** — Moverse y escalar
- **SPACE** — Saltar
- **E** — Instalar antenas y backhaul
- **X** — Disparar ondas de radio (boss fight)

---

## 🧱 Niveles

1. 🏗️ **Rural Water Tower**  
   Esquiva barriles de competidores mientras subes la torre.

2. 🌾 **Grain Elevator**  
   El clima entra en juego: barriles que “suben” por las estructuras.

3. 🏙️ **Rooftop POP**  
   Mezcla de todos los tipos de hazards, más “fantasmas de espectro”.

4. ⚡ **Boss: Interference Storm**  
   Junta espectro licenciado, dispara ondas de radio y derrota al Interference King.

Cada nivel introduce mecánicas nuevas sin perder el feeling clásico de arcade.

---

## 📡 Fixed Wireless en modo 8-bit

Spectrum Kong está lleno de guiños al mundo WISP:

- Competidores que lanzan “barriles” de interferencia.
- Tokens de espectro que representan licencias y bandas limpias.
- Instalación de antenas y backhaul en puntos clave.
- Boss final con ataques de interferencia aleatoria.

Todo con estética 8-bit, colores fuertes y audio chiptune.

---

## 🌎 Pensado para ferias y páginas de ISP

Spectrum Kong es ideal para:

- **Stands de ferias WISP** (WISPA, WISPMX, ABRINT, eventos regionales).
- **Landing pages de ISP** que quieren algo divertido y temático.
- **Activaciones** en las que se quiera gamificar el mundo WISP.

Características que lo hacen perfecto para esto:

- Un solo archivo `spectrum_kong.html`.
- Sin instalación ni dependencias.
- Sesiones cortas (partidas de 2–5 minutos).
- High score local para competencia amistosa en el stand.

---

## ⚙️ Roadmap — Versión 2.0

La versión actual es totalmente jugable. El objetivo de la v2.0 es convertir Spectrum Kong en un **arcade pulido listo para stands**:

### Mejor UX y onboarding

- [ ] Menú principal con **Play**, **Controles**, **Idioma**.
- [ ] Pantalla de “Cómo jugar” clara y rápida.
- [ ] Selección de idioma (EN/ES/PT) desde el menú.

### Balance y claridad en la jugabilidad

- [ ] Ajuste de dificultad por nivel (velocidad de barriles, frecuencia de hazards).
- [ ] Feedback al morir más claro (animaciones, mensajes).
- [ ] Boss final con patrones más telegrafiados y barra de vida visible.

### Modo demo / stand

- [ ] Atract mode:
  - Demo automática cuando no hay input durante X segundos.
  - Mensaje “Press any key to play”.
- [ ] Auto-reset:
  - Volver al menú tras la partida si no hay input.

### High score y rejugabilidad

- [ ] Top 5 scores con iniciales del jugador guardados en `localStorage`.
- [ ] Pequeños logros internos para darle más vida al juego.

### Branding para ISPs y asociaciones

- [ ] Configuración `ISP_CONFIG`:
  - Nombre y colores del ISP.
  - Logo opcional.
- [ ] Mensajes “Powered by <ISP>” en las pantallas clave.
- [ ] Pantalla final personalizable con CTA (web, QR, etc.).

---

## 🧱 Stack técnico

- HTML5 Canvas + JavaScript puro
- Web Audio API (sonido 8-bit generado al vuelo)
- Sin imágenes externas (pixel art dibujado vía Canvas)
- Sin dependencias, sin build, un solo archivo HTML

---

## ❤️ Hecho para la comunidad WISP

Spectrum Kong fue creado con cariño para:

- [WISPA](https://www.wispa.org)  
- [WISPMX](https://wisp.mx)  
- [ABRINT](https://abrint.com.br)  

Si eres un WISP o una asociación y quieres usar Spectrum Kong en tu sitio o en eventos, o quieres una versión con tu branding, abre un issue o contacta a los maintainers.

---

## 📄 Licencia

MIT — puedes jugarlo, compartirlo, hostearlo en tu web, y personalizarlo (con créditos) para tus eventos.

---

_© 2026 Spectrum Kong | Creado con ❤️ para la comunidad WISP._
