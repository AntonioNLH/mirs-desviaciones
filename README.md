# MIRS · Análisis de Desviaciones

App web para analizar desviaciones con **Ishikawa**, **5 porqués (RCA)** y **plan de acción**, con el formato MIRS.

**Abrir la app:** https://antonionlh.github.io/mirs-desviaciones/

## Qué hace

- Registra todas las desviaciones que necesites (faena o laboratorio).
- Por cada desviación: descripción, diagrama de Ishikawa que se dibuja solo, 5 porqués con causa raíz y plan de acción con responsable, fecha y estado.
- Resumen con todas las desviaciones y conclusiones.
- Exporta a **PDF**, a **PowerPoint** con la plantilla MIRS y a **CSV** para Excel.

## Cómo trabajar en equipo

Cada persona guarda su avance en su propio navegador (nadie ve los datos de otro).

1. Cada integrante completa sus desviaciones y usa **Exportar** (descarga un archivo `.json`).
2. Envía ese archivo a quien consolida.
3. Quien consolida usa **Importar → Agregar a las mías**, y así quedan todas las desviaciones juntas para generar la PPT o el PDF final.

## Exportar PDF

Botón **Exportar PDF** → en la ventana de impresión elige **Guardar como PDF** y orientación **horizontal**.

## Actualizar la app

Reemplaza `index.html` en este repositorio (Add file → Upload files → Commit changes). GitHub Pages publica el cambio en uno o dos minutos.
