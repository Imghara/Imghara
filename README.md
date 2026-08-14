# 👋 Hola, este perfil fue creado para mostrar parte de la experiencia frente a posiciones de Gerencia & Dirección con enfoque en la Operatividad y anticipación de escenarios con BI (Business Intelligence)

> **Inteligencia y Estrategia Comercial** · Gerente Comercial con 15 años de experiencia liderando transformaciones operativas y estrategias de venta B2B, con un perfil único de inteligencia analítica y certificación en Data Analytics (Google).

🔀 **Nota para reclutadores:** este perfil también aparece como **gluevanos** y como **ghara** — son mis alias; siempre soy la misma persona, el mismo portafolio y el mismo correo (`gluevanos@gmail.com`).

---

## 🌊 El Errante — BI & Incentivos con Prescripción Estratégica

> Dashboard de Business Intelligence para el Gerente General de una cadena de restaurantes de mariscos con 3 sucursales (Nuevo León, Coahuila y Tamaulipas). No se limita a informar: detecta cuándo el margen entra en zona de riesgo y prescribe la acción correctiva con su impacto esperado, protegiendo la rentabilidad ante la volatilidad del mercado de mariscos.

El problema: un restaurantero multisucursal compra insumos perecederos (mariscos, cerveza) cuyo costo fluctúa ±15% al mes y decide a ciegas: no sabe qué meseros rinden, qué clientes se van o qué platillos aguantan un aumento de precio.

La solución: Dashboard en esquema en estrella con 8 tablas (4 dimensiones + 4 hechos) y 700,000+ líneas de venta sintéticas realistas (2024-2025): $119M MXN de ingresos, margen bruto 49.2%, y estacionalidad auténtica de mariscos (Cuaresma +40%, cuesta de enero −20%).

Regla de oro: datos 100% reproducibles (semilla fija) con las reglas de negocio sembradas en el generador (crecimiento 1.5×, costos ±15%, elasticidad). El ROI usa el costo mayorista real por producto y mes, y el ancla (Sopa de Mariscos) queda fuera de los incentivos por diseño.

- 🧭 **10 módulos analíticos**: Consolidado Financiero, Incentivos, CRM, Presupuesto vs Real, Alertas, Pronóstico, Rotación de Mesas, Deserción, Elasticidad de Precios y Auditoría Anti-fraude.

- 🔮 **Pronóstico de demanda** (GradientBoosting): MAPE **30.9%** vs 45.2% de referencia ingenua → convierte el pronóstico semanal en **kg de marisco** y **cajas de cerveza** para comprar anticipado al mayorista y congelar precio.

- 🚨 **Centro de alertas con simulador de estrés**: 5 reglas con umbrales verde/amarillo/rojo; anticipa qué pasa si el marisco sube 25% o la demanda cae 10% y abre el plan de contingencia.

- 👥 **Detección de churn**: 58 clientes Oro/VIP en riesgo = **$1.05M MXN** de valor anual en peligro, con plan de reactivación listo (Sopa gratis + 2 bebidas de marketing).

- 📈 **Elasticidad de precios** (log-log con efectos fijos): 33 productos inelásticos identificados → +5% de precio agrega **+$2.5M MXN** sin perder clientes.

- 🕵️ **Auditoría anti-fraude**: detecta "venta impositiva" — meseros con comisiones altas y servicio < 3.5 — crecimiento que no es sano; 6 meseros críticos con plan de acción.

- 🧪 **Calidad profesional**: 41 pruebas automatizadas (pytest) que validan las reglas de negocio + manual de usuario en norma APA 7.ª (28 páginas, una sola tinta).

Stack: Python · Streamlit · Plotly · pandas · scikit-learn · esquema en estrella.

[![Código](https://img.shields.io/badge/C%C3%B3digo-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Imghara/Gelatto)
[![Documentación](https://img.shields.io/badge/Documentaci%C3%B3n-Maestro-1BA39C?style=for-the-badge)](https://github.com/Imghara/Gelatto/blob/main/Documento_Maestro.md)

## 🌊 Gelatto — Data Warehouse y Dashboard de BI con Prescripción Estratégica
> Dashboard de Business Intelligence para el Director Comercial y de Marketing de una empresa B2B de lácteos y helados (Nuevo León, Coahuila, Tamaulipas y Durango). No se limita a informar: detecta cuándo un indicador entra en zona de riesgo y prescribe la acción correctiva con su impacto esperado.

El problema: una empresa mediana (~1,200 clientes, 30 vendedores, 13 rutas, 4 canales) toma decisiones con datos dispersos. El Director necesita una fuente única de verdad que le diga qué vender, a quién retener, a qué vendedor capacitar y qué insumo reabastecer.

La solución: Data Warehouse en esquema estrella con 17 tablas (8 dimensiones + 9 hechos) y 1.5M+ filas sintéticas realistas (2023-2025): $2,056M MXN de ingresos, margen 30.5%, y estacionalidad auténtica de helados (temporada alta = 2.35x la baja).

Regla de oro: toda la agregación pesada ocurre en el motor de datos (GROUP BY, ventanas, particionado en SQL). Streamlit recibe solo las filas finales, nunca SELECT * de millones de filas. Arquitectura de doble motor: DuckDB+Parquet en desarrollo y Google BigQuery en producción, conmutados por una variable de entorno.

- 🧭 **9 módulos analíticos**: Resumen Ejecutivo, Ventas, Alertas y Recomendaciones, Clientes y Fraude, Inventarios y Costos, Distribución y Mapas, Incentivos y Campañas, Simulador de Escenarios.

- 🚨 **Motor de alertas y recomendaciones**: umbrales verde/amarillo/rojo por KPI; al cruzar la zona de riesgo genera alerta + recomendación + impacto monetario (vendedor al 68% de cuota → coaching, gap de $450K; cliente que redujo 56% su compra → visita con oferta especial).

- 🕵️ **Detección de fraude y churn**: fraude por z-score sobre ventana móvil de 12 meses previos (12 clientes anómalos detectados); churn con comparación año contra año para eliminar la estacionalidad (evita 921 falsas alarmas); vendedores con cancelaciones del 15-23% auditados.

- 🧮 **Simulador de escenarios**: +5% de precio con elasticidad 1.5 → +$17.5M de margen; promoción de 10% que requiere +75% de volumen para pagarse sola; cuota +10% que deja 15 vendedores bajo el umbral de coaching.

- **Ingeniería**: datos con semilla fija y escenarios sembrados (churn, fraude, desabastos, salto de +25% en lácteos); 8 módulos + 6 interacciones validados con Streamlit AppTest (0 excepciones); listo para migrar a facturación real sin rediseñar. (1.5M+ líneas sintéticas realistas)

Stack: Python · Streamlit · Plotly · DuckDB · BigQuery · pandas · SQL analítico · esquema estrella.
 

🔗 [Demo en vivo](https://gelatto.streamlit.app) · [Código fuente](https://github.com/Imghara/Gelatto) · [Documento Maestro](https://github.com/Imghara/Gelatto/blob/main/Documento_Maestro.md)

---

## 🛠️ Stack y herramientas

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=power-bi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=flat&logo=salesforce&logoColor=white)
![SAP](https://img.shields.io/badge/SAP-0FAAFF?style=flat&logo=sap&logoColor=white)

**Excel Avanzado · SQL · R · Python · Power BI · Salesforce · SAP · Google Analytics · IA aplicada** (redes neuronales, análisis de patrones, automatización).

---

## 🏢 Trayectoria (resumen)

- **Gerente Regional de Ventas** · Cuatro Vientos (2011 – actualidad) — gestión comercial multiestatal, homologación de procesos y optimización de rentabilidad
- **Business Development Manager** · Grupo Modelo NL (2019) — apertura de cuentas clave y desarrollo B2B
- **Jefe de Departamento** · CISEN, Gobierno Federal (2006 – 2009) — inteligencia estratégica y análisis de contextos complejos
- **Certificación**: Google Data Analytics Professional Certificate (2022)

---

## 📫 Contacto

📧 `gluevanos@gmail.com` · 📍 San Nicolás de los Garza, NL ·

---

*Portafolio profesional en construcción — nuevos proyectos de BI, análisis y automatización en camino.* 🌊
