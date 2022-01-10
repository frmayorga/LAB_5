# LAB_5

# OBJETIVOS

## OBJETIVO GENERAL 
- Haciendo uso del circuito proporcionado en la actividad y los conocimientos impartidos en clase demostrar que todo circuito resistivo puede ser llevado a la forma de un circuito equivalente de thevenin que consta de una fuente de voltaje y un resistor equivalente, donde ambos componentes se encuentran en serie con cualquier carga que se les conecte.

## OBJETIVO ESPECIFICO
- definir un circuito equivalente de thevenin con el ejercicio proporcionado.
- demostrar que todo circuito resistivo puede ser thevenizado.

# MARCO TEORICO

![Teorema de Thevenin](https://user-images.githubusercontent.com/93361435/147798351-741194ce-f083-4f11-aa0f-d91f0a9dca22.jpg)


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


# PROCEDIMIENTO

Se utilizaron los siguientes materiales: 

| CANTIDAD | MATERIAL |
|--------|------------|
| 2 | Fuente de voltaje en C.D. |
| 2 | Multimetro Digital |
| 1 | Resistor de 4.7 Kilo-Ohmios |
| 1 | Resistor de 330 Ohmios |
| 1 | Resistor de 100 Ohmios |
| 1 | Resistor de 1 kilo-ohmio |
| 1 | Potenciómetro de precisión de 1 kilo-ohmio |
| 1 | Protoboard |

Se procedio a armar el circuito de la figura en el simulador tinkercad, ademas se realizaron los calculos respectivos del voltaje de thevenin y resistencia de thevenin para finalmente armar el circuito de thevenin y tambien medir sus valores con el fin de demostrar el teorema propuesto. 

![image](https://user-images.githubusercontent.com/93361435/147798424-3b15c131-5b2b-418c-a979-e3f5db79d543.png)





# RESPUESTA DE INTERROGANTES 

**5.5.2. Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.**

**Calculo de valores:**

Se utilizo el metodo de superposicion y se obtuvo los siguientes resultados: 

![superposicion-thevenin](https://user-images.githubusercontent.com/93361435/148452795-f50be373-3bff-4c3c-8745-61d963037923.png)

**Medición de valores:**

Armamos el circuito y con los multimetros medimos corriente y voltaje en R5: 

![image](https://user-images.githubusercontent.com/93361435/148446297-41ac113a-79df-413f-bd3e-4932ccc5b91b.png)


| CORRIENTE CALCULADO | VOLTAJE CALCULADO | CORRIENTE MEDIDA | VOLTAJE MEDIDO |
|--------|------------|--------|------------|
| 3.896 mA| 3.896 V | 3.89 mA| 3.89 V|


**5.5.3. Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla 5.1.**

**Calculo de valores:**

Se utiliza el metodo de calculo de corrientes de mallas para encontrar el voltaje de Thevenin(VTH):

Circuito original:

![image](https://user-images.githubusercontent.com/93561706/148723289-9e209013-5727-4159-8f58-32f382bbe548.png)

Circuito sin R5 para calcular el voltaje de thevenin:
![image](https://user-images.githubusercontent.com/93561706/148723346-45f71ce6-cdb8-406a-ae93-6cc4625a7e43.png)

![image](https://user-images.githubusercontent.com/93561706/148723368-c0ef924f-71dc-4c39-9f31-66e8dd718c75.png)

![image](https://user-images.githubusercontent.com/93561706/148722546-36d10493-536e-4ae8-9952-bb075e58b825.png) 
![image](https://user-images.githubusercontent.com/93561706/148722600-a4834929-196b-49f1-bafd-07862af939be.png)

![image](https://user-images.githubusercontent.com/93561706/148722605-f3c0b406-f7e5-4eb5-9ea9-7a4a4b216390.png)

![image](https://user-images.githubusercontent.com/93561706/148722638-89d131e5-7eea-4ab0-b033-a08d26b661de.png)

**Medición de valores:**

Armamos el circuito y con los multimetros medimos corriente y voltaje: 

![image](https://user-images.githubusercontent.com/93561706/148724369-2ddff113-8f07-4930-93ef-0b497db74dcd.png)


| VOLTAJE CALCULADA THEVENIN | VOLTAJE MEDIDA THEVENIN |
|--------|------------|
| 5.06 V | 5.06 V |

**5.5.4. Desconecte la resistencia R5 y mida la resistencia en el circuito abierto. Anote el valor medido en la tabla 5.1.**

**Calculo de valores:**
- procedemos a reeemplazar las fuentes de voltaje existentes en el circuito por sus resistencias internas las cuales son iguales a cero, lo cual es equivalente a poner un cable y al mismo tiempo retiramos el resistor R5, de esta manera optenemos lo siguiente:  
![image](https://user-images.githubusercontent.com/93398718/148318153-8b1784d3-d37b-4699-87b8-5d95f872b2ad.png)  
- procedemos a realizar el respectivo analisis para determinar el valor de RTH:  
![image](https://user-images.githubusercontent.com/93398718/148319636-e5154ffa-ea88-41a9-bce6-ce3b05781fe4.png)  
- obtuvimos como resultado que el valor de RTH es 298.85 Ohmnios.

**Medición de valores:**
- para comprobar que obtubimos el resultado correcto realizaremos el mismo procedimento en un simulador de la siguiente manera:
![image](https://user-images.githubusercontent.com/93398718/148320367-c37c0c16-e4cd-44af-a3ae-90ae73950761.png)  

- podemos apreciar que el resultado calculado es casi igual al medido, de esta manera se puede afirmar que la resistencia equivalente de thevenin para este circuito tiene un valor de 298.85 Ohmnios. 

| RESISTENCIA CALCULADA THEVENIN | RESISTENCIA MEDIDA THEVENIN |
|--------|------------|
| 298.85 Ohmios | 299 Ohmios |

**5.5.5. Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.**

**Calculo de valores** 

Se realizo el calculo de la corriente y voltaje como un circuito serie: 

![thevenin](https://user-images.githubusercontent.com/93361435/148661712-79826f25-15ed-408e-bf36-85e9ee2c6773.png)

**Medicion de valores**

Realizamos el armado del circuito con el uso de un potenciometro, ya que el valor de la resistencia no es fijo en si, ajustamos el potenciometro hasta la resistencia requerida y observamos las mediciones de corriente y voltaje en R5: 

 ![image](https://user-images.githubusercontent.com/93361435/148441801-ef223e77-22d8-4272-ad69-df1357e68cf4.png)

| CORRIENTE CALCULADA THEVENIN | VOLTAJE CALCULADO THEVENIN | CORRIENTE MEDIDA THEVENIN | VOLTAJE MEDIDO THEVENIN |
|--------|------------|--------|------------|
| 3.893 mA | 3.892 V | 3.89 mA | 3.89 V |

## CALCULO DEL ERROR 

#### calculo de error para RTH:
![image](https://user-images.githubusercontent.com/93398718/148321321-cf661522-f9fc-4ce1-a6fb-11eca1dac6f8.png)  

**Calculo de error para la corriente:**

![image](https://user-images.githubusercontent.com/93361435/148453196-baf6b460-d1eb-41fb-84a0-0827e9c72fc8.png)

**Calculo de error para el voltaje:**

![image](https://user-images.githubusercontent.com/93361435/148453291-8dfaf683-a6a9-41b6-ad7c-92ae26630b86.png)

# VIDEO

https://youtu.be/5OIQSAfOu5g

# CONCLUSIONES

- Como se pudo observa en todo el laboratorio se logra hallar un circuito equivalente al originar que comple con las mismas condiciones, en conclusion el metodo de thevenin es una herramienta muy util el cual nos ayudo a resolver este ejercicio.
- Se observo y determino que si se puede llegar a que todo circuito complejo este de la forma de thevenin y cumplas las mismas condiciones.
# BIBLIOGRAFIA

- Floyd, T. (2007). *Principios de circuitos eléctricos*. Octava edición. Mexico. Editorial Pearson.
- Robbins, A., Miller, W. (2008) *Analisis de circuitos Teoria y Practica*. Cuarta Edicion. Mexico. Editorial CENGAGE Learning.
