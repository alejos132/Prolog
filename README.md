# Sistema de Gestión de Ventas de Vehículos - Prolog

## Descripción
Proyecto de la asignatura Lenguajes de Programación (EAFIT).  
Consiste en un sistema en **Prolog** para administrar y consultar un inventario de vehículos, aplicando filtros y generando reportes.

## Objetivos
- Definir un catálogo de vehículos con atributos: marca, referencia, tipo, precio y año.  
- Implementar consultas con findall/3 y bagof/3.  
- Restringir resultados según un presupuesto máximo.

## Funcionalidades
- Filtrar vehículos por tipo y presupuesto.  
- Listar vehículos por marca.  
- Generar reportes que incluyan lista filtrada y valor total del inventario.  

## Casos de Prueba
1. SUVs Toyota por debajo de $30,000.  
2. Vehículos Ford agrupados por tipo y año.  
3. Valor total de sedanes sin superar $500,000.

## Ejemplos de ejecución del código

En (1), se prueba el predicado meet_budget -> Devuelve falso cuando el presupuesto es insuficiente, pero devuelve verdadero cuando el presupuesto es mayor o igual que el precio.
En (2) se usa bagof para listar vehículos de una marca. También probamos el predicado generate_report que retorna una lista con vehículos de una marca y tipo según el presupuesto.
En (3) se inicializa cada caso de prueba y se retornan los vehículos que cumplen con las condiciones establecidas.

## Referencias

- Bratko, I. (2011). *Prolog Programming for Artificial Intelligence* (4th ed.). Addison-Wesley.  
- Sterling, L., & Shapiro, E. (1994). *The Art of Prolog: Advanced Programming Techniques* (2nd ed.). MIT Press.  
- Clocksin, W. F., & Mellish, C. S. (2003). *Programming in Prolog* (5th ed.). Springer.  
- OpenAI. (2025). *ChatGPT (GPT-5)*. Disponible en: [https://chat.openai.com/](https://chat.openai.com/)  





