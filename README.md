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



#### 5.5.4. Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.

#### calculo de valores:
- procedemos a reeemplazar las fuentes de voltaje existentes en el circuito por sus resistencias internas las cuales son iguales a cero, lo cual es equivalente a poner un cable y al mismo tiempo retiramos el resistor R5, de esta manera optenemos lo siguiente:  
![image](https://user-images.githubusercontent.com/93398718/148318153-8b1784d3-d37b-4699-87b8-5d95f872b2ad.png)  
- procedemos a realizar el respectivo analisis para determinar el valor de RTH:  
![image](https://user-images.githubusercontent.com/93398718/148319636-e5154ffa-ea88-41a9-bce6-ce3b05781fe4.png)  
- obtuvimos como resultado que el valor de RTH es 298.85 Ohmnios.  
#### medicion de valores:
- para comprobar que obtubimos el resultado correcto realizaremos el mismo procedimento en un simulador de la siguiente manera:
![image](https://user-images.githubusercontent.com/93398718/148320367-c37c0c16-e4cd-44af-a3ae-90ae73950761.png)  

- podemos apreciar que el resultado calculado es casi igual al medido, de esta manera se puede afirmar que la resistencia equivalente de thevenin para este circuito tiene un valor de 298.85 Ohmnios. 
  

 
 


# RESPUESTA DE INTERROGANTES 

**5.5.2. Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.**

Armamos el circuito y con los multimetros medimos corriente y voltaje en R5: 

![image](https://user-images.githubusercontent.com/93361435/148446297-41ac113a-79df-413f-bd3e-4932ccc5b91b.png)


| CORRIENTE CALCULADO | VOLTAJE CALCULADO | CORRIENTE MEDIDA | VOLTAJE MEDIDO |
|--------|------------|--------|------------|
| 3.892 mA| 3.892 V | 3.89 mA| 3.89 V|


**5.5.3. Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla 5.1.**

**Calculo de valores:**


**Medición de valores:**




**5.5.5. Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.**

Realizamos el armado del circuito con el uso de un potenciometro, ya que el valor de la resistencia no es fijo en si, ajustamos el potenciometro hasta la resistencia requerida y observamos las mediciones de corriente y voltaje en R5: 

 ![image](https://user-images.githubusercontent.com/93361435/148441801-ef223e77-22d8-4272-ad69-df1357e68cf4.png)

| CORRIENTE CALCULADA THEVENIN | VOLTAJE CALCULADO THEVENIN | CORRIENTE MEDIDA THEVENIN | VOLTAJE MEDIDO THEVENIN |
|--------|------------|--------|------------|
| 3.893 mA | 3.892 V | 3.89 mA | 3.89 V |

## CALCULO DEL ERROR 

#### calculo de error para RTH:
![image](https://user-images.githubusercontent.com/93398718/148321321-cf661522-f9fc-4ce1-a6fb-11eca1dac6f8.png)  



# VIDEO


# CONCLUSIONES


# BIBLIOGRAFIA

- Floyd, T. (2007). *Principios de circuitos eléctricos*. Octava edición. Mexico. Editorial Pearson.
- Robbins, A., Miller, W. (2008) *Analisis de circuitos Teoria y Practica*. Cuarta Edicion. Mexico. Editorial CENGAGE Learning.
