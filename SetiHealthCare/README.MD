# 💡 Machine Learning e Inteligencia Artificial con KNIME  
### Un acercamiento No-Code / Low-Code

## 🔗 Recursos oficiales de KNIME
- 🌐 **Sitio web oficial:** [https://www.knime.com](https://www.knime.com)  
- 📚 **Documentación:** [https://docs.knime.com](https://docs.knime.com)  
- 💻 **Descarga KNIME Analytics Platform:** [https://www.knime.com/downloads](https://www.knime.com/downloads)  
- 🎓 **KNIME Learning Hub (Cursos y certificaciones):** [https://www.knime.com/learning-hub](https://www.knime.com/learning-hub)  
- 🧩 **Extensiones y componentes:** [https://hub.knime.com](https://hub.knime.com)

---

## 🧠 ¿Qué es KNIME?

**KNIME (Konstanz Information Miner)** es una plataforma **open-source** para **análisis de datos, Machine Learning y ciencia de datos**, diseñada para permitir a usuarios sin conocimientos avanzados de programación construir flujos analíticos complejos mediante una interfaz visual e intuitiva.  

Sus principales características son:
- **No-Code / Low-Code:** ideal para científicos de datos, analistas y profesionales de negocio.  
- **Integración flexible:** conecta múltiples fuentes de datos y herramientas externas.  
- **Automatización y colaboración:** permite crear y compartir flujos reutilizables.  
- **Escalabilidad:** trabaja con grandes volúmenes de datos en entornos locales o en la nube.  
- **Extensible:** se integra con Python, R, TensorFlow, Spark, y más.  

KNIME impulsa la **toma de decisiones basada en datos**, mejora la **eficiencia operativa** y **democratiza la analítica avanzada** dentro de las organizaciones.

---

## 🧩 Resumen de la presentación: *“Charla - ML IA”*

### 1. Introducción  
La charla plantea un **acercamiento práctico al Machine Learning (ML) y la Inteligencia Artificial (IA)** usando plataformas **No-Code / Low-Code** como KNIME.  
Se destacan dos paradigmas:
- **Computational:** la capacidad de automatizar cálculos y análisis.  
- **Inferential:** la habilidad de obtener conclusiones basadas en patrones de datos.

---

### 2. ¿Por qué No-Code / Low-Code?

| Beneficio | Descripción |
|------------|-------------|
| **Facilidad de uso** | Permite que usuarios no técnicos adopten herramientas avanzadas. |
| **Mayor engagement** | Fomenta el entendimiento y la experimentación directa con modelos de IA. |
| **Soluciones locales** | Facilita crear prototipos rápidos que luego pueden escalarse a soluciones empresariales. |

---

### 3. Caso de estudio: **Seguros SETI**

**Contexto:**  
Seguros SETI busca crear un **modelo de precios predictivo** para seguros médicos, considerando hábitos, edad y condiciones del asegurado, con el fin de ofrecer productos más justos y competitivos.

**Concepto clave:**  
> “El riesgo individual no refleja el colectivo. La ley de grandes números permite predecir comportamientos agregados.”

---

### 4. Preparación de datos

El proceso incluyó:
- **Conversión de datos alfanuméricos a numéricos**, ya que los modelos de ML requieren variables cuantitativas.  
- **Eliminación de columnas originales** para evitar redundancia.  
- **EDA (Exploratory Data Analysis):**
  - La **edad** mostró mayor correlación con el monto de las reclamaciones.  
  - El **número de hijos** tiene baja correlación directa con las reclamaciones, pero cierta relación con el **IMC**.  
  - Las **regiones** presentan valores promedio similares, aunque el **southeast** muestra una ligera elevación.  
  - Los **fumadores** presentan reclamaciones promedio casi **el doble** de los no fumadores, con picos máximos **casi triples**.

---

### 5. Aplicación de Machine Learning

- Se aplicó una **red neuronal con el algoritmo RPROP** para predecir el valor de las reclamaciones.  
- El modelo mostró buena alineación entre los valores **predichos** y los **reales**.  
- Ejemplos de aplicaciones derivadas:
  - Predicción de la **ejecución de proyectos** según el rendimiento de equipos (EVC).  
  - Estimación de **costos y desviaciones** respecto a líneas base.  
  - **Análisis de historias de usuario** para detectar complejidad o riesgo de incumplimiento.

---

### 6. Conclusiones

KNIME demuestra que la **IA y el ML pueden ser accesibles sin escribir código**, promoviendo un aprendizaje práctico y colaborativo.  
El enfoque **No-Code / Low-Code** permite a las empresas acelerar la adopción de analítica avanzada y generar valor desde la experimentación hasta la producción.

---

### 🏁 Agradecimientos
> ¡Muchas gracias por participar y explorar el poder de KNIME y el aprendizaje automático accesible!
