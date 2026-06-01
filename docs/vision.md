# Operations Intelligence Hub

## Problema

Los responsables de operaciones suelen consultar indicadores externos
(economía, energía, inflación, etc.) en múltiples fuentes y no disponen
de una visión unificada ni de alertas automáticas sobre cambios relevantes.

## Usuario objetivo

- Responsables de operaciones
- Ingenieros de mejora continua
- Analistas de negocio
- Supply Chain Managers

## Qué hace

- Descarga indicadores desde APIs públicas.
- Guarda históricos en una base de datos.
- Visualiza tendencias mediante dashboards.
- Genera alertas simples sobre cambios relevantes.

## Qué NO hace

- Gestión de usuarios.
- Autenticación.
- Predicciones avanzadas.
- Integraciones empresariales.
- Chatbots.
- Aplicaciones móviles.

## Definición de MVP

El MVP estará terminado cuando:

- Se descarguen 3 indicadores.
- Los datos se almacenen en PostgreSQL.
- Exista una API FastAPI funcional.
- Exista un dashboard Streamlit.
- Existan al menos 3 alertas automáticas.
