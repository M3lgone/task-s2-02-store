# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 16 correctas de 26 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.37 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 5: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nom del producte | euros | dòlars
+nombre_del_producto | euros | dolares
 Disco duro SATA3 1TB | 86.99 | 95.69
 Memoria RAM DDR4 8GB | 120.00 | 132.00
 Disco SSD 1 TB | 150.99 | 166.09
```

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio
+upper(nombre) | precio
 DISCO DURO SATA3 1TB | 86.99
 MEMORIA RAM DDR4 8GB | 120.00
 DISCO SSD 1 TB | 150.99
```

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 7: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio
+LOWER(nombre) | precio
 disco duro sata3 1tb | 86.99
 memoria ram ddr4 8gb | 120.00
 disco ssd 1 tb | 150.99
```

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 8: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,10 @@
 nombre | iniciales
-Asus | AS
-Lenovo | LE
-Hewlett-Packard | HE
-Samsung | SA
-Seagate | SE
-Crucial | CR
-Gigabyte | GI
-Huawei | HU
-Xiaomi | XI
+Asus | ASus
+Lenovo | LEnovo
+Hewlett-Packard | HEwlett-packard
+Samsung | SAmsung
+Seagate | SEagate
+Crucial | CRucial
+Gigabyte | GIgabyte
+Huawei | HUawei
+Xiaomi | XIaomi
```

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 10: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio truncado
-Disco duro SATA3 1TB | 86.00
+nombre | precio_truncado
+Disco duro SATA3 1TB | 86.90
 Memoria RAM DDR4 8GB | 120.00
-Disco SSD 1 TB | 150.00
+Disco SSD 1 TB | 150.90
 GeForce GTX 1050Ti | 185.00
 GeForce GTX 1080 Xtreme | 755.00
 Monitor 24 LED Full HD | 202.00
-Monitor 27 LED Full HD | 245.00
+Monitor 27 LED Full HD | 245.90
 Portátil Yoga 520 | 559.00
 Portátil Ideapd 320 | 444.00
-Impresora HP Deskjet 3720 | 59.00
+Impresora HP Deskjet 3720 | 59.90
 Impresora HP Laserjet Pro M26nw | 180.00
```

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 21: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio | nombre del fabricante
+producto | precio | fabricante
 Disco duro SATA3 1TB | 86.99 | Seagate
 Memoria RAM DDR4 8GB | 120.00 | Crucial
 Disco SSD 1 TB | 150.99 | Samsung
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 22: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio | nombre del fabricante
+nombre | precio | nombre_del_fabricante
 Monitor 24 LED Full HD | 202.00 | Asus
 Monitor 27 LED Full HD | 245.99 | Asus
 Memoria RAM DDR4 8GB | 120.00 | Crucial
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 23: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-codigo | nombre | codigo fabricante | nombre fabricante
+codigo | nombre | codigo_fabricante | nombre_del_fabricante
 1.00 | Disco duro SATA3 1TB | 5.00 | Seagate
 2.00 | Memoria RAM DDR4 8GB | 6.00 | Crucial
 3.00 | Disco SSD 1 TB | 4.00 | Samsung
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 24: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio | fabricant
+nombre | precio | fabricante
 Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
```

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 25: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 26: Error
- **Descripción**: 'NoneType' object is not iterable

