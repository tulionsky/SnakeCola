# 🐍 Explicación del Código del Juego de Snake usando Colas

Este repositorio contiene diferentes versiones del clásico juego de **Snake**, con implementaciones progresivas que exploran el uso de **colas** para gestionar el cuerpo de la serpiente.

## 📌 Versiones del Código

### 1️⃣ Snake
Este es el código inicial donde la serpiente se representa usando un **array**. Es una implementación básica sin colas.

### 2️⃣ Snake2 (Código con errores)
Este código fue adaptado por Claude para utilizar una **cola**, pero presenta un problema:  
Cuando la serpiente crece al comer, **su cuerpo se genera en una posición incorrecta**, lo que provoca una colisión instantánea y hace que el jugador pierda.

### 3️⃣ Snake1 (Código de referencia)
Solicité a Claude que escribiera una versión completamente nueva desde cero.  
Este código funciona correctamente y me ayudó a identificar que el problema en **Snake2** estaba en la **gestión de colisiones** y la forma en que se añadían nuevos segmentos al cuerpo de la serpiente.

### 4️⃣ Snake3 (Código final y funcional ✅)
Este es el código definitivo que **usa una cola de manera correcta**.  
- Se inicializa con una **Queue**.
- La posición inicial se gestiona con un **enqueue**.
- Se corrigieron los errores de **Snake2**.
- Ahora el juego funciona sin ningún problema. 🎉

