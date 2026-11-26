# ⚽ Armador de Equipos (Fútbol 5 / 6 / 8)

App para el celular que arma equipos parejos y aleatorios según el nivel de cada jugador.

## Cómo se usa
1. **Inicio**: tarjetas con tus equipos (ej: "Los martes"). Tocá **+ Nuevo equipo** para crear otro (nombre y color).
2. **Dentro de un equipo**: cargá jugadores con 7 habilidades de 1 a 5 ⭐ (velocidad, regate, pase, definición, defensa, resistencia, atajada).
   Con el buscador 🔍 podés sumar jugadores que ya tenés cargados en otros equipos.
3. **⚽ Armar equipos**: elegí F5, F6 u F8, marcá quién viene y tocá **Armar**. Con **Agregar invitado** sumás a alguien que juega sólo ese día (nivel promedio si no sabés cómo juega).
4. **Resultado**: equipos parejos por nivel, habilidad y posición (ARQ/DEF/MED/DEL). 🔒 fija un jugador, **Re-sortear** da otra combinación, **Imagen** genera los equipos parados en una cancha (Claros vs Oscuros) para mandar por WhatsApp; también se pueden compartir como texto.
   **Cuentas de la cancha**: total, cuánto pone cada uno, quién pagó, alias y recordatorio. En **Partidos** ves quién debe.
5. **Cargar resultado**: fecha, cancha, marcador, goles y asistencias de cada jugador, quién atajó (el arco rota: todos marcados, desmarcás al que no atajó) y cuántos goles le hicieron a cada uno y la figura 🏆. Queda en la pestaña **Partidos** y suma al **Ranking por puntos**: jugar +1, ganar +3 / empatar +1 (× dificultad según el equipo que te tocó, de ×0,5 a ×1,6), gol +2, asistencia +1, figura +3, atajar sin que te hagan goles +1, −0,5 por gol recibido atajando, no atajar −3.
6. **Ajustes del sorteo** (en Armar equipos): *Nivel según resultados* (quien gana seguido sube hasta +0.6, quien pierde baja) y *Parejas* (siempre juntos / nunca juntos).
7. **Ficha del jugador**: tocá un jugador para ver su carta estilo FIFA (con foto), radar de habilidades, estadísticas, racha e historial. **Compartir** genera la carta como imagen.

Todo se guarda en el celular. Usá **Exportar/Importar** (en el inicio) para backup o para pasarlo a otro teléfono.

## Instalarla en el celular
La app es una PWA: tiene que abrirse desde una dirección `https://` para poder instalarse.
- Opción rápida: subí esta carpeta a **Netlify Drop** (app.netlify.com/drop) o **GitHub Pages** y abrí el link en el celular.
- Android (Chrome): menú ⋮ → *Agregar a pantalla de inicio* / *Instalar app*.
- iPhone (Safari): botón Compartir → *Agregar a inicio*.

Para probarla en la PC: abrí `index.html` en el navegador.
