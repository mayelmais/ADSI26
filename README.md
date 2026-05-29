# Proyecto Final: App de Cafetería Estudiantil

**Materia:** Análisis y Diseño de Sistemas de Información (COM-12102-001)

**Equipo PAID**

**Integrantes:**
* Pablo Ernesto Gómez Ignorosa (211643)
* Ana Sofía Ceballos Martínez (212560)
* Ismael Cabrera Arroyo (217632)
* Dulce

---

## Contexto del Proyecto
Construcción de una aplicación móvil en donde los estudiantes puedan programar pedidos de café antes de entrar a clase para optimizar su tiempo. La aplicación incluye:
* Manera intuitiva de seleccionar el menú.
* Sistema para elegir y personalizar un pedido.
* Múltiples opciones de pago integradas (Tarjeta Bancaria (Debito o Credito), Apple Pay, Efectivo).
* Proceso claro para confirmar la hora exacta de entrega.

---

## Entregables

### 1. 3 Personas

Para entender las necesidades y motivaciones de nuestros usuarios, desarrollamos 3 perfiles principales.

### Persona 1: El estudiante acelerado
Representa a nuestro usuario principal, enfocado en la velocidad y la eficiencia.
![Persona 1 - Mateo](./Assets/persona_1.png)

### Persona 2: La profesora con agenda llena
Representa al personal académico que valora la previsibilidad y la puntualidad extrema.
![Persona 2 - Elena](./Assets/persona_2.png)

### Persona 3: La estudiante organizadora
Representa al usuario que realiza pedidos múltiples o altamente personalizados para equipos de trabajo.
![Persona 3 - Valeria](./Assets/persona_3.png)

---

### 2. 1 Customer Journey

Trazamos el recorrido de nuestro usuario para identificar los *touchpoints*, sus emociones durante el proceso y las oportunidades de mejora en cada fase.

![Customer Journey Map](./Assets/customer_journey.png)

---

### 3. 1 Prototipo a Papel
*(Prototipo a papel)*

---

### 4. 3 Pruebas del Prototipo a Papel
*(3 pruebas iniciales)*

---

### 5. 1 Reflexión sobre los Hallazgos y Cambios a Realizar (De Papel a Medio Nivel)
*(Reflexión)*

---

### 6. 1 Prototipo a Medio Nivel
En esta etapa construimos un *wireframe* interactivo en escala de grises para validar la arquitectura de la información, el flujo de navegación y la usabilidad estructural antes de invertir tiempo en el diseño visual.

(Preferible en telefono)
* **Prototipo (Diseño en Figma):** [Ver archivo de Figma](https://www.figma.com/design/s6R7mhIO14TVrg9y1aNgOc/Cafeteria-Medio-Nivel?node-id=0-1&t=NneSjFBnyN4NlNiw-1)
* **Prueba Digital (Prototipo Interactivo):** [Probar prototipo de medio nivel](https://www.figma.com/proto/s6R7mhIO14TVrg9y1aNgOc/Cafeteria-Medio-Nivel?node-id=0-1&t=NneSjFBnyN4NlNiw-1)

---

### 7. Pruebas de usuario en Lyssna

Para validar la intuición de la navegación realizamos un *Navigation Test* interactivo utilizando **Lyssna**. 

A los usuarios se les asignó la tarea de: Iniciar sesión, personalizar un Capuchino, revisar el carrito, pagar con Apple Pay y programar su horario de recolección.

**[Enlace a la prueba interactiva en Lyssna](https://app.lyssna.com/do/ztfe4nkszj1y/z6za6z)**

### Resultados de la Prueba

A continuación se presentan las métricas obtenidas de las interacciones de los usuarios durante la prueba:

![Resultados Lyssna 1](./Assets/resultado_lyssna_1.png)

![Resultados Lyssna 2](./Assets/resultado_lyssna_2.png)

![Resultados Lyssna 3](./Assets/resultado_lyssna_3.png)

![Resultados Lyssna 4](./Assets/resultado_lyssna_4.png)

---

### 8. 1 Reflexión sobre los Hallazgos y Cambios a Realizar (De Medio a Alto Nivel)
**Objetivo de la prueba:** Validar la fluidez del flujo de pedido (seleccionar un café, personalizarlo y pagarlo) garantizando que el proceso completo se sienta ágil para cumplir con la promesa de valor de la app.

**Hallazgos Principales (Prueba Digital de Medio Nivel):**
Al probar el prototipo interactivo en escala de grises con usuarios representativos, identificamos tres áreas de oportunidad clave:
1. **Fricción cognitiva en el menú:** Al tener los cafés representados con cuadros grises genéricos, los usuarios tardaban en leer los textos para encontrar su bebida. En un escenario de prisa, la lectura detiene el flujo.
2. **Identificación en el Checkout:** En la pantalla de métodos de pago, el formato de solo texto obligaba al usuario a buscar meticulosamente la opción deseada, generando un retraso en el paso más crítico.
3. **Incertidumbre post-compra:** Tras confirmar el pago, la pantalla de éxito resultaba muy estática. Los usuarios mencionaron sentir ansiedad al no saber el estado real de su café.

**Cambios Implementados (Prototipo de Alto Nivel):**
Con base en estos hallazgos, el diseño evolucionó enfocándose en la respuesta visual y la velocidad:
* **Inclusión de ilustraciones a color:** Se sustituyeron los cuadros grises por ilustraciones claras de cada bebida (Capuchino, Matcha, etc.). Esto permite al estudiante escanear el menú visualmente en una fracción de segundo.
* **Reconocimiento de marca en pagos:** En la pantalla "Total a pagar", se incorporaron los logotipos oficiales de los métodos de pago (Visa, Mastercard, Apple Pay) junto al texto. Esto facilita el reconocimiento inmediato.
* **Barra de progreso en tiempo real (Live Tracker):** Para eliminar la incertidumbre, la pantalla de "Tu orden" se rediseñó por completo. Se añadió una línea de tiempo con tres estados visuales (*Recibido*, *Preparando* y *En barra*), complementada con la hora exacta en la que el pedido estará listo.

---

### 9. 1 Prototipo a Alto Nivel
Versión final de la aplicación con diseño visual completo, tipografías, paleta de colores, microinteracciones y los ajustes de usabilidad aplicados tras las pruebas de usuario.

(Preferible en telefono)
* **Prototipo (Diseño en Figma):** [Ver archivo de Figma](https://www.figma.com/design/FpGEyCkSmcWek0Cf3JsSiY/Cafeteria-Alto-Nivel?node-id=0-1&t=U9VXwjtCamA71Exd-1)
* **Prueba Digital (Prototipo Interactivo):** [Probar prototipo final](https://www.figma.com/proto/FpGEyCkSmcWek0Cf3JsSiY/Cafeteria-Alto-Nivel?node-id=0-1&t=U9VXwjtCamA71Exd-1)

---

## Backlog del Proyecto
Backlog de la planeación, asignación de tareas y el progreso general de nuestro equipo durante el desarrollo de la aplicación:

* [Ver Backlog](https://github.com/users/mayelmais/projects/1/views/1)

---

## User Stories


## Criterios de complejidad

* **1:** Cambio mínimo
* **3:** Interfaz/frontend
* **5:** Mostrar datos o cálculo simple
* **7:** Base de datos y lógica básica
* **10:** Funcionalidad completa con formulario
* **15:** Nueva interfaz y base de datos
* **21:** Varias opciones con lógica compleja
* **30:** Integración de APIs externas


| Usuario               | User Story                                                                                                                                            | Complejidad | Prioridad |
| --------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | ----------: | --------- |
| Estudiante: Dulce     | Como estudiante, quiero consultar el menú de bebidas disponibles, para elegir fácilmente qué café pedir antes de entrar a clase.                      |           5 | Alta      |
| Estudiante: Rafael    | Como estudiante, quiero personalizar mi bebida con opciones como tamaño, tipo de leche y azúcar, para pedirla de acuerdo con mis gustos.              |          21 | Alta      |
| Estudiante: Sara      | Como estudiante, quiero elegir la hora exacta de entrega de mi café, para recogerlo antes de entrar a clase.                                          |          10 | Alta      |
| Estudiante: Diego     | Como estudiante, quiero ver el tiempo estimado de preparación, para saber cuándo ir por mi café.                                                      |           5 | Alta      |
| Estudiante: Iñaki     | Como estudiante, quiero pagar con tarjeta de débito, para no tener que usar efectivo.                                                                 |          30 | Alta      |
| Estudiante: Raúl      | Como estudiante, quiero pagar con tarjeta de crédito, para tener otra opción de pago dentro de la aplicación.                                         |          30 | Alta      |
| Estudiante: Alejandro | Como estudiante, quiero seleccionar pago en efectivo, para poder pagar al recoger mi pedido.                                                          |           7 | Media     |
| Estudiante: Mónica    | Como estudiante, quiero crear una cuenta, para identificarme dentro de la aplicación.                                                                 |          10 | Alta      |
| Estudiante: Tomás     | Como estudiante, quiero iniciar sesión, para acceder a mis pedidos y guardar mi información.                                                          |           7 | Alta      |
| Estudiante: Leo       | Como estudiante, quiero guardar mis pedidos favoritos, para repetirlos rápidamente.                                                                   |           7 | Media     |
| Estudiante: Sandra    | Como estudiante, quiero recibir promociones y descuentos, para gastar menos dinero en mis compras.                                                    |           3 | Baja      |
| Estudiante: Nelly     | Como estudiante, quiero ver el estado de mi orden, para saber si mi café fue recibido, está en preparación o ya está listo.                           |          15 | Alta      |
| Estudiante: Fátima    | Como usuario, quiero revisar el resumen de mi pedido antes de confirmar, para verificar la bebida, personalización, hora de entrega y método de pago. |           5 | Alta      |

