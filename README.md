Analizador Léxico y Sintáctico — Expresiones Algebraicas

Universidad Mariano Gálvez de Guatemala
Curso: Autómatas y Lenguajes Formales
Fase II — Proyecto de Analizador Léxico y Sintáctico
Autor: Dulce Claudia Michelle Ramirez Rac
Carné: 9989-23-15707
Sección: “A” — Ingeniería en Sistemas

Descripción del Proyecto

Este proyecto implementa un analizador léxico y sintáctico en Java, capaz de reconocer y validar expresiones algebraicas como:

3a + (b^2) - 10
x * -2a
(a + b) * c^3


El analizador:

Identifica los tokens léxicos (COEFICIENTE, VARIABLE, OPERADOR, EXPONENTE, LPAREN, RPAREN, etc.).

Detecta errores léxicos (símbolos inválidos).

Verifica errores sintácticos (paréntesis sin cerrar, operadores al final, expresiones incompletas).

Genera los diagramas AFN y AFD en formato .dot y .png.

Requisitos Previos
Opción 1: Ejecutar en NetBeans
- Java JDK 8 o superior
- NetBeans IDE 12+
  
