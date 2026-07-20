# STEPQUEST

Juego RPG para móvil donde **tus pasos reales son el motor del juego**. Los pasos (de Apple Salud / Health Connect, sin reloj) hacen avanzar a tu Cazador: cada 100 pasos = 1 avance con enemigos, oro y botín. Sigue progresando aunque cierres la app.

**▶️ Demo jugable:** https://esttik.github.io/stepquest-demo/

---

## Qué incluye la demo (v4)

- **Creador de personaje** (estilo LPC): clase, género, tono de piel, peinado.
- **Bucle central por pasos**: expedición automática con feed de recompensas en vivo.
- **Pasos guardados (offline)**: se aplican al volver → recompensa de bienvenida.
- **Racha diaria 🔥 + meta de pasos** con cofre diario.
- **⚡ Furia del Cazador**: barra que cargas y desatas para x2 recompensas.
- **🎯 Misiones**: objetivos encadenados con cofres.
- **Jefes con mecánica**: combate manual con **GOLPE BRUTAL** que debes bloquear (🛡️ Defender).
- **Dificultad real**: enemigos escalan con tu nivel; las expediciones pueden fallar.
- **⚔️ Arena PvP asíncrona**: luchas contra la *build* de otros cazadores (simulados por ahora), con liga, trofeos y clasificación.
- **Equipo, inventario, tienda y forja** (mejora de equipo con oro).
- **Optimizado para móvil** (pantalla completa).

## Economía
- 🪙 **Oro**: se gana jugando; se gasta en forja y tienda.
- 💎 **Gemas**: premium / cosmético.

## Cómo actualizar la web
La demo es un único `index.html` autónomo (HTML+CSS+JS). Al reemplazarlo y hacer `git push`, GitHub Pages reconstruye y la misma URL se actualiza en ~1 min.

## Roadmap
1. Afinar dificultad y recompensas con feedback.
2. **Abismo Infinito** (modo sin fin con récord de profundidad).
3. **PvP real**: backend (cuentas, base de datos, API, anti-trampas) para que la Arena sean jugadores reales.
4. Sets de equipo con sinergias y árbol de habilidades.
5. Compañero/mascota con bonus real.
6. Eventos / mazmorra diaria y temporadas de arena.

## Nota técnica
Prototipo 100% cliente (sin servidor). Los sprites se componen en el navegador desde el generador LPC. En la app real, los pasos vendrían de HealthKit / Health Connect.
