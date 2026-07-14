# 🧮 CoreCalc

> Un motor aritmético modular y eficiente desarrollado en **Java SE**. Este proyecto demuestra buenas prácticas de programación defensiva, manejo de excepciones y validación de operaciones matemáticas mediante una arquitectura estructurada de pruebas.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Build](https://img.shields.io/badge/Build-Apache%20Ant-red?style=for-the-badge&logo=apache-ant&logoColor=white)
![Testing](https://img.shields.io/badge/Testing-Manual%20Harness-blue?style=for-the-badge&logo=codeforces&logoColor=white)

---

## 🛠️ Estructura del Proyecto

El código fuente está dividido limpiamente para separar la lógica del negocio de los escenarios de validación:

*   **`Calculadora.java` (Lógica Core):** Clase encargada de encapsular las operaciones matemáticas básicas (suma, resta, multiplicación y división), controlando casos de error lógicos como la división entre cero.
*   **`PruebaCalculadora.java` (Controlador/Pruebas):** Clase encargada de orquestar la entrada de datos, simular transacciones y validar que el motor aritmético devuelva los resultados esperados bajo diferentes casos de uso.

---

## ✨ Características Técnicas

*   🛡️ **Programación Defensiva:** Control preventivo para impedir el colapso del sistema ante operaciones matemáticas indeterminadas (ej. división por cero).
*   🧪 **Suite de Pruebas Integrada:** Clase controladora que funciona como arnés de pruebas para comprobar la precisión de los cálculos sin interfaces complejas.
*   🧩 **Modularidad:** Métodos de cálculo desacoplados y reutilizables, listos para integrarse en una interfaz gráfica (GUI) o API en el futuro.

---

## 🚀 Cómo Ejecutar el Proyecto

### Requisitos previos
*   Tener instalado el **Java Development Kit (JDK 8 o superior)**.

### Instrucciones de ejecución
1. **Clona este repositorio:**
   ```bash
   git clone https://github.com/AliaJimenez/CoreCalc
   ```
2. **Abre el proyecto en NetBeans u otro IDE compatible con Apache Ant utilizando el archivo build.xml**.

3. **Ejecuta la clase controladora principal PruebaCalculadora.java para ver el set de validaciones aritméticas en acción**.
