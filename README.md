## **Estructura del Proyecto**

index.html          # Archivo principal 

## **Tecnologías Utilizadas**

- HTML5
- TailwindCSS (vía CDN)
- Chart.js (vía CDN)
- JavaScript Vanilla

## **Funcionalidades Principales**

### 1. Vista de Inicio

- Visualización de balance general (Ingresos, Gastos, Balance)
- Gráfico circular de distribución por categorías
- Lista de movimientos recientes (últimos 4)

### 2. Vista de Movimientos

- Agregar nuevos movimientos
- Filtrar movimientos por:
    - Tipo (Ingreso/Gasto)
    - Categoría
    - Fecha específica
    - Búsqueda por descripción
- Visualización detallada de todos los movimientos

### 3. Vista de Gráficos

- Tendencia mensual de ingresos y gastos
- Balance mensual comparativo
- Filtrado por año (2024-2025)

## **Manual de Usuario**

### 1. Inicio

- Los totales de ingresos, gastos y balance se muestran en la parte superior
- El gráfico circular muestra la distribución por categorías
- Use los botones "Gastos/Ingresos" para cambiar la visualización del gráfico
- Los últimos 4 movimientos se muestran en la parte inferior

### 2. Movimientos

1. Para agregar un movimiento:
    - Click en "Agregar Movimiento"
    - Seleccionar tipo (Ingreso/Gasto)
    - Ingresar monto
    - Seleccionar o crear nueva categoría
    - Agregar descripción (opcional)
    - Seleccionar fecha
    - Click en "Guardar Movimiento"
2. Para filtrar movimientos:
    - Use la barra de búsqueda para filtrar por descripción
    - Seleccione tipo de movimiento
    - Seleccione categoría específica
    - Seleccione fecha específica
    - Click en "Filtrar" o "Limpiar" para resetear

### 3. Gráficos

- Seleccione el año para ver las estadísticas (2024-2025)
- El gráfico superior muestra la tendencia de ingresos y gastos
- El gráfico inferior muestra el balance mensual
- Se muestra la comparación del balance con el mes anterior

