# ✈️ GDS AI-Assistant: Solución Integral de Contingencias

## 📝 Introducción
Este proyecto nace de la necesidad de estandarizar y agilizar la resolución de incidencias críticas en agencias de viajes. Utiliza **IA (Generative AI)** para interpretar normativas aéreas complejas y traducirlas en pasos legales y comandos técnicos de GDS (Amadeus/Sabre).

## 🚀 Funcionalidades (Escalabilidad)
A diferencia de soluciones aisladas, este asistente es capaz de procesar múltiples categorías de incidencias:
* **Menores (UMNR):** Protocolos Kids Solo y servicios de acompañamiento.
* **Reemisiones:** Cotización de cambios, penalidades y comandos de revalidación.
* **Ancillaries:** Gestión de asientos y servicios adicionales.
* **Documentación:** Pasos legales ante robos o falta de permisos.

## 🧠 Metodología: Fast Prompting
La POC (Proof of Concept) implementa técnicas avanzadas de prompting:
* **Role Prompting:** El modelo asume el rol de un Agente Senior de Operaciones.
* **Dynamic System Prompt:** La instrucción de la IA cambia según el trámite elegido, mejorando la precisión técnica.
* **Eficiencia de Costos:** Se optimiza el uso de tokens enviando todo el contexto en una única consulta estructurada.

## 🛠️ Tecnologías utilizadas
* **Python:** Lógica del motor técnico.
* **Ipywidgets:** Interfaz de usuario interactiva dentro de la Notebook.
* **OpenAI API / Gemini:** Modelos de lenguaje para el procesamiento de normativas.

---
**Autor:** Fabricio Tammaro  
**Diplomatura en IA: Generación de Prompts**
