# Tipos de Control

Los modos de control definen cómo un sistema responde al error entre la variable medida y el valor deseado.

| Tipo de Control | Descripción | Ventajas | Desventajas |
|------------------|-------------|-----------|--------------|
| **Todo-nada (On/Off)** | Solo tiene dos estados: encendido o apagado. | Simple y económico. | Oscilaciones, poca precisión. |
| **Flotante** | Cambia gradualmente la salida. | Menos desgaste, control suave. | Lento para procesos rápidos. |
| **Proporcional (P)** | Corrige según la magnitud del error. | Respuesta rápida. | Deja un error permanente. |
| **Integral (I)** | Corrige acumulando el error. | Elimina el error permanente. | Puede causar oscilaciones. |
| **Derivativo (D)** | Actúa según la rapidez del cambio del error. | Predice variaciones. | Sensible al ruido. |

**Control PID:** combina P + I + D, equilibrando estabilidad, rapidez y precisión.

---
