# 🧬 Bitácora de Análisis RNA-seq  

Este repositorio corresponde a mi **bitácora personal de análisis de RNA-seq**, desarrollada como parte de los prácticos del curso [**Bioinformática y Genómica**](https://github.com/TarifenoLab/Curso-Bioinformatica_y_Genomica_4115030/wiki).  

Su propósito es documentar de manera clara y ordenada cada paso del flujo de trabajo, facilitando la **reproducibilidad** y el **aprendizaje aplicado** de los métodos de análisis de datos transcriptómicos.  

---

## 📂 Estructura del repositorio  
|-- data -> Datos crudos y procesados (FASTQ, BAM, GTF, etc.)
|-- ntbk -> Cuadernos Júpyter con el proceso de ejecución de los análisis
|-- README.md -> Archivo de descripción principal

---

## 🚀 Flujo de análisis RNA-seq  

1. **📊 Control de calidad inicial**  
   - Evaluar la calidad de las lecturas crudas con *FastQC* y *Fastq_screen* y consolidar reportes con *MultiQC*.  

2. **✂️ Preprocesamiento (Trimming y filtrado)**  
   - Eliminar adaptadores y bases de baja calidad (*Cutadapt*, *Trimmomatics*, *NGS QC Toolkit*, *FASTX-Toolkit*).  
   - Filtrar lecturas demasiado cortas o contaminantes.

3. **🧩 Alineamiento de secuencias** 


4. **📈 Control de Calidad del Alineamiento, Visualización y Conteo de Reads**


5. **🖥️ Análisis de expresión diferencial**  


6. **🛠️  Ensamble de novo del transcriptoma**
