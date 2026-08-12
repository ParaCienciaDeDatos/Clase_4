
# 📊 Manejo de Datos (Episodio II)

<!-- badges: start -->
<!-- badges: end -->


**Curso:** Introducción a Ciencia de Datos  
**Docentes:** Dr. Gustavo Giménez | Mg. Ana Haique  
**Formato:** Diapositivas Quarto HTML (`.qmd`)

---

## 📌 Resumen del Módulo

Este módulo aborda las técnicas esenciales para el **ingreso, importación y gestión de datos** en R. Cubre desde la lectura de archivos de texto plano y hojas de cálculo complejas hasta la consulta eficiente de bases de datos relacionales locales y remotas sin saturar la memoria RAM.

---

## 📚 Ejes Temáticos

* **Archivos Delimitados y Comprimidos (`readr`):** Lectura eficiente de `.csv`, `.tsv`, archivos con delimitadores personalizados y formatos comprimidos (`.gz`, `.zip`) sin necesidad de desempacar en disco.
* **Hojas de Cálculo (`readxl` / `writexl`):** Inspección de pestañas, selección de rangos específicos, omisión de filas de metadatos (`skip`), tratamiento de valores nulos (`na`) y exportación a Excel.
* **Manipulación y Ensamble:** Creación manual de tablas (`tibble` / `tribble`) y combinación de estructuras horizontal (`bind_cols`) y verticalmente (`bind_rows`).
* **Lectura Masiva:** Carga de múltiples archivos en lote mediante funciones aplicadas (`lapply` + `list.files`).
* **Bases de Datos SQL (`DBI` + `dbplyr`):** Conexión a motores relacionales (SQLite, PostgreSQL, MariaDB) y ejecución de consultas mediante evaluación perezosa (*lazy evaluation*).

---

## 📁 Estructura del Repositorio

```text
.
├── Manejo_de_datos.qmd       # Archivo fuente de la presentación
├── styles.css                 # Estilos visuales
├── Imagenes/                  # Recursos gráficos
└── Datos/                     # Datasets de práctica (.csv, .xlsx, .gz, .sqlite)