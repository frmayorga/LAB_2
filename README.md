# LAB_2 ANALISIS DE MALLAS

# INTEGRANTES

Fernanda Mayorga, Stalyn Castellanos, Nicolás Reyes

# OBJETIVOS

## OBJETIVO GENERAL 

Realizar la aplicación del análisis de mallas en circuitos eléctricos además demostrar el análisis de mallas experimentalmente con la ayuda de simuladores virtuales y con el respectivo sustento teórico de tema

## OBJETIVOS ESPECIFICOS

- comparar los resultados obtenidos en la corriente existenete en cada malla de manera experimental, analitica y simulada.
- aplicar el metodo de analisis de mallas para encontrar valores de corriente en un circuito, mediante la cual podamos conocer mas caracteristicas de los componentes del circuito como lo son el voltaje o la resistencia.

# MARCO TEORICO

![Marco teorico](https://user-images.githubusercontent.com/93361435/142778540-6e5adb05-28c8-42a5-b124-837869409550.jpg)

**CODIGO DE COLORES PARA RESISTORES DE 4 BANDAS** 

| DIGITO | COLOR |
|--------|------------|
| 0 | Negro |
| 1 | Café |
| 2 | Rojo |
| 3 | Naranja |
| 4 | Amarillo |
| 5 | Verde |
| 6 | Azul |
| 7 | Violeta |
| 8 | Gris |
| 9 | Blanco |

TOLERANCIA : Oro +- 5%; Plata +- 10%.

# EXPLICACION DEL PROCEDIMIENTO

**Se utilizo los siguientes materiales:** 

| CANTIDAD | MATERIAL |
|--------|------------|
| 1 | Fuente de voltaje en C.D. |
| 1 | Multimetro Digital |
| 1 | Resistor de 820 Ohmios |
| 1 | Resistor de 390 Ohmios |
| 1 | Resistor de 1 kilo-ohmio |
| 1 | Resistor de 1.2 kilo-ohmios |
| 1 | Resistor de 2.2 Kilo-ohmios |
| 1 | Protoboard |

Con los materiales disponibles se procedio a armar el circuito en tinkercad y multisim, para el posterior análisis con uso de tablas. 

![image](https://user-images.githubusercontent.com/93361435/142775359-fdbaade0-d7a4-4656-a6a1-796989cb7e4d.png)

Para los resultados analitos se realizo el siguiente calculo usando el analisis de mallas.

![Pizarra](https://user-images.githubusercontent.com/93361435/142781707-601d0ea4-1f63-4cfa-92e3-ad3a9bc55ea2.png)

Obteniendo los siguientes resultados (con la ayuda de una calculadora online) 

![image](https://user-images.githubusercontent.com/93361435/142781950-ba984bfc-9585-4a99-99d3-77b3884a3083.png)

### resultados experimentales:

- en primer lugar y con la ayuda de un simulador de circuitos esquematicos, procedemos a graficar nuestro ejercicio:  
![image](https://user-images.githubusercontent.com/93398718/142787267-7eba2f72-c83e-4779-ad9e-de7defffad34.png)
- ahora procedemos a medir la corriente existente en cada una de las mallas de modo que podamos comparar los resultados obtenidos experimentalmente:  
![image](https://user-images.githubusercontent.com/93398718/142787496-b4ef7403-9452-4c98-a34e-52a1acde8799.png)
- la razon por la cual medimos la corriente de las mallas en las resistencias R1, R2 y R3 es por que atravez de ellas podemos obtener una corriente que no se ve afectada por las demas corrientes de las otras mallas y esta corriente es la de su mmalla correpondiente.

- ahora que tenemos los datos procedemos a realizar su analisis:  

| MALLA | R. ANALITICO | R. EXPERIMENTAL | R. SIMULADO |
|--------|------------|-------------------|-------------|
| MALLA 1 | 11.45 mA | 11.455 mA  | 11.5 mA  |
| MALLA 2 | 2.847 mA | 2.8474 mA  | 2.85 mA |
| MALLA 3 | 488.12 uA | 488.12 uA  | 488 uA |

- como podemos apreciar los resultados son muy similares, asi que podemos asegurar que existe un alto grado de exaxtitud en los calculos.


# RESPUESTA A INTERROGANTES Y CALCULO DE ERROR 

TABLA: 

| MALLA | R. ANALITICO | R. EXPERIMENTAL | R. SIMULADO |
|--------|------------|-------------------|-------------|
| MALLA 1 | 11.45 mA | 11.455 mA  |  |
| MALLA 2 | 2.847 mA | 2.8474 mA  |  |
| MALLA 3 | 488.12 uA | 488.12 uA  |  |


# VIDEO



# CONCLUSIONES

- el analis de mallas es sumanente importante pues no ayuda a determinar las corrientes que circulan por una malla, la cual no es mas que un caso particular de trayectorias, es decir, una zona en la que la corriente circula sin interrupciones.una vez que obtenemos esta corriente podemos obtener otros datos que tambien son necesarios como por ejemplo el voltaje en cada componente.
- tras analizar los resultados obtenidos pudimos apreciar que existia una gran precision, por este motivo se podria decir que el analisis de mallas es un metodo sumamente exacto. de esta manera podemos confiar en que los resultados obtenido con este metodo son muy cercanos a los reales.


# BIBLIOGRAFIA

- Floyd, T. (2007). Principios de circuitos eléctricos. Octava edición. Mexico. Editorial Pearson.
- Robbins, A., Miller, W. (2008) Analisis de circuitos Teoria y Practica. Cuarta Edicion. Mexico. Editorial CENGAGE Learning.
- McAllister, W. (s.f) El método de la corriente de malla. Khan Academy. Recuperado el 21 de noviembre del 2021 de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-mesh-current-method
- McAllister, W. (s.f) Las Leyes de Kirchoff. Khan Academy. Recuperado el 21 de noviembre del 2021 de https://es.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/ee-kirchhoffs-laws
- CALCULADORA ONLINE: http://es.onlinemschool.com/math/assistance/equation/combined_equations/
