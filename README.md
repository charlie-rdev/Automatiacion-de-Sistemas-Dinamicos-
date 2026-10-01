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


### 2. ¿Qué tipo de comportamiento tiene un sistema inestable?

**Respuesta:** Su salida crece sin límite (o oscila con amplitud creciente) y no regresa al equilibrio tras una perturbación.


### 3. ¿Cuál de las siguientes es la función de transferencia de un sistema dinámico?

**Respuesta:** G(s) = Y(s) / U(s): salida entre entrada en el dominio de Laplace, con condiciones iniciales cero. El PDF no trae las opciones; elige la que tenga esta forma.



### 4. ¿Qué muestra un diagrama de bloques en el análisis de sistemas dinámicos?

**Respuesta:** La interconexión de los componentes del sistema: cada bloque es una función de transferencia y las flechas son el flujo de señales (incluida la retroalimentación).



### 5. ¿Para qué se usa la transformación de Laplace de una función f(t)?

**Respuesta:** Para convertir ecuaciones diferenciales en ecuaciones algebraicas en s, y así analizar y diseñar el sistema de control.



### 6. ¿Qué tipo de sistemas describen las funciones de transferencia?

**Respuesta:** Sistemas lineales e invariantes en el tiempo.



### 7. ¿Cuál de los siguientes componentes NO es parte de un sistema de control?

**Respuesta:** Sin las opciones no se puede marcar. Sí son parte: variable controlada, variable manipulada, perturbaciones, elemento de medición, controlador y elemento final de control. Marca la opción ajena a esa lista.



### 8. ¿Qué significa "sistema de control"?

**Respuesta:** La combinación de componentes que actúan conjuntamente para cumplir un determinado objetivo.



### 9. ¿Cómo se describe un sistema dinámico?

**Respuesta:** Con un modelo matemático: ecuaciones diferenciales, o su función de transferencia tras aplicar Laplace.



### 10. ¿Qué describe la función de transferencia de un sistema en el dominio de Laplace?

**Respuesta:** La relación entre la salida y la entrada, es decir, el comportamiento de estado estacionario y dinámico del sistema.


### 11. ¿La transformada de Laplace de una ecuación diferencial permite convertirla al dominio del tiempo?

**Respuesta:** FALSO. Laplace pasa del tiempo al dominio s; para volver al tiempo se usa la transformada inversa.



### 12. ¿La linealización transforma un sistema no lineal en uno lineal cerca del punto de equilibrio?

**Respuesta:** VERDADERO.



### 13. ¿Los diagramas de bloques permiten analizar sistemas complejos mediante la interconexión de funciones de transferencia?

**Respuesta:** VERDADERO.



### 14. ¿La función de transferencia solo es válida si el sistema es estable?

**Respuesta:** FALSO. Requiere que el sistema sea lineal e invariante en el tiempo, no que sea estable.



### 15. ¿Los diagramas de bloques ayudan a visualizar cómo responde un sistema ante diferentes tipos de entradas?

**Respuesta:** FALSO (probable). El diagrama muestra la estructura y el flujo de señales; la respuesta ante una entrada se calcula aplicando esa entrada a la función de transferencia.


### 16. ¿La expresión en variables incrementales solo sirve para pequeñas perturbaciones alrededor del punto de equilibrio?

**Respuesta:** VERDADERO.



### 17. ¿El punto de equilibrio se obtiene cuando las entradas y salidas no cambian con el tiempo?

**Respuesta:** VERDADERO.



### 18. ¿La función de transferencia es útil únicamente para sistemas no lineales?

**Respuesta:** FALSO. Es útil para sistemas lineales.



### 19. ¿Los diagramas de bloques no pueden representar sistemas con retroalimentación?

**Respuesta:** FALSO. Sí los representan; de hecho son la forma estándar de dibujar un lazo cerrado.



### 20. ¿Qué tipo de controlador elimina el error en estado estacionario?

**Respuesta:** Integral (I). Acumula el error pasado hasta llevarlo a cero.



### 21. ¿Qué controlador cambia entre dos estados (encendido y apagado)?

**Respuesta:** On-Off (todo o nada).


### 22. ¿Qué controlador ofrece la acción más precisa combinando tres tipos de correcciones?

**Respuesta:** PID (proporcional + integral + derivativo).



### 23. ¿Cuál es el controlador que actúa solo según el error presente?

**Respuesta:** Proporcional (P).



### 24. ¿Qué controlador combina correcciones proporcionales e integrales?

**Respuesta:** PI.



### 25. ¿Qué controlador integra acciones proporcionales y derivativas?

**Respuesta:** PD.


