
# Plan de Pruebas – Analisis-QA-Argentina.gob

## 1. Introducción

Este documento describe el plan de pruebas para el análisis QA manual del sitio:  
https://www.argentina.gob.ar/  

El objetivo es evaluar la calidad funcional, la usabilidad básica y ciertos aspectos de accesibilidad y comportamiento responsive, con fines didácticos.

---

## 2. Objetivos de las pruebas

- Verificar el correcto funcionamiento de las funcionalidades principales del sitio.
- Identificar defectos funcionales, de navegación y de contenido.
- Detectar problemas básicos de accesibilidad (contraste, etiquetas, foco).
- Evaluar el comportamiento en diferentes tamaños de pantalla.
- Generar documentación clara y reutilizable para un portafolio QA.

---

## 3. Alcance

### 3.1 Incluido en el alcance

- Página principal (Home).
- Buscador principal.
- Navegación por menú.
- Sección “Trámites” (navegación y enlaces principales).
- Formularios simples (si están disponibles sin login).
- Elementos básicos de accesibilidad (texto alternativo, contraste, foco).
- Comportamiento responsive en:
  - Mobile (≈ 360px)
  - Tablet (≈ 768px)
  - Desktop (≥ 1366px)

### 3.2 Fuera de alcance

- Pruebas de backend / APIs.
- Pruebas de seguridad avanzada.
- Pruebas de rendimiento a gran escala.
- Flujos que requieran autenticación con datos reales.
- Validación legal de contenido.

---

## 4. Tipos de pruebas

- Pruebas funcionales.
- Pruebas exploratorias.
- Pruebas de regresión ligera (sobre flujos clave).
- Pruebas de accesibilidad básica (WCAG 2.1 nivel AA, parcialmente).
- Pruebas de UI/UX (coherencia visual, alineación, legibilidad).
- Pruebas responsive (mobile, tablet, desktop).
- Pruebas de enlaces (link testing).

---

## 5. Criterios de entrada

Las pruebas pueden comenzar cuando:

- El sitio es accesible públicamente.
- Se dispone de un entorno estable (producción).
- Se han definido los módulos a evaluar.
- Se cuenta con al menos un conjunto inicial de casos de prueba documentados.

---

## 6. Criterios de salida

Las pruebas se consideran completadas cuando:

- Se han ejecutado los casos de prueba definidos para el alcance.
- Los defectos críticos y altos han sido identificados y documentados.
- No se detectan nuevos defectos críticos en una pasada exploratoria final.
- La documentación (casos de prueba y bugs) está actualizada en el repositorio.

---

## 7. Riesgos y supuestos

### 7.1 Riesgos

- Cambios en producción durante el análisis que alteren el comportamiento.
- Contenido dinámico que genere resultados variables.
- Limitaciones de tiempo para explorar todas las secciones del sitio.

### 7.2 Supuestos

- El sitio se mantendrá disponible durante el período de análisis.
- No se requiere acceso a entornos internos ni credenciales especiales.
- El análisis es observacional y no intrusivo.

---

## 8. Entregables

- Plan de pruebas (`/test-plan/plan-de-pruebas.md`).
- Casos de prueba (`/test-cases/*.md`).
- Matriz de trazabilidad (opcional, `/test-cases/matriz-de-trazabilidad.*`).
- Reportes de bugs (`/bug-reports/*.md`).
- Checklists de QA (`/tools/*.md`).
- Documentación didáctica (`/docs/*.md`).

---

## 9. Herramientas

- Navegadores: Chrome, Firefox.
- Chrome DevTools.
- Lighthouse.
- WAVE (extensión de accesibilidad).
- Hojas de cálculo (Excel / Google Sheets).
- Herramientas de captura de pantalla.

---

## 10. Estrategia de ejecución

1. Realizar una exploración inicial del sitio para identificar flujos clave.
2. Definir y documentar casos de prueba para:
   - Home
   - Buscador
   - Navegación
   - Trámites
   - Accesibilidad básica
3. Ejecutar los casos de prueba y registrar resultados.
4. Documentar los defectos encontrados en formato de bug report.
5. Realizar una pasada exploratoria final para detectar defectos adicionales.
6. Actualizar documentación y cerrar el ciclo de pruebas.


