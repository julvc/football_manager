## 🧪 Caso de uso: Generar alineación óptima para un equipo en una temporada

### 🎯 Objetivo
Seleccionar la mejor alineación posible (11 jugadores) para un equipo específico en una temporada determinada, considerando rendimiento individual, posición, y sinergia táctica.

### 📥 Datos requeridos
- club (nombre del equipo)
- season (año o rango de temporada)
- position (para filtrar por rol: GK, DF, MF, FW)
- overall_rating, potential, age, appearances, goals, assists, clean_sheets, etc.


### ⚙️ Lógica esperada
- Filtrar jugadores del equipo y temporada seleccionada.
- Agrupar por posición para asegurar una alineación balanceada (ej. 4-3-3).
- Ordenar por rendimiento (rating, contribuciones ofensivas/defensivas).
- Aplicar reglas básicas de sinergia (evitar jugadores con bajo tiempo de juego o incompatibles por rol).
- Retornar los 11 mejores jugadores según la formación táctica elegida.


### 📤 Resultado esperado
- Una tabla con los 11 jugadores seleccionados, sus posiciones y métricas clave.
- Posible visualización tipo campo de fútbol con los nombres ubicados según formación.
- Opción de exportar como JSON para usar en backend o frontend.
