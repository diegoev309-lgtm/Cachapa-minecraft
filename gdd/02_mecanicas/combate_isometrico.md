# Mecánica: Combate Isométrico en Tiempo Real

## Perspectiva y Movimiento
- **Proyección:** Isométrica 2:1 clásica (Pixel Art).
- **Controles Básicos:**
  - `W, A, S, D` o `Flechas`: Movimiento en 8 direcciones adaptado al ángulo de la cuadrícula isométrica.
  - `Espacio` o `Shift`: **Dash / Desplazamiento rápido evasivo**. Posee marcos de invulnerabilidad (*i-frames*) temporales para atravesar garras o proyectiles ácidos. Consume estamina / energía.
  - `Click Izquierdo` (o `J`): Ataque principal con el arma biomecánica equipada.
  - `Click Derecho` (o `K`): Habilidad especial / disparo secundario del arma.
  - `Rueda del Ratón` / `1, 2, 3`: Cambio rápido de arma en el inventario.

---

## Sistema de Profundidad (Y-Depth Sorting)
- El personaje, los enemigos y los objetos del escenario (columnas, consolas, tubos de carne colgantes) tienen su orden de dibujado ajustado dinámicamente según su posición en el eje Y (`depth = y`).
- Esto garantiza que el protagonista pueda caminar tanto por delante como por detrás de cualquier estructura de la ciudad sin cortes visuales.

---

## Dinámica de Combate: Biomasa vs Electricidad
- **Vulnerabilidad Orgánica:** La carne viva está saturada de fluidos biológicos y soluciones salinas, haciéndola un conductor eléctrico extraordinario. Los ataques cargados con corriente causan aturdimiento y daño por electrocución continua.
- **Enemigos con Armadura de Quitina:** Ciertas criaturas han endurecido su piel con placas óseas. Requieren armas de bilis corrosiva o impacto contundente antes de poder electrocutarlas con efectividad.
