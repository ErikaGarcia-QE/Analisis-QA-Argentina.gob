# Casos de Prueba – Buscador del sitio https://www.argentina.gob.ar/

Este documento contiene los casos de prueba diseñados para validar el correcto funcionamiento del buscador, incluyendo resultados, comportamiento, accesibilidad y manejo de errores.

---

## 🔹 TC-B01 – Verificar funcionamiento básico del buscador
**Objetivo:** Validar que el buscador acepte texto y muestre resultados.  
**Precondición:** Home cargado correctamente.

**Pasos:**
1. Ingresar al Home.
2. Escribir “pasaporte” en el buscador.
3. Presionar Enter.

**Resultado esperado:**  
Se muestran resultados relacionados con “pasaporte”.

---

## 🔹 TC-B02 – Validar búsqueda con términos inexistentes
**Objetivo:** Verificar el comportamiento ante búsquedas sin resultados.

**Pasos:**
1. Escribir “asdfghjk” en el buscador.
2. Presionar Enter.

**Resultado esperado:**  
El sistema muestra un mensaje indicando que no hay resultados.

---

## 🔹 TC-B03 – Validar búsqueda con mayúsculas y minúsculas
**Objetivo:** Verificar que el buscador no sea case-sensitive.

**Pasos:**
1. Buscar “PASAPORTE”.
2. Buscar “pasaporte”.

**Resultado esperado:**  
Ambas búsquedas devuelven los mismos resultados.

---

## 🔹 TC-B04 – Validar búsqueda con acentos
**Objetivo:** Verificar que el buscador interprete correctamente caracteres acentuados.

**Pasos:**
1. Buscar “educación”.
2. Buscar “educacion”.

**Resultado esperado:**  
Ambas búsquedas devuelven los mismos resultados.

---

## 🔹 TC-B05 – Validar autocompletado (si aplica)
**Objetivo:** Verificar que el buscador sugiera términos mientras se escribe.

**Pasos:**
1. Escribir “pas”.
2. Observar sugerencias.

**Resultado esperado:**  
Se muestran sugerencias relacionadas.

---

## 🔹 TC-B06 – Validar accesibilidad del buscador
**Objetivo:** Verificar que el buscador sea accesible mediante teclado.

**Pasos:**
1. Navegar con TAB hasta el buscador.
2. Escribir un término.
3. Presionar Enter.

**Resultado esperado:**  
El buscador funciona sin necesidad de mouse.

---

## 🔹 TC-B07 – Validar foco visible en el campo de búsqueda
**Objetivo:** Verificar que el foco sea visible al seleccionar el buscador.

**Pasos:**
1. Navegar con TAB hasta el campo.
2. Observar el estilo del foco.

**Resultado esperado:**  
El foco es claro y visible.

---

## 🔹 TC-B08 – Validar búsqueda con espacios al inicio o final
**Objetivo:** Verificar que el sistema ignore espacios innecesarios.

**Pasos:**
1. Buscar “   pasaporte   ”.
2. Presionar Enter.

**Resultado esperado:**  
Los resultados son los mismos que para “pasaporte”.

---

## 🔹 TC-B09 – Validar búsqueda vacía
**Objetivo:** Verificar el comportamiento cuando el usuario no ingresa texto.

**Pasos:**
1. Dejar el buscador vacío.
2. Presionar Enter.

**Resultado esperado:**  
El sistema no realiza búsqueda o muestra un mensaje adecuado.

---

## 🔹 TC-B10 – Validar enlaces dentro de los resultados
**Objetivo:** Verificar que los resultados sean clickeables y funcionen.

**Pasos:**
1. Realizar una búsqueda válida.
2. Hacer clic en los primeros 3 resultados.

**Resultado esperado:**  
Cada enlace redirige correctamente a su página.

---
