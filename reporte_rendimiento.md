# Reporte de Análisis de Rendimiento

## Información General
- **Fecha de Análisis:** 2025-10-18 04:43:49
- **Archivo Analizado:** logs_ejemplo.txt
- **Total de Líneas Procesadas:** 50
- **Período de Tiempo:** 2024-10-17 10:23:45 - 2024-10-17 10:24:34

## Estadísticas Generales
- **Total de solicitudes procesadas:** 50
- **Tiempo promedio de respuesta:** 254.6 ms
- **Tiempo máximo:** 1234.0 ms
- **Tiempo mínimo:** 11.0 ms
- **Desviación estándar:** 307.7 ms

## Análisis por Código de Estado
| Código | Cantidad | Porcentaje | Tiempo Promedio |
|--------|----------|------------|-----------------|
| 200    | 44      | 88.0%        | 228.8 ms       |
| 201    | 3      | 6.0%        | 171.0 ms       |
| 404    | 1      | 2.0%        | 23.0 ms       |
| 500    | 1      | 2.0%        | 892.0 ms       |
| Otros  | 1      | 2.0%        | 1234.0 ms       |

## Análisis por Endpoint
| Endpoint | Solicitudes | Tiempo Promedio | Tiempo Max | Tiempo Min |
|----------|-------------|-----------------|------------|------------|
| /api/users | 1 | [AVG] ms | 1234.0 ms | 11.0 ms |
| /api/products | 1 | [AVG] ms | 1234.0 ms | 11.0 ms |
| /api/login | 1 | [AVG] ms | 1234.0 ms | 11.0 ms |
| [OTROS ENDPOINTS] | ... | ... | ... | ... |

## Endpoints Más Lentos
1. **/api/upload** - Promedio: 1234.0 ms
   - Solicitudes: 1
   - Tiempo máximo: 1234.0 ms

2. **/api/backup** - Promedio: 1234.0 ms
   - Solicitudes: 1
   - Tiempo máximo: 1234.0 ms

3. **/api/orders** - Promedio: 1234.0 ms
   - Solicitudes: 1
   - Tiempo máximo: 1234.0 ms

## Análisis de Errores
- **Total de errores (4xx, 5xx):** 3
- **Tasa de error:** 6.0%
- **Endpoint con más errores:** /api/orders (1 errores)
- **Tipo de error más común:** 500 - 1 ocurrencias

## Patrones Identificados
- Se observa un incremento en los tiempos de respuesta para el endpoint /api/orders
- Se observa un incremento en los tiempos de respuesta para el endpoint /api/reports
- Se observa un incremento en los tiempos de respuesta para el endpoint /api/upload
- Se observa un incremento en los tiempos de respuesta para el endpoint /api/stats
- Se observa un incremento en los tiempos de respuesta para el endpoint /api/payment
- Se observa un incremento en los tiempos de respuesta para el endpoint /api/export
- Se observa un incremento en los tiempos de respuesta para el endpoint /api/backup
- Se observa un incremento en los tiempos de respuesta para el endpoint /api/process
- Los errores estan distribuidos, el mas frecuente es 500 en /api/orders
- Ejemplo: Se observa un incremento en los tiempos de respuesta para el endpoint /api/reports
- Ejemplo: Los errores 500 están concentrados en el endpoint /api/orders

## Recomendaciones de Optimización
1. **Optimizar el endpoint /api/upload**
   - Impacto esperado: Reduccion significativa en el tiempo de respuesta general del sistema
   - Prioridad: Alta

2. **Revisar y corregir endpoints con errores HTTP**
   - Impacto esperado: Reduccion significativa en el tiempo de respuesta general del sistema
   - Prioridad: Alta

3. **Estabilizar la variabilidad en los tiempos de respuesta**
   - Impacto esperado: Reduccion significativa en el tiempo de respuesta general del sistema
   - Prioridad: Alta

## Conclusiones
[TUS CONCLUSIONES SOBRE EL ANÁLISIS]

---
*Reporte generado usando Python - Análisis de Logs de Rendimiento*
*Asignatura: Diseño Funcional - FESC*
*Tema: Subalgoritmos, Funciones y Procedimientos*