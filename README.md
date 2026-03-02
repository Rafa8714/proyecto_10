🛒 Optimización de Ingresos: Análisis de Hipótesis y Pruebas A/B
Este proyecto se enfoca en la toma de decisiones basada en datos para una tienda en línea. El proceso abarca desde la priorización estratégica de experimentos hasta el análisis riguroso de un test A/B para maximizar el impacto en el negocio.

🎯 Objetivos del Proyecto
Priorizar 9 hipótesis de negocio utilizando los frameworks ICE y RICE.

Analizar un test A/B mediante el seguimiento de métricas acumuladas y la detección de anomalías.

Tomar una decisión de negocio: ¿Continuar la prueba, detenerla y declarar un ganador, o detenerla y declarar que no hay diferencia?

🚀 Etapa 1: Priorización de Hipótesis
Se evaluaron diversas estrategias (marketing, logística, UI/UX) bajo dos metodologías:

🔹 Framework ICE (Impact, Confidence, Ease)
Top 1: Lanzar promociones con descuentos para cumpleaños.

Conclusión: Esta hipótesis destaca por su alto impacto y confianza con un esfuerzo moderado. Es una victoria rápida ("Quick Win").

🔹 Framework RICE (Reach, Impact, Confidence, Effort)
Top 1: Agregar un formulario de suscripción a todas las páginas principales.

Conclusión: 
  * Al introducir el Alcance (Reach), el ranking cambia drásticamente. Esta hipótesis escala al primer lugar porque impacta a todos los visitantes, no solo a un segmento pequeño, multiplicando el retorno de inversión          potencial.

🧪 Etapa 2: Análisis del Test A/B
🧹 Preparación y Limpieza de Datos
Antes del análisis, se realizó un control de calidad crítico:

Hallazgo: 
  * Se identificaron 58 usuarios que aparecían simultáneamente en el Grupo A y en el Grupo B.

Acción: 
  * Estos usuarios fueron excluidos del análisis para mantener la pureza de los grupos y evitar errores en el cálculo de la tasa de conversión y el ticket promedio.

📊 Métricas Analizadas
Ingresos Acumulados: 
  * Seguimiento diario de las ventas por grupo para observar estabilidad.

Conversión: 
  * Análisis de la relación entre visitas y pedidos realizados.

Tamaño Promedio de Pedido: 
  * Evaluación de si los cambios incentivaron compras de mayor valor.

Ingresos acumulados por grupo:

<img width="1042" height="600" alt="image" src="https://github.com/user-attachments/assets/7108075a-a61a-45c4-9772-590bde07ef8f" />

Tasa de Conversión Diaria (Pedidos / Visitas):

<img width="1386" height="690" alt="image" src="https://github.com/user-attachments/assets/9fdaa927-1501-4ac8-80ac-69f64630eab1" />

Precios de Pedidos por Transacción:

<img width="1160" height="628" alt="image" src="https://github.com/user-attachments/assets/857a8cb7-67f8-4a64-84a4-b5ddd415f4b0" />




💡 Conclusiones del Análisis:

Frameworks de Priorización: 
  * La diferencia entre ICE y RICE demuestra que el alcance es un factor decisivo. Proyectos que parecen menores pueden ser prioritarios si afectan a toda la base de usuarios.

Integridad del Test:
  * La presencia de usuarios en ambos grupos sugiere un posible error en el mecanismo de asignación (logging o segmentación). Es vital corregir esto antes de futuras pruebas.

Resultados: 
  * La Variante B no logró el objetivo de mejorar el rendimiento del negocio. Los pequeños cambios observados son ruido estadístico. Lo más eficiente es detener la prueba y evitar la implementación de un cambio que no ofrece ningún beneficio.

🛠️ Herramientas Utilizadas

  * Python: Lenguaje principal.

  * Pandas & NumPy: Procesamiento y limpieza de datos.
