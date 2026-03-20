# 🔍 Casos de Prueba – Buscador

## 🔹 TC-B01 – Verificar funcionamiento básico del buscador
**Objetivo:** Validar que el buscador acepte texto y muestre resultados.  
**Pasos:**  
1. Escribir “pasaporte”.  
2. Presionar Enter.  
**Resultado esperado:**  
Se muestran resultados relacionados.

---

## 🔹 TC-B02 – Validar búsqueda con términos inexistentes
**Objetivo:** Verificar comportamiento ante búsquedas sin resultados.  
**Pasos:**  
1. Escribir “asdfghjk”.  
2. Presionar Enter.  
**Resultado esperado:**  
Se muestra mensaje de “sin resultados”.

---

## 🔹 TC-B03 – Validar búsqueda con mayúsculas/minúsculas
**Objetivo:** Verificar que no sea case-sensitive.  
**Pasos:**  
1. Buscar “PASAPORTE”.  
2. Buscar “pasaporte”.  
**Resultado esperado:**  
Ambas búsquedas devuelven los mismos resultados.

---

## 🔹 TC-B04 – Validar búsqueda con acentos
**Objetivo:** Verificar que el buscador interprete acentos.  
**Pasos:**  
1. Buscar “educación”.  
2. Buscar “educacion”.  
**Resultado esperado:**  
Ambas búsquedas devuelven los mismos resultados.

---

## 🔹 TC-B05 – Validar autocompletado
**Objetivo:** Verificar sugerencias mientras se escribe.  
**Pasos:**  
1. Escribir “pas”.  
**Resultado esperado:**  
Se muestran sugerencias relacionadas.

---

## 🔹 TC-B06 – Validar accesibilidad del buscador
**Objetivo:** Verificar uso con teclado.  
**Pasos:**  
1. Navegar con TAB hasta el buscador.  
2. Escribir un término.  
3. Presionar Enter.  
**Resultado esperado:**  
El buscador funciona sin mouse.

---

## 🔹 TC-B07 – Validar foco visible
**Objetivo:** Verificar estilo del foco.  
**Pasos:**  
1. Navegar con TAB.  
**Resultado esperado:**  
El foco es visible.

---

## 🔹 TC-B08 – Validar búsqueda con espacios
**Objetivo:** Verificar que ignore espacios innecesarios.  
**Pasos:**  
1. Buscar “   pasaporte   ”.  
**Resultado esperado:**  
Resultados iguales a “pasaporte”.

---

## 🔹 TC-B09 – Validar búsqueda vacía
**Objetivo:** Verificar comportamiento sin texto.  
**Pasos:**  
1. Dejar el buscador vacío.  
2. Presionar Enter.  
**Resultado esperado:**  
No se realiza búsqueda o se muestra mensaje adecuado.

---

## 🔹 TC-B10 – Validar enlaces dentro de resultados
**Objetivo:** Verificar que los resultados sean clickeables.  
**Pasos:**  
1. Realizar una búsqueda válida.  
2. Hacer clic en los primeros 3 resultados.  
**Resultado esperado:**  
Cada enlace redirige correctamente.
