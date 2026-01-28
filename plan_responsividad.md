# Plan de Optimización para Responsividad y Diseño Premium

Este plan detalla los pasos para asegurar que la web se vea perfecta en todos los dispositivos (móviles, tablets y escritorio), evitando desbordamientos de texto y roturas de diseño.

## Tareas

1. **Ajuste de Tipografía Responsiva**:
   - Usar tamaños de fuente más pequeños en móviles para los títulos de las tarjetas.
   - Implementar `hyphens: auto` o `word-break` donde sea necesario para evitar que palabras largas desborden.

2. **Optimización de Tarjetas en `index.html`**:
   - Revisar el padding y el gap de las tarjetas en tamaños de pantalla pequeños.
   - Asegurar que la tarjeta del Máster (la más ancha) se adapte correctamente.

3. **Mejores en `calendario.css`**:
   - Ajustar el tamaño de los nodos de la línea de tiempo para que no colisionen en móviles.
   - Asegurar que las tablas de carga académica no tengan scroll horizontal innecesario.

4. **Refuerzo de Estilos Globales**:
   - Revisar contenedores máximos (`max-w-Xl`) para que no queden demasiado pegados a los bordes en móviles.

## Verificación
- Probar el diseño en diferentes anchos simulados (Móvil, Tablet, Desktop).
- Confirmar que el texto del Máster no sobresale de la tarjeta en pantallas pequeñas.
