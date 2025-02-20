# Día 2: Aplicaciones Prácticas

## 🎯 Objetivo
Desarrollar un prototipo funcional que utilice **LLMs y/o RAG** aplicados a documentos históricos, integrando los conceptos aprendidos en los talleres anteriores. Además, se explorará la posibilidad de utilizar **Label Studio** para anotar, validar y mejorar los resultados generados por los modelos de IA.

---

## 🏗️ Estructura del Día 2

### 1️⃣ **Formación de Equipos (30 min)**
- Se conformarán equipos mixtos con participantes de ambos talleres.
- Cada equipo definirá un problema a resolver con LLMs y/o RAG.
- Ejemplo de proyectos:
  - Asistente de archivo que responde consultas sobre documentos históricos.
  - Sistema de búsqueda semántica para documentos del siglo XIX.
  - Generador automático de resúmenes y metadatos para archivos históricos.

### 2️⃣ **Opcional: Uso de Label Studio para Anotación y Validación**
Para mejorar los resultados obtenidos con LLMs y RAG, los participantes pueden utilizar [Label Studio](https://labelstud.io/) como herramienta de apoyo en la validación y optimización de los modelos. Su uso se aplicará de la siguiente manera:

#### **🔹 Grupo Python (Taller 1 - LLMs y APIs)**
📍 **Objetivo:** Evaluar y mejorar la extracción automática de información con LLMs.

✅ **Flujo de trabajo:**
1. **Subir documentos históricos a Label Studio** en formato **TXT o CSV**.
2. **Anotar manualmente** entidades clave como **personas, lugares y fechas**.
3. **Ejecutar un LLM (Cohere/Hugging Face) en Python** para extraer automáticamente esas entidades.
4. **Comparar los resultados de la IA con las anotaciones humanas**.
5. **Ajustar los modelos** basándose en los errores detectados, mejorando la extracción y análisis.

📌 **Resultado esperado:** Un dataset validado con **entidades extraídas** y un modelo optimizado para mejorar futuras consultas.

---

#### **🔹 Grupo No-Code (Taller 2 - RAG sin programación)**
📍 **Objetivo:** Validar y mejorar la recuperación de información usando **RAG**.

✅ **Flujo de trabajo:**
1. **Subir documentos históricos a Label Studio** en **TXT o CSV**.
2. **Realizar preguntas a los documentos usando RAG** en **Vectara, ChatBees o Nuclia**.
3. **Comparar las respuestas de RAG con anotaciones manuales**:
   - ¿La IA extrae la información correcta?
   - ¿Las fuentes citadas son relevantes?
4. **Marcar errores y ajustar la indexación** para mejorar la precisión.

📌 **Resultado esperado:** Un sistema RAG optimizado con respuestas **más precisas y verificadas**.

---

### 3️⃣ **Desarrollo del Prototipo (3-4 horas)**
Cada equipo trabajará en:
- **Grupo Python:** Creará un script para interactuar con APIs de LLMs y podrá validar sus resultados en Label Studio si decide utilizarlo.
- **Grupo No-Code:** Configurará una plataforma RAG para consultas documentales y podrá ajustar la indexación usando Label Studio si lo considera necesario.

🚀 **Herramientas disponibles:**
- Google Colab para ejecución de código Python.
- Vectara, ChatBees o Nuclia para integración sin código.
- Corpus histórico de ejemplo para pruebas.
- **Label Studio** como herramienta opcional para anotación, validación y mejora de resultados IA.

---

### 4️⃣ **Presentación de Resultados (1 hora)**
- Cada equipo dispondrá de **5 minutos** para presentar su proyecto.
- Se dará retroalimentación entre equipos y se discutirán mejoras.

📌 **Criterios de evaluación:**
- **Innovación:** Creatividad en la aplicación de IA.
- **Funcionalidad:** Capacidad del prototipo para resolver consultas reales.
- **Claridad:** Explicación concisa y demostración práctica.
- **Uso efectivo de herramientas adicionales**, como Label Studio si se decidió implementar.

---

## 🏆 **Resultado esperado**
Cada equipo contará con un prototipo funcional basado en **LLMs y/o RAG** aplicado a documentos históricos, con la opción de haber mejorado sus resultados mediante el uso de **Label Studio**.

🚀 **¡Felicitaciones por llegar hasta aquí!** Ahora pueden seguir refinando sus proyectos y explorar nuevas aplicaciones en humanidades digitales.

