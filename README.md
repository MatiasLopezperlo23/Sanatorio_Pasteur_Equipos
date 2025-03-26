# 📊 Análisis de Equipos Médicos por Ubicación – Power BI

## 📌 Descripción del Proyecto

Este proyecto consiste en un **análisis detallado del estado funcional de equipos médicos** del **Sanatorio Pasteur de Catamarca** y otras dos sedes. 

El objetivo principal fue identificar áreas críticas para optimizar el **mantenimiento preventivo** y mejorar la **gestión operativa** de los dispositivos.

A partir de un conjunto de datos con información de **61 equipos**, se diseñó un **dashboard interactivo en Power BI** que permite visualizar el estado de los equipos, su distribución por ubicación y las marcas/modelos más propensos a fallas.

---

## 🎯 Objetivo del Proyecto

- Analizar el **estado funcional** de los equipos (Funciona, No Funciona, Funciona con Fallas).
- Identificar **patrones de fallas** según la **ubicación**, **marca** y **modelo**.
- Desarrollar un **dashboard en Power BI** que facilite el seguimiento y la toma de decisiones.
- Proporcionar **recomendaciones** para mejorar el mantenimiento y la gestión de equipos críticos.

---

## 🗂️ Estructura del Proyecto

```
├── Data/                    # Archivos de datos utilizados (anonimizados si es necesario)
├── Dashboard/               # Archivos .pbix de Power BI
├── Docs/                    # Informes en PDF (Análisis y Conclusiones)
└── README.md                # Descripción del proyecto
```

---

## 🔍 Análisis Realizado

### 1. Procesamiento de Datos
- Limpieza y transformación de los datos con **Power Query**.
- Unificación de información desde múltiples ubicaciones (Pasteur, Misiones, C.S. Javier).

### 2. Modelado de Datos
- Creación de relaciones entre tablas (equipos, ubicación, estado funcional).
- Optimización del modelo para un rendimiento eficiente en **Power BI**.

### 3. Medidas DAX Implementadas
- Total de equipos por estado (Funciona, No Funciona, Funciona con Fallas).
- Porcentaje de equipos funcionales por sede.
- Identificación de las marcas y modelos más propensos a fallas.

---

## 📊 Resultados Clave

- **82%** de los equipos están funcionales, **8%** no funciona y **10%** presenta fallas.
- **Pasteur** es la sede con más equipos no funcionales (11,11%).
- **Misiones** destaca por tener el **100% de sus equipos operativos**.
- Los **ecógrafos Philips** fueron los dispositivos con más fallas recurrentes.

---

## 🛠️ Tecnologías Utilizadas

- **Power BI Desktop**: Creación del dashboard interactivo.
- **Power Query**: Limpieza y transformación de los datos.
- **DAX (Data Analysis Expressions)**: Cálculos y medidas personalizadas.
- **Excel**: Procesamiento previo y exploración inicial de los datos.

---

## 📈 Mejoras Futuras

- Implementar un **sistema automatizado** de actualización de datos en Power BI.
- Ampliar el análisis con **tendencias históricas** de fallas para predicción.
- Integrar alertas para el seguimiento de **equipos críticos**.

---

## 📌 Cómo Ejecutar el Proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/tuusuario/diagnostico-equipos-medicos.git
```

2. Abrir el archivo **.pbix** en **Power BI Desktop**.

3. Explorar el dashboard interactivo.

---

## 📊 Dashboard de Muestra

![Dashboard Preview](ruta/a/imagen_dashboard.png)

---

## 📚 Contribuciones

¡Las contribuciones son bienvenidas! Si tienes alguna mejora o sugerencia, no dudes en crear un **Pull Request** o abrir un **Issue**.

---

✨ **Si te interesa el análisis de datos aplicado a la gestión sanitaria, este proyecto es un ejemplo claro de cómo los datos pueden impulsar decisiones estratégicas.**
