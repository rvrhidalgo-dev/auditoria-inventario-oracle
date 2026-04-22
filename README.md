# Auditoría de Inventario y Conciliación de Datos (Oracle Cloud ERP)

## 📌 Contexto del Proyecto
Este proyecto simula un escenario real en una planta de manufactura de aerosoles. El objetivo fue identificar discrepancias financieras y operativas entre los registros de **Oracle Cloud ERP** y el inventario físico real.

## 🛠️ Problemas Detectados (Data Cleaning)
El reporte inicial presentaba los siguientes errores críticos que fueron saneados manualmente:
- **Duplicados:** Facturas repetidas que inflaban el inventario contable.
- **Inconsistencia de Formatos:** Fechas y nombres de materiales desordenados.
- **Valores Nulos:** Falta de registros de entrada en materiales críticos (Gas Propelente).

## 📊 Hallazgos de la Auditoría
Tras la limpieza y aplicación de fórmulas de conciliación, se identificaron:
1. **Errores de Captura:** Una diferencia de 995 unidades en Gas Propelente debido a omisión en la recepción del sistema.
2. **Mermas No Justificadas:** Identificación de "pérdida invisible" en insumos (canicas, envases, etiquetas) tras descontar los ajustes de producción.

## 📈 Dashboard de Resultados
*(Aquí puedes insertar la imagen de tu gráfica)*
![Dashboard de Auditoría](image_1ab585.png)

## 💡 Habilidades Aplicadas
- Limpieza de datos (Data Cleaning).
- Auditoría de inventarios (Conciliación).
- Google Sheets / Excel Avanzado.
- Análisis de procesos logísticos.
