# 📘 Actividad de Análisis y Solución de Algoritmos

<div align="center">

# 📚 Actividad de Análisis y Solución de Algoritmos

### 🔍 Algoritmos Secuenciales y Condicionales

![GitHub](https://img.shields.io/badge/GitHub-Compatible-success?style=for-the-badge)
![Markdown](https://img.shields.io/badge/Markdown-Documentación-blue?style=for-the-badge)
![Diagramas](https://img.shields.io/badge/Diagramas-Flujo-orange?style=for-the-badge)

---

*Desarrollo de situaciones problema, análisis de algoritmos y diagramas de flujo.*

</div>

---

# 📖 Situaciones de Ejemplo

---

## 🟦 Situación/Ejemplo 1

### 💼 Cálculo del Ingreso Semestral de un Empleado

---

### 📝 Planteamiento
> Analicemos el siguiente problema y representemos su solución mediante un algoritmo secuencial.

**Problema:**

* Construye un algoritmo que, al recibir como datos **el ID** del empleado y los seis primeros sueldos del año, calcule el ingreso total semestral y el promedio mensual, e imprima el ID del empleado, el ingreso total y el promedio mensual.

---

### ✅ Solución

> El algoritmo comienza solicitando el **ID del empleado** y los seis sueldos correspondientes al primer semestre del año (**S1, S2, S3, S4, S5 y S6**).
>
> A continuación, suma los seis salarios para obtener el **Ingreso Total (IT)** del semestre.
>
> Después, calcula el **Promedio Mensual (PM)** dividiendo el ingreso total entre seis.
>
> Finalmente, muestra el **ID del empleado**, el **ingreso total semestral** y el **promedio mensual**, y termina la ejecución del proceso.

---

### 🖼️ Diagrama de Flujo

<div align="center">

![Caso 1](./Imagenes/Diagrama1.png)

</div>

---

### 📥 Datos de Entrada

| NOMBRE | DEFINICIÓN | TIPO   | UNIDAD |
| ------ | ---------- | ------ | ------ |
| ID     |            | Entero | -      |
| S1-S6  |            | Real   | $      |

---

### 📤 Datos de Salida

| NOMBRE | DEFINICIÓN | TIPO   | UNIDAD |
| ------ | ---------- | ------ | ------ |
| ID     |            | Entero | -      |
| IT     |            | Real   | $      |
| PM     |            | Real   | $      |

---

## 🟦 Situación/Ejemplo 2

### 🎂 Cálculo de Edad y Verificación de Cumpleaños

---

### 📝 Planteamiento
> Analicemos el siguiente problema y representemos su solución mediante un algoritmo secuencial.

**Problema:**

* Construye un algoritmo que reciba como datos la fecha de nacimiento de una persona (año, mes y día) y la fecha actual (año, mes y día). El algoritmo deberá calcular la edad actual de la persona y determinar si ya ha cumplido años en el año en curso. Finalmente, deberá mostrar la edad correspondiente y un mensaje indicando si la persona ya cumplió años o si aún no ha llegado la fecha de su cumpleaños.

---

### ✅ Solución

> El algoritmo recibe como datos la fecha de nacimiento de una persona (año, mes y día) y la fecha actual.
>
> Primero calcula una edad preliminar restando el año de nacimiento al año actual.
>
> Luego compara el mes actual con el mes de nacimiento para determinar si el cumpleaños ya ocurrió durante el año en curso.
>
> Si el mes actual es mayor que el mes de nacimiento, se considera que la persona ya cumplió años y se muestra la edad calculada.
>
> En caso contrario, se verifica si el día actual es igual o mayor que el día de nacimiento.
>
> Si esta condición se cumple, también se considera que ya cumplió años; de lo contrario, se indica que aún no ha cumplido años.
>
> Finalmente, el algoritmo muestra el resultado correspondiente y termina su ejecución.

---

### 🖼️ Diagrama de Flujo

<div align="center">

![Situación 2](./Imagenes/Diagrama2.png)

</div>

---

### 📥 Datos de Entrada

| NOMBRE | DEFINICIÓN        | TIPO   | UNIDAD |
| ------ | ----------------- | ------ | ------ |
| Año_N  | Año de Nacimiento | Entero | -      |
| Año_A  | Año Actual        | Entero | -      |
| Mes_N  | Mes de Nacimiento | Entero | -      |
| Mes_A  | Mes Actual        | Entero | -      |
| Día_N  | Día de Nacimiento | Entero | -      |
| Día_A  | Día Actual        | Entero | -      |

---

### 📤 Datos de Salida

| NOMBRE    | DEFINICIÓN | TIPO | UNIDAD |
| --------- | ---------- | ---- | ------ |
| Cumple Hb |            | -    | -      |

---

# 🧩 Ejercicios de Práctica

---

## 🟩 Ejercicio 1

### 🐠 Capacidad de un Acuario

---

### 📝 Problema

> Un acuario necesita determinar cuántos litros o galones (eso lo decide el usuario) de agua caben en un acuario, pero solo dispone de una cinta métrica (en centímetros). Diseña un algoritmo para solucionar el problema.

---

### ✅ Solución

> Para resolver el problema, se utilizan como datos de entrada las dimensiones del acuario medidas en centímetros (largo, ancho y alto) y la unidad en la que el usuario desea obtener el resultado (litros o galones).
>
> Con estas medidas se calcula el volumen del acuario y se convierte a litros.
>
> Si el usuario solicita el resultado en galones, se realiza la conversión correspondiente.
>
> Finalmente, el algoritmo muestra la capacidad total del acuario en la unidad seleccionada.

---

### 🖼️ Diagrama de Flujo

<div align="center">

![Ej 1](./Imagenes/Diagrama3.png)

</div>

---

### 📥 Datos de Entrada

| NOMBRE   | DEFINICIÓN          | TIPO     | UNIDAD |
| -------- | ------------------- | -------- | ------ |
| FormaTnq | La forma del tanque | Flotante | -      |
| Largo    | -                   | Entero   | cm     |
| Alto     | -                   | Entero   | cm     |
| Ancho    | -                   | Entero   | cm     |

---

### 📤 Datos de Salida

| NOMBRE                | DEFINICIÓN | TIPO | UNIDAD |
| --------------------- | ---------- | ---- | ------ |
| Capacidad del Acuario | -          | -    | -      |
| Unidad de medida      | -          | -    | -      |

---

## 🟩 Ejercicio 2

### ✏️ Compra de Lápices

---

### 📝 Problema

> Realice un algoritmo para determinar cuánto se debe pagar por equis cantidad de lápices considerando que si son 1000 o más el costo es de $85 cada uno; de lo contrario, el precio es de $90.

---

### ✅ Solución

> Para resolver el problema, se solicita al usuario la cantidad de lápices que desea comprar.
>
> El algoritmo verifica si la cantidad es mayor o igual a 1000 unidades; en ese caso, asigna un precio de $85 por lápiz.
>
> De lo contrario, asigna un precio de $90 por lápiz.
>
> Finalmente, calcula el total a pagar multiplicando la cantidad de lápices por el precio correspondiente y muestra el resultado.

---

### 🖼️ Diagrama de Flujo

<div align="center">

![Ej 2](./Imagenes/Diagrama4.png)

</div>

---

### 📥 Datos de Entrada

| NOMBRE           | DEFINICIÓN        | TIPO   | UNIDAD |
| ---------------- | ----------------- | ------ | ------ |
| Cantidad_Lapices | Numero de lapices | entero | -      |

---

### 📤 Datos de Salida

| NOMBRE     | DEFINICIÓN | TIPO     | UNIDAD |
| ---------- | ---------- | -------- | ------ |
| TotalPagar | -          | Flotante | $      |

---

## 🟩 Ejercicio 3

### 👕 Descuento en Almacén de Ropa

---

### 📝 Problema


> Un almacén de ropa tiene una promoción: por compras superiores a $250 000 se les aplicará un descuento de 15%, de caso contrario, sólo se aplicará un 8% de descuento.

---

### ✅ Solución

*

---

### 🖼️ Diagrama de Flujo

<div align="center">

![Ej 3](./Imagenes/Diagrama4.png)

</div>

---

### 📥 Datos de Entrada

| NOMBRE           | DEFINICIÓN        | TIPO   | UNIDAD |
| ---------------- | ----------------- | ------ | ------ |
| Cantidad_Lapices | Numero de lapices | entero | -      |

---

### 📤 Datos de Salida

| NOMBRE     | DEFINICIÓN | TIPO     | UNIDAD |
| ---------- | ---------- | -------- | ------ |
| TotalPagar | -          | Flotante | $      |

---

## 🟩 Ejercicio 4

### 🚌 Viaje de Estudios

---

### 📝 Problema

> El director de una escuela está organizando un viaje de estudios, y requiere determinar cuánto debe cobrar a cada alumno y cuánto debe pagar a la compañía de viajes por el servicio.

---

### ✅ Solución

*

---

### 🖼️ Diagrama de Flujo

<div align="center">

![Ej 4](./Imagenes/Diagrama4.png)

</div>

---

### 📥 Datos de Entrada

| NOMBRE           | DEFINICIÓN        | TIPO   | UNIDAD |
| ---------------- | ----------------- | ------ | ------ |
| Cantidad_Lapices | Numero de lapices | entero | -      |

---

### 📤 Datos de Salida

| NOMBRE     | DEFINICIÓN | TIPO     | UNIDAD |
| ---------- | ---------- | -------- | ------ |
| TotalPagar | -          | Flotante | $      |

---

<div align="center">

## 🎯 Fin de la Actividad

</div>

---

