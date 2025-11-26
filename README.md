📌 Descripción General

Este proyecto automatiza el proceso de leer datos desde un archivo Excel y llenar un formulario web con esos valores usando UiPath Studio 2025.
Incluye manejo básico de validaciones, recorrido fila por fila (For Each Row), escritura en campos de texto y captura de evidencias para documentación.

El objetivo principal es demostrar la capacidad de UiPath para interactuar con archivos Excel y automatizar formularios web de manera estable y repetible.

🗂️ Estructura del Repositorio
/UiPath
   Data.xlsx                → Archivo Excel con los datos a procesar
   /Proyecto                → Carpeta completa del proyecto UiPath
      Main.xaml
      project.json
      (carpetas internas de UiPath: .screenshots, .local, etc.)

/Screenshots
   evidencia_1_excel.png
   evidencia_2_formulario.png
   evidencia_3_resultado.png

README.md

🚀 Funcionalidad del Proyecto

Carga un archivo Excel (Data.xlsx)

Convierte el contenido en un DataTable

Itera cada fila con For Each Row in DataTable

Escribe los valores en un formulario web

Valida que los campos se sobrescriban correctamente

Incluye un pequeño manejo de errores

Termina mostrando un mensaje de completado

📄 Archivos Importantes
📁 UiPath / Proyecto

Contiene el flujo completo (Main.xaml) y archivos internos que UiPath necesita.

📄 UiPath / Data.xlsx

Excel de entrada que el robot procesará.

📸 Screenshots

Capturas mínimas necesarias para evidenciar la práctica:

Cargar Excel con datos

Formulario recibiendo información del robot

Output Panel mostrando ejecución completada

▶️ Cómo Ejecutar el Proyecto

Abre UiPath Studio

Ve a Open → Open Folder

Selecciona: (RUTA DEL HASTA EL ARCHIVO "project.json")

Si UiPath lo solicita, presiona Restore Dependencies

Corrige la ruta del archivo Excel si es necesario

Presiona Run

🧪 Flujo General

Read Range para cargar el Excel

For Each Row para recorrer cada registro

Type Into para llenar el formulario

Borrar/reescribir campos cuando es necesario

Log Message / Output Panel para seguimiento

Fin de ejecución sin errores

🛠️ Tecnologías Utilizadas

UiPath Studio 2025

UiPath.Excel.Activities

UiPath.System.Activities

Google Chrome / Microsoft Edge

Excel como fuente de datos

📷 Evidencias

Las capturas están dentro de la carpeta /Screenshots.

Screenshots/excel_input.jpg
Screenshots/OUTPUT.jpg
Screenshots/project_structure.jpg
Screenshots/workflow.jpg

📌 Mejoras Futuras (Opcional)

Mejor manejo de errores con Try–Catch

Validación de campos obligatorios

Generación de un archivo con los resultados

Publicación del proceso en Orchestrator

👤 Autor

German Sánchez
Proyecto de práctica — Curso gratuito RPA UiPath 2025 de Camilo Duarte.