# 📝 Bitácora de Investigación - Gran Hotel Olimpo
**Equipo Auditor:** [Nombre Piloto] & [Nombre Copiloto]  
**Fecha:** [DD/MM/AAAA]

---

## 1. 🔑 Hallazgo Inicial (Puerta 1 - Git Bash)
* **Comando utilizado para encontrar la credencial oculta:** `ls -la`
* **Código de la Llave Maestra:** `GH-OLIMPO-DATA-2026-KEY`
* **Primera anomalía detectada en el servidor:** Se encontraron 10 filas totalmente duplicadas en el archivo data/reservas_raw.csv, además de valores vacíos (NaN) en las columnas de precios y noches.

---

## 2. 🛡️ Registro de Control de Versiones (Puerta 2 - Git & GitHub)
* **Comando para preparar archivos (Staging):** `git add README.md`
* **Mensaje del primer commit local:** `Initial commit`
* **URL del repositorio público en GitHub:** `https://github.com/superco-art/gran-hotel-data-escape`

---

## 3. 🗺️ Arquitectura y Entorno (Puerta 4 - VS Code & Dependencies)
* **Versión de Python detectada:** `Python 3.12.10`
* **Comando utilizado para instalar `requirements.txt`:** `py -3.12 -m pip install -r requirements.txt`
* **Diferencia entre Ruta Absoluta y Ruta Relativa (explicación breve):** Una ruta absoluta indica la ubicación completa de un archivo en el ordenador.

Una ruta relativa indica la ubicación de un archivo tomando como referencia la carpeta del proyecto.

---

## 4. ⚙️ Conciliación Financiera (Puerta 5 - Python CLI)
* **Facturación Bruta (Sin filtrar):** `52.755,00 €`
* **Facturación Neta Real (Solo Completadas):** `29.905,00 €`
* **Fuga Financiera (Canceladas + Devueltas):** `32.850,00 €`
* **Conclusión de Negocio:** No debemos tomar decisiones basándonos únicamente en la facturación bruta, porque incluye reservas canceladas y devueltas que no representan ingresos reales para el hotel. La facturación neta de las reservas completadas es de 29.905 €, por lo que debemos utilizar esta cifra para evaluar los ingresos reales del negocio.

---

## 5. 🔮 Auditoría Final e IA Generativa (Puerta 6 - Jupyter & Prompting)
* **Número de duplicados exactos eliminados:** `...`
* **Respuesta de la LLM tras enviar el Prompt Estructurado:**
  > [Pegar aquí la síntesis generada por la IA]
* **Verificación de Factualidad y Sesgos (Guardrails):**
  - ¿La IA inventó algún dato que no estuviera en el contexto? (Sí/No y detalle):
  - ¿El lenguaje utilizado es neutro y libre de sesgos de culpabilidad?

---

## 🏁 Semáforo de Autoevaluación Individual
* **Piloto:** 🟢 Verde / 🟡 Amarillo / 🔴 Rojo — *Comentario:*
* **Copiloto:** 🟢 Verde / 🟡 Amarillo / 🔴 Rojo — *Comentario:*