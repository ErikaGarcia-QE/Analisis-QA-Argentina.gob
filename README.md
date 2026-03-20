# Analisis-QA-Argentina.gob
Analisis con fines didacticos con ejemplos prácticos

**Repositorio didáctico con ejemplos prácticos de análisis QA manual**

Este proyecto presenta un análisis QA realizado sobre el sitio oficial del Gobierno de Argentina:  
https://www.argentina.gob.ar/

El objetivo es **mostrar de forma didáctica** cómo se estructura, documenta y ejecuta un proceso de testing profesional, incluyendo ejemplos reales, buenas prácticas y documentación clara.

---

## 📚 Objetivos del repositorio

- Demostrar habilidades de QA Manual con un caso real.
- Presentar documentación profesional y organizada.
- Enseñar cómo estructurar un análisis QA dentro de un repositorio GitHub.
- Aplicar buenas prácticas recomendadas por GitHub para README y repositorios.
- Incluir ejemplos prácticos: casos de prueba, reportes de bugs, checklists y análisis.

---

## 🧭 Contenido del repositorio

| Carpeta | Descripción |
|--------|-------------|
| **/test-plan** | Plan de pruebas, alcance, criterios, riesgos y estrategia |
| **/test-cases** | Casos de prueba funcionales, exploratorios y de accesibilidad |
| **/bug-reports** | Reportes de bugs con severidad, prioridad y evidencia |
| **/tools** | Checklists de QA (UI, accesibilidad, responsive) |
| **/docs** | Material didáctico adicional, ejemplos y guías |

---

## 📝 Ejemplo práctico: Caso de prueba

```markdown
### TC-001 – Validación del buscador principal

**Módulo:** Home  
**Objetivo:** Verificar que el buscador devuelva resultados relevantes  
**Precondiciones:** Navegador abierto en https://www.argentina.gob.ar/  

**Pasos:**
1. Ingresar “pasaporte” en el buscador.
2. Presionar Enter.

**Resultado esperado:**  
Se muestran resultados relacionados con trámites de pasaporte.

**Resultado obtenido:**  
Se muestran resultados no relacionados (ej.: noticias generales).

**Estado:** Fallido  
