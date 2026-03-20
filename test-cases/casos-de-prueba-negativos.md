# ❌ Casos de Prueba Negativos

## 🔹 TC-N01 – Búsqueda con caracteres especiales
**Objetivo:** Validar que el buscador maneje caracteres no válidos.  
**Pasos:**  
1. Ingresar “@@@###” en el buscador.  
2. Presionar Enter.  
**Resultado esperado:**  
El sistema muestra mensaje de “sin resultados” o ignora caracteres inválidos.

---

## 🔹 TC-N02 – Búsqueda extremadamente larga
**Objetivo:** Validar que el sistema maneje inputs excesivos.  
**Pasos:**  
1. Ingresar un texto de más de 300 caracteres.  
2. Presionar Enter.  
**Resultado esperado:**  
El sistema no se rompe y muestra mensaje adecuado.

---

## 🔹 TC-N03 – Búsqueda con emojis
**Objetivo:** Validar que el buscador maneje caracteres Unicode.  
**Pasos:**  
1. Ingresar “✈️🇦🇷😊”.  
2. Presionar Enter.  
**Resultado esperado:**  
El sistema devuelve “sin resultados” sin errores.

---

## 🔹 TC-N04 – Home sin conexión
**Objetivo:** Validar comportamiento ante pérdida de red.  
**Pasos:**  
1. Desactivar conexión.  
2. Intentar cargar el Home.  
**Resultado esperado:**  
Se muestra mensaje del navegador sin romper el layout.

---

## 🔹 TC-N05 – Menú mobile sin JavaScript
**Objetivo:** Validar degradación funcional.  
**Pasos:**  
1. Desactivar JavaScript.  
2. Abrir menú mobile.  
**Resultado esperado:**  
El menú no funciona, pero el sitio no se rompe.
