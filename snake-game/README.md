# ⚽ Stadium Snake Edition

Implementación del clásico juego Snake con **temática de fútbol**, usando **React vía CDN** y **Babel vía CDN**. Todo el código en un único archivo `index.html`, sin herramientas de build.

---

## 🚀 Cómo jugar

1. Abre `index.html` directamente en tu navegador.
2. Presiona **PATEAR PARA JUGAR**.
3. Controla al jugador con **↑ ↓ ← →** o **W A S D**.
4. Recoge los balones ⚽ para anotar goles y crecer.
5. Evita salirte del campo o chocarte contigo mismo.
6. Al terminar, presiona **SEGUNDO TIEMPO** para reiniciar.

---

## 🧩 Componentes React

```
App                     ← contenedor principal + estado + game loop
├── Score               ← marcador de goles y récord
├── LevelPanel          ← división / nivel actual con indicadores
├── Board               ← tablero + overlays (inicio / game over)
│   ├── FieldLines      ← SVG decorativo de cancha de fútbol
│   ├── Snake           ← segmentos del jugador
│   └── Food            ← balón de fútbol SVG animado
```

---

## ✅ Requisitos cubiertos

| Requerimiento | Estado |
|---|---|
| React + Babel vía CDN | ✅ |
| Todo en `index.html` | ✅ |
| Componentes separados (Game/Board/Snake/Food/Score) | ✅ |
| `useState` para el estado | ✅ |
| `useEffect` para el loop y teclado | ✅ |
| Props entre componentes | ✅ |
| Sin variables globales | ✅ |
| Sin `document.getElementById` | ✅ |
| Movimiento con teclado | ✅ |
| Crecer al comer | ✅ |
| Colisión con pared | ✅ |
| Colisión consigo mismo | ✅ |
| Game Over | ✅ |
| Puntaje | ✅ |

## ⭐ Extras 
- **Animaciones**: balón rebota y gira, jugador aparece con pop, score hace bump al anotar
- **Pantalla de inicio + reinicio**: overlay temático con textos del futbol
- **5 niveles de dificultad**: ROOKIE → AMATEUR → PRO → ALL-STAR → LEGEND

## 🎨 Temática deportiva
- Cancha de fútbol con líneas SVG 
- Balón de fútbol SVG animado como comida
- Marcador estilo estadio
- Ticker de noticias deportivas
- Paleta verde cancha + amarillo jersey