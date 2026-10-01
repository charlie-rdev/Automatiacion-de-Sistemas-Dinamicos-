# Control de sistemas dinámicos: guía de estudio para el examen de medio curso



## Fórmulas clave

| Tema | Expresión |
|---|---|
| Función de transferencia | `G(s) = Y(s) / U(s), condiciones iniciales cero` |
| Variable de desviación | `x'(t) = x(t) - x_s   (x_s = valor en el punto de operación)` |
| Lazo cerrado | `G_lc(s) = G(s) / (1 + G(s)H(s))` |
| Controlador P | `u(t) = Kp e(t)` |
| Controlador PI | `u(t) = Kp e(t) + Ki (integral de e(t) dt)` |
| Controlador PD | `u(t) = Kp e(t) + Kd de(t)/dt` |
| Controlador PID | `u(t) = Kp e(t) + Ki (integral de e(t) dt) + Kd de(t)/dt` |

## Respuestas

### 1. ¿Qué son los sistemas dinámicos?

**Respuesta:** Sistemas cuya salida cambia con el tiempo y que se describen con ecuaciones diferenciales.

- **Concepto:** Sistema dinámico / modelo
- **Relación con las definiciones:** Puntos 10 y 11: las ecuaciones que representan un proceso se linealizan para analizarlas con Laplace. Punto 9: ejemplo clásico, la máquina de vapor con carga variable. La guía no da la definición literal; esta es la definición estándar.
- **Base:** Estándar

### 2. ¿Qué tipo de comportamiento tiene un sistema inestable?

**Respuesta:** Su salida crece sin límite (o oscila con amplitud creciente) y no regresa al equilibrio tras una perturbación.

- **Concepto:** Estabilidad / perturbación
- **Relación con las definiciones:** Punto 1 (perturbación) y puntos 12 y 17 (punto de operación): un sistema estable regresa al punto de operación después de la perturbación, el inestable no. La guía no lo define de forma directa.
- **Base:** Estándar

### 3. ¿Cuál de las siguientes es la función de transferencia de un sistema dinámico?

**Respuesta:** G(s) = Y(s) / U(s): salida entre entrada en el dominio de Laplace, con condiciones iniciales cero. El PDF no trae las opciones; elige la que tenga esta forma.

- **Concepto:** Función de transferencia
- **Relación con las definiciones:** Puntos 19 y 20: la función de transferencia define completamente las características de estado estacionario y dinámico. Punto 22: caso de circuito cerrado.
- **Base:** Guía

### 4. ¿Qué muestra un diagrama de bloques en el análisis de sistemas dinámicos?

**Respuesta:** La interconexión de los componentes del sistema: cada bloque es una función de transferencia y las flechas son el flujo de señales (incluida la retroalimentación).

- **Concepto:** Diagrama de bloques
- **Relación con las definiciones:** Punto 21 (diagramas de bloques y control por retroalimentación) y punto 22 (funciones de transferencia de circuito cerrado). Punto 3: el sistema de control es la combinación de componentes.
- **Base:** Guía

### 5. ¿Para qué se usa la transformación de Laplace de una función f(t)?

**Respuesta:** Para convertir ecuaciones diferenciales en ecuaciones algebraicas en s, y así analizar y diseñar el sistema de control.

- **Concepto:** Transformada de Laplace
- **Relación con las definiciones:** Punto 14: se aplica a variables y señales, no a procesos o instrumentos. Punto 10: las ecuaciones lineales se pueden tratar con Laplace. Puntos 15 y 16: linealidad y diferenciación real.
- **Base:** Guía

### 6. ¿Qué tipo de sistemas describen las funciones de transferencia?

**Respuesta:** Sistemas lineales e invariantes en el tiempo.

- **Concepto:** Linealidad
- **Relación con las definiciones:** Punto 10: las ecuaciones lineales son las que se pueden usar con transformadas de Laplace. Punto 11: la linealización aproxima un sistema no lineal a uno lineal.
- **Base:** Guía

### 7. ¿Cuál de los siguientes componentes NO es parte de un sistema de control?

**Respuesta:** Sin las opciones no se puede marcar. Sí son parte: variable controlada, variable manipulada, perturbaciones, elemento de medición, controlador y elemento final de control. Marca la opción ajena a esa lista.

- **Concepto:** Componentes del sistema de control
- **Relación con las definiciones:** Puntos 1 a 5: perturbación, variable manipulada, sistema de control y variable controlada.
- **Base:** Guía

### 8. ¿Qué significa "sistema de control"?

**Respuesta:** La combinación de componentes que actúan conjuntamente para cumplir un determinado objetivo.

- **Concepto:** Sistema de control
- **Relación con las definiciones:** Punto 3, casi literal.
- **Base:** Guía

### 9. ¿Cómo se describe un sistema dinámico?

**Respuesta:** Con un modelo matemático: ecuaciones diferenciales, o su función de transferencia tras aplicar Laplace.

- **Concepto:** Modelo matemático
- **Relación con las definiciones:** Puntos 10, 11 y 14: ecuaciones del proceso, linealización y Laplace.
- **Base:** Guía

### 10. ¿Qué describe la función de transferencia de un sistema en el dominio de Laplace?

**Respuesta:** La relación entre la salida y la entrada, es decir, el comportamiento de estado estacionario y dinámico del sistema.

- **Concepto:** Función de transferencia
- **Relación con las definiciones:** Punto 20, casi literal.
- **Base:** Guía

### 11. ¿La transformada de Laplace de una ecuación diferencial permite convertirla al dominio del tiempo?

**Respuesta:** FALSO. Laplace pasa del tiempo al dominio s; para volver al tiempo se usa la transformada inversa.

- **Concepto:** Transformada de Laplace
- **Relación con las definiciones:** Punto 14: las funciones del tiempo se transforman a variables en s para el diseño del sistema de control.
- **Base:** Guía

### 12. ¿La linealización transforma un sistema no lineal en uno lineal cerca del punto de equilibrio?

**Respuesta:** VERDADERO.

- **Concepto:** Linealización
- **Relación con las definiciones:** Punto 11: la linealización aproxima ecuaciones no lineales a lineales. Puntos 12 y 17: se trabaja con variables de desviación respecto al punto de operación.
- **Base:** Guía

### 13. ¿Los diagramas de bloques permiten analizar sistemas complejos mediante la interconexión de funciones de transferencia?

**Respuesta:** VERDADERO.

- **Concepto:** Diagrama de bloques
- **Relación con las definiciones:** Puntos 21 y 22: bloques con funciones de transferencia, incluida la de circuito cerrado.
- **Base:** Guía

### 14. ¿La función de transferencia solo es válida si el sistema es estable?

**Respuesta:** FALSO. Requiere que el sistema sea lineal e invariante en el tiempo, no que sea estable.

- **Concepto:** Función de transferencia
- **Relación con las definiciones:** Punto 10 (linealidad) y punto 20 (la función de transferencia define el comportamiento dinámico, que incluye sistemas que se vuelven inestables).
- **Base:** Guía + lógica

### 15. ¿Los diagramas de bloques ayudan a visualizar cómo responde un sistema ante diferentes tipos de entradas?

**Respuesta:** FALSO (probable). El diagrama muestra la estructura y el flujo de señales; la respuesta ante una entrada se calcula aplicando esa entrada a la función de transferencia.

- **Concepto:** Diagrama de bloques
- **Relación con las definiciones:** Puntos 21 y 22. Pregunta ambigua: si tu profesor lo planteó como verdadero, sigue su versión.
- **Base:** Lógica

### 16. ¿La expresión en variables incrementales solo sirve para pequeñas perturbaciones alrededor del punto de equilibrio?

**Respuesta:** VERDADERO.

- **Concepto:** Variables de desviación
- **Relación con las definiciones:** Puntos 11, 12 y 17: la linealización y las variables de desviación son válidas cerca del punto de operación.
- **Base:** Guía

### 17. ¿El punto de equilibrio se obtiene cuando las entradas y salidas no cambian con el tiempo?

**Respuesta:** VERDADERO.

- **Concepto:** Punto de equilibrio
- **Relación con las definiciones:** Puntos 12 y 17: la variable de desviación se mide respecto al valor en el punto de operación.
- **Base:** Guía

### 18. ¿La función de transferencia es útil únicamente para sistemas no lineales?

**Respuesta:** FALSO. Es útil para sistemas lineales.

- **Concepto:** Linealidad
- **Relación con las definiciones:** Puntos 10 y 11: Laplace y la función de transferencia requieren ecuaciones lineales; por eso se linealiza.
- **Base:** Guía

### 19. ¿Los diagramas de bloques no pueden representar sistemas con retroalimentación?

**Respuesta:** FALSO. Sí los representan; de hecho son la forma estándar de dibujar un lazo cerrado.

- **Concepto:** Retroalimentación
- **Relación con las definiciones:** Puntos 6, 8, 21 y 22: control por retroalimentación y funciones de transferencia de circuito cerrado.
- **Base:** Guía

### 20. ¿Qué tipo de controlador elimina el error en estado estacionario?

**Respuesta:** Integral (I). Acumula el error pasado hasta llevarlo a cero.

- **Concepto:** Controladores
- **Relación con las definiciones:** La guía de definiciones no trae controladores. Se relaciona con el punto 9 (control regulador: mantener constante la velocidad con carga variable) y el punto 6.
- **Base:** Estándar

### 21. ¿Qué controlador cambia entre dos estados (encendido y apagado)?

**Respuesta:** On-Off (todo o nada).

- **Concepto:** Controladores
- **Relación con las definiciones:** Mismo caso: no viene en la guía de definiciones.
- **Base:** Estándar

### 22. ¿Qué controlador ofrece la acción más precisa combinando tres tipos de correcciones?

**Respuesta:** PID (proporcional + integral + derivativo).

- **Concepto:** Controladores
- **Relación con las definiciones:** Mismo caso: no viene en la guía de definiciones.
- **Base:** Estándar

### 23. ¿Cuál es el controlador que actúa solo según el error presente?

**Respuesta:** Proporcional (P).

- **Concepto:** Controladores
- **Relación con las definiciones:** Mismo caso: no viene en la guía de definiciones.
- **Base:** Estándar

### 24. ¿Qué controlador combina correcciones proporcionales e integrales?

**Respuesta:** PI.

- **Concepto:** Controladores
- **Relación con las definiciones:** Mismo caso: no viene en la guía de definiciones.
- **Base:** Estándar

### 25. ¿Qué controlador integra acciones proporcionales y derivativas?

**Respuesta:** PD.

- **Concepto:** Controladores
- **Relación con las definiciones:** Mismo caso: no viene en la guía de definiciones.
- **Base:** Estándar
