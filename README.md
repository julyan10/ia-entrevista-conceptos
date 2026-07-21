# Conceptos IA para entrevistas

Página web estática para repasar conceptos de IA, agentes, RAG, bases de datos, seguridad y backend antes de entrevistas.

## Qué incluye

- Búsqueda por concepto, explicación o frase de entrevista.
- Filtros por categoría, favoritos, pendientes y dominados.
- Filtro por ruta de preparacion: General, Data Scientist - UNICO e Ingeniero de Datos y BI - Pint Pharma.
- Modo repaso con tarjeta aleatoria.
- Sección inicial de arquitectura completa de un Agente IA con MCP, tool calling, RAG, n8n, LangGraph, LangChain, memoria, observabilidad y guardrails.
- Sección de caso práctico SaaS B2B AI-first: problema, priorización, arquitectura, MVP, riesgos y métricas.
- Sección con dos ejemplos aplicados: RAG y Text2SQL.
- Conceptos de Power BI: Importación, DirectQuery y Conexión en vivo.
- Sección final simplificada con programas y herramientas clave de datos.
- Ejemplo aplicado de pipeline con ERP, APIs, Data Lake, PySpark, SQL, BI e IA.
- Ejemplo detallado de implementación en Azure con Data Factory, Data Lake Gen2, Databricks, Azure SQL, Power BI y Azure OpenAI.
- Sección Oracle + PySpark + Medallion con conexión JDBC, capas Bronze/Silver/Gold y respuesta para entrevista.
- Conceptos de datos: SQL, PySpark, ETL / ELT, ERP, Cloud, Data Lake, Analítica / BI e Integración de datos.
- Conceptos Oracle/Lakehouse: Oracle Database, PL/SQL, JDBC, Medallion, Bronze, Silver, Gold, Lakehouse, Delta Lake, Data Quality, Data Lineage y Data Governance.
- Conceptos de automatización IA: Document Intelligence, OCR, Human in the loop, Idempotencia, DLQ, Structured Outputs, Dataset dorado, Evaluación automática y OpenTelemetry.
- Conceptos modernos de agentes: MCP, Function Calling, Chunking, Re-ranking, Chroma, Pinecone, FAISS, Weaviate, Milvus, Fine-tuning, memoria, webhooks, temperatura, tokens, hallucination, guardrails y comparaciones rápidas.
- Agregar conceptos nuevos desde la página.
- Guardado local con `localStorage`.
- Exportar e importar los conceptos en JSON.
- Ruta Data Scientist - UNICO con EDA, feature engineering, modelos supervisados y no supervisados, metricas, SHAP, A/B testing, MLOps y monitoreo.
- Ruta Ingeniero de Datos y BI - Pint Pharma con pipelines, Azure Data Factory, Data Lake, Databricks, Delta Lake, modelo estrella, DAX, Power BI, particiones y calidad de datos.
- Tema claro y oscuro.

## Cómo abrirlo

Abre `index.html` directamente en el navegador.

## Cómo subirlo a GitHub

1. Crea un repositorio nuevo en GitHub.
2. Sube estos archivos:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
3. En GitHub, entra a `Settings > Pages`.
4. En `Build and deployment`, selecciona `Deploy from a branch`.
5. Elige la rama `main` y la carpeta `/root`.
6. Guarda y espera a que GitHub genere la URL.

## Cómo agregar conceptos de forma permanente

Puedes usar el formulario de la página y luego exportar el JSON como respaldo. Si quieres que los conceptos nuevos queden en el repositorio para todos los navegadores, agrega nuevos objetos en el arreglo `baseConcepts` dentro de `script.js`.
