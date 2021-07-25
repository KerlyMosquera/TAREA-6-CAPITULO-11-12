# TAREA-6-CAPITULO-11-12
## 1. OBJETIVOS
## 1.1  CARGA, DESCARGA DEL CAPACITOR Y CIRCUITOS FORMADORES DE ONDA SIMPLES 
-  Explicar por qué los transitorios ocurren en circuitos RC
-  Explicar por qué un capacitor descargado parece como un cortocircuito cuando se energiza por primera vez.
-  Describir por qué un capacitor parece un circuito abierto en estado estable de cd.
-  Describir la carga y descarga de circuitos RC simples con excitación de cd.
-  Determinar los voltajes y corrientes en circuitos RC simples durante la carga y descarga.
-  Graficar el voltaje y transitorios de corriente.
-  Entender el papel que desempeñan las constantes de tiempo en determinar la duración de los transitorios.
-  Calcular constantes de tiempo.
-  Describir el uso de las formas de onda de carga y descarga en aplicaciones simples de temporización.
-  Resolver problemas simples de transitorios rc con pspice y
Multisim.
## 1.2  MAGNETISMO Y CIRCUITOS MAGNÉTICOS 
- Representar los campos magnéticos usando el concepto de flujo de Faraday.
- Describir los campos magnéticos en forma cuantitativa en términos del flujo y la densidad de flujo.
- Explicar qué son los circuitos magnéticos y por qué se usan.
- Determinar la intensidad de campo magnético o la densidad de flujo magnético de una curva B-H
- Resolver circuitos magnéticos en serie.
- Resolver circuitos magnéticos en serie-paralelo.
- Calcular la fuerza de atracción de un electroimán.
- Explicar la teoría de dominio del magnetismo.
- Describir el proceso de desmagnetización.
##  2. MARCO TEÓRICO (RESUMEN)
## 2.1 CARGA, DESCARGA DEL CAPACITOR Y CIRCUITOS FORMADORES DE ONDA SIMPLES 
### 2.1.1 INTRODUCCIÓN
### 2.1.2  ECUACIONES DE CARGA DEL CAPACITOR 
### 2.1.3  CAPACITOR CON UN VOLTAJE INICIAL 

![capacitor con un voltaje inicial (2)](https://user-images.githubusercontent.com/84431598/126885960-326f62f8-cf78-40f5-b440-31ee48600506.png)

### 2.1.4 ECUACIONES DE DESCARGA DEL CAPACITOR 
### 2.1.5 CIRCUITOS MÁS COMPLEJOS 
### 2.1.6 UNA APLICACIÓN DE LA TEMPORIZACIÓN RC 

![aplicacion (2)](https://user-images.githubusercontent.com/84431598/126885984-80544529-5afd-4704-bb26-bfd31cd314ae.png)

### 2.1.7 RESPUESTA AL PULSO DE CIRCUITOS RC 
### 2.1.8 ANÁLISIS TRANSITORIO POR COMPUTADORA 
## 2.2  MAGNETISMO Y CIRCUITOS MAGNÉTICOS 
### 2.2.1  LA NATURALEZA DE UN CAMPO MAGNÉTICO 
### 2.2.2 ELECTROMAGNETISMO 
### 2.2.3 FLUJO MAGNÉTICO Y DENSIDAD DE FLUJO 
### 2.2.4  CIRCUITOS MAGNÉTICOS 
### 2.2.5 ESPACIOS DE AIRE, DESBORDAMIENTO Y NÚCLEOS LAMINADOS 
### 2.2.6  ELEMENTOS EN SERIE Y EN PARALELO 
### 2.2.7 CIRCUITOS MAGNÉTICOS CON EXCITACIÓN DE CD 
### 2.2.8  INTENSIDAD DE CAMPO MAGNÉTICO Y CURVAS DE MAGNETIZACIÓN 
### 2.2.9  LEY DE CIRCUITOS DE AMPÈRE 
### 2.2.10  CIRCUITOS MAGNÉTICOS EN SERIE: A PARTIR DE DETERMINAR NI 
### 2.2.11 CIRCUITOS MAGNÉTICOS SERIE-PARALELO 
### 2.2.12 CIRCUITOS MAGNÉTICOS EN SERIE: A PARTIR DE NI DETERMINAR 
### 2.2.13 FUERZA DEBIDA A UN ELECTROIMÁN 
### 2.2.14 PROPIEDADES DE LOS MATERIALES MAGNÉTICOS 
### 2.2.15 MEDICIÓN DE CAMPOS MAGNÉTICOS
## 3. EXPLICACIÓN Y RESOLUCIÓN DE LOS EJERCICIOS
## 3.1 CARGA, DESCARGA DEL CAPACITOR Y CIRCUITOS FORMADORES DE ONDA SIMPLES 
### 3.1.1 INTRODUCCIÓN 

1. El capacitor de la figura 11-50 esta descargado.

a. ¿Cuál es el voltaje y la corriente del capacitor justo después de que se cierra el interruptor?

b. ¿Cuál es el voltaje y la corriente del capacitor después de que está totalmente
cargado?

![image](https://user-images.githubusercontent.com/84431598/126852643-193268ba-2bbb-4142-8945-c6046f614cf9.png)

![1-2](https://user-images.githubusercontent.com/84431598/126879112-4319a4a2-c55c-4398-90e3-e2bbadd7b164.png)

3. a. ¿A qué se parece un capacitor descargado en el instante que se conecta el
interruptor?

b. ¿Cómo se ve un capacitor cargado en el instante que se acciona el interruptor?

c. ¿A qué se parece un capacitor en estado estable de cd?

d. ¿Qué se quiere decir con i(0_) y con i(0_)?

![3](https://user-images.githubusercontent.com/84431598/126879075-e6a878f3-28d7-4fd6-815f-3e84a5ca928f.png)

5. Para un circuito de carga, R  =5.6 kΩ y vC (0^-) = 0 V. Si i(0^+) = 2.7 mA,
¿cuál es el valor de E? 

![5](https://user-images.githubusercontent.com/84431598/126879062-056ad449-4828-463b-b710-2effa29c79cf.png)


### 3.1.2 ECUACIONES DE CARGA DEL CAPACITOR 

7. Repita el problema 6 si R = 500 Ω, C =25 μF y E = 45 V, pero ahora
calcule y grafique valores en t = 0^+ s, 20, 40, 60, 80 y 100 ms.

	Determine la ecuación para el voltaje de carga v_C.
	Determine la ecuación  para la corriente de carga i_C.
	Por sustitución directa, calcule v_C  e i_C  para los valores dados.
	Grafique v_C  e i_C en papel milimétrico con los resultados del inciso (c).

![7-11](https://user-images.githubusercontent.com/84431598/126880967-6cde0171-66fd-4875-9013-8f5fd9be69e2.png)

![7-2 (2)](https://user-images.githubusercontent.com/84431598/126880981-d55746be-1c65-47b6-8fb2-f9744862e789.png)

![nadie (2)](https://user-images.githubusercontent.com/84431598/126881006-acd04f40-cdd9-40fd-9e21-b2e5b95674e4.png)

![7 CO (3)](https://user-images.githubusercontent.com/84431598/126916069-a1c5ef55-6a91-45da-84c5-2822137faea4.png)

![7VO (2)](https://user-images.githubusercontent.com/84431598/126916100-53697d49-92c9-44aa-ac0a-f72a13eac7e5.png)

9. Repita el problema 8 para el circuito de la figura 11-52.

![image](https://user-images.githubusercontent.com/84431598/126852704-951ccf26-c299-4608-8ba2-4b216f93f1fc.png)

![9 (2)](https://user-images.githubusercontent.com/84431598/126881379-5931f433-ca67-4886-9c4b-12c30b52e62f.png)

11. Determine la constante de tiempo para el circuito de la figura 11-50. ¿Cuánto
tiempo (en segundos) tardará el capacitor en cargarse?

![image](https://user-images.githubusercontent.com/84431598/126852759-eab1896b-00bc-4666-9140-92051c9d5261.png)

![11 (2)](https://user-images.githubusercontent.com/84431598/126881843-fbc6730e-53a3-4abe-b505-21630f68c61b.png)

13. Para la figura 11-50, el voltaje del capacitor con el interruptor abierto es de
0 V. Cierre el interruptor en t =0 y determine el voltaje y corriente del capacitor
en t = 0, 40, 80, 120, 160 y 200 us, use las curvas de la constante de
tiempo universal.

![image](https://user-images.githubusercontent.com/84431598/126852793-db058f59-0b6d-474a-9e70-99c0a63a9f55.png)

![am (2)](https://user-images.githubusercontent.com/84431598/126882697-42e7c7b9-fc53-44e3-a08d-1d0eb355c691.png)

![ab (2)](https://user-images.githubusercontent.com/84431598/126882736-d563a85e-cac7-4c07-a1c2-4b9fb8ae61a8.png)

![h (2)](https://user-images.githubusercontent.com/84431598/126882772-222fe811-0d1f-48ca-be7d-2efeed39bec7.png)

![q (2)](https://user-images.githubusercontent.com/84431598/126882800-bbe961f9-5248-43d9-99ea-3b8367a337c3.png)


15. Para la figura 11-2, la corriente se eleva a 3 mA cuando el interruptor se cierra.
El capacitor tarda 1 s para cargarse. Si E =75 V, determine R y C.

![11 2 (3)2](https://user-images.githubusercontent.com/84431598/126887702-8d0bd7ff-ae0c-4175-b3d8-6b8d56102f1b.png)

![15 (2)](https://user-images.githubusercontent.com/84431598/126887915-84296435-297b-4556-92fa-bcfb50d6f806.png)

17. Para la figura 11-2, determine E, R y C si el capacitor tarda 5 ms en cargarse,
la corriente en 1 constante de tiempo después de que el interruptor se cierra es
de 3.679 mA, y el capacitor se carga a 45 volts en estado estable.

![11 2 (3)2](https://user-images.githubusercontent.com/84431598/126887704-4d142024-bb35-4091-833f-15e87aba0f2c.png)

![17 (2)](https://user-images.githubusercontent.com/84431598/126888090-6d153acc-3fe2-4b87-b557-ed553874be5c.png)


### 3.1.3 CONDENSADOR CON UN VOLTAJE INICIAL 

19. El capacitor de la figura 11-50 tiene un voltaje inicial. Si V0 =10 V, ¿cuál es
el corriente justo después de que el interruptor se ha cerrado?

![image](https://user-images.githubusercontent.com/84431598/126852881-d0e63b5c-668e-4244-b475-930431c034dc.png)

![19 (2)](https://user-images.githubusercontent.com/84431598/126883149-bf6e5f4e-3384-410a-bdd8-29802892735c.png)

21. Para el capacitor de la figura 11-51, V0 = 30 V.

a. Determine la expresión para el voltaje de carga vC.

b. Determine la expresión para la corriente iC.

c. Grafique vC e iC.

![image](https://user-images.githubusercontent.com/84431598/126852919-9f56bc52-468c-487a-905f-73d96bc70824.png)

![21 (2)](https://user-images.githubusercontent.com/84431598/126888370-7c0acfc7-fb7f-4494-9087-6a79b9ae8b64.png)

![VOLTAJEGR21](https://user-images.githubusercontent.com/84431598/126889140-7d395ac2-f856-4b12-8cc5-6e806590c53d.png)

![CORRIENTE (2)](https://user-images.githubusercontent.com/84431598/126889117-8b93b1af-d867-43a7-ab11-3c241e0595bc.png)

### 3.1.4 ECUACIONES DE DESCARGA DEL CAPACITOR 

23. Para el circuito de la figura 11-53, suponga que el capacitor está cargado a
50 V antes de que el interruptor se cierre.

a. Determine la ecuación para el voltaje de descarga vC.

b. Determine la ecuación para la corriente de descarga iC.

c. Determine la constante de tiempo del circuito.

d. Calcule vC e iC en t = 0 s, t = t, 2, 3, 4, y 5t.

e. Grafique los resultados del inciso (d) con el eje del tiempo con escalas de
segundos y de constantes de tiempo.

![image](https://user-images.githubusercontent.com/84431598/126853000-4d4429ed-becd-4253-adfe-76ccc38a1aca.png)

![23 (2)](https://user-images.githubusercontent.com/84431598/126887342-143d7898-5ed4-427c-b321-b2cfd943dbbe.png)

![23-1 (2)](https://user-images.githubusercontent.com/84431598/126887365-4c2cf370-47d7-4d6f-ad35-31837e400fd5.png)

![23-2 (2)](https://user-images.githubusercontent.com/84431598/126887387-059e149d-6afb-48f5-a69e-d6a5aa400ade.png)

![23-3 (2)](https://user-images.githubusercontent.com/84431598/126887407-552a7121-0ab4-4841-b34e-de2a36163014.png)


25. Un capacitor de 4.7 uF se carga a 43 volts. Si un resistor de 39 kΩ se
conecta al capacitor, ¿cuál es el voltaje, 200 ms después de que se conecta
el resistor?

![25 (2)](https://user-images.githubusercontent.com/84431598/126883416-c1907d84-2cdc-4619-9f37-269178632858.png)

27. Para la figura 11-54, sea E = 200 V, R2 =1 kΩ y C = 0.5 μF. Después de
que el capacitor está totalmente cargado en la posición 1, el interruptor es movido
a la posición 2.

a. ¿Qué voltaje tiene el capacitor inmediatamente después de que el interruptor
es movido a la posición 2? ¿Cuál es la corriente?

b. ¿Cuál es la constante de tiempo de descarga?

c. Determine las ecuaciones de descarga para vC e iC.

![11-54(2)](https://user-images.githubusercontent.com/84431598/126886092-6b5fbf92-5266-4e3b-8f90-8c65a2436a76.png)

### 3.1.5 CIRCUITOS MÁS COMPLEJOS 

29. Los capacitores de la figura 11-55 están descargados. El interruptor se cierra
en t = 0. Determine la ecuación para vC. Calcule vC a una constante de tiempo
usando la ecuación y la curva de constante de tiempo universal. Compare sus
respuestas.

![11-55 (2)](https://user-images.githubusercontent.com/84431598/126886155-c8873c6f-cb84-4921-8c6f-5d9fcd26760c.png)

31. Repita el problema 30, del inciso (a) al (c) para el circuito de la figura 11-57.

![11-57 (2)](https://user-images.githubusercontent.com/84431598/126886182-3637df96-c893-4395-9c55-fa2131396ae1.png)

33. Para el circuito de la figura 11-54, el capacitor esta inicialmente descargado.
El interruptor es movido primero a la posición de carga y luego a la de descarga,
proporcionando la corriente que se muestra en la figura 11-58. El capacitor
se carga totalmente en 12.5 s. Determine E, R2 y C.

![11-54(2)](https://user-images.githubusercontent.com/84431598/126886207-b6e480a7-e556-4704-80a5-be1ac48cd700.png)

35. Determine los voltajes del capacitor y la corriente de la fuente para el circuito
de la figura 11-60 después de que se alcanzó el estado estable.

![11-60 (2)](https://user-images.githubusercontent.com/84431598/126886250-1e307d99-1b6d-4530-b8d3-4283b3c611d0.png)

### 3.1.6 UNA APLICACIÓN DE LA TEMPORIZACIÓN RC 

37. Para el circuito de alarma de la figura 11-32, si la entrada desde el sensor es
de 5 V, R = 750 kΩy la alarma es activada en 15 s cuando vC = 3.8 V, ¿que
valor tiene C?

### 3.1.7 RESPUESTA AL PULSO DE CIRCUITOS RC 

39. Considere la forma de onda de la figura 11-62.
a. ¿Cuál es el periodo?

b. ¿Cuál es el ciclo de trabajo?

c. ¿Cuál es el VRP?

![11-62 (2)](https://user-images.githubusercontent.com/84431598/126886306-4e77e3da-c0b1-4433-9e98-50f3a3288044.png)

41. Determine el tiempo de subida, de bajada y el ancho de pulso para el pulso de
la figura 11-64.

![11-64 (2)](https://user-images.githubusercontent.com/84431598/126886340-8fe5967a-7b88-4d90-bdd1-f1552d55c94d.png)

43. Se aplica un escalón al circuito de la figura 11-66. Si R = 150Ω y C =20 pF,
estime el tiempo que tarda en subir el voltaje de salida.


### 3.1.8  ANÁLISIS TRANSITORIO POR COMPUTADORA 

45. Grafique el voltaje del capacitor para el circuito de la figura 11-2 con E =
-25 V, R =40Ω, V0 = 0 V y C =400 μF (vease la Nota 1). Fije los valores
para la escala de la gráfica en t = 20 ms, utilice el cursor. Compare los resultados
que obtuvo con la ecuación 11-3 o la curva de la figura 11-15(a).

47. Considere la figura 11-57. Use Multisim y suponga condiciones iniciales de
cero para ambos capacitores. Haga lo siguiente (véase la Nota 3).
a. Haga una gráfica del voltaje del capacitor para el circuito de la figura
11-57 y encuentre vC en t = 4 ms.
b. Determine la corriente en el resistor de 4 _ en t = 3.5 ms.

49. Use PSpice para graficar el voltaje y la corriente del capacitor de un circuito
de carga con E = 25 V, R = 40 Ω, V0 = 0 V y C = 400 μF. Determine los
valores de la escala de la gráfica con el cursor. Use las ecuaciones 11-3 y 11-5
o las curvas de la figura 11-15 para comparar los resultados que obtuvo.

51. El interruptor de la figura 11-69 está cerrado en t = 0 s. Use PSpice para
hacer una gráfica de las formas de onda del voltaje y la corriente. Utilice el
cursor para determinar vC e iC en t = 10 ms.

![11-69 (2)](https://user-images.githubusercontent.com/84431598/126886488-e7ec136a-491f-4941-968f-5cd8c8c6d9d2.png)

53. Use PSpice para encontrar los voltajes y corrientes en el circuito de la figura
11-60. A partir de ello, determine los voltajes y corrientes finales (en estado
estable) y compare los resultados con los que obtuvo en el problema 35.
## 3.2  MAGNETISMO Y CIRCUITOS MAGNÉTICOS 
### 3.2.3 FLUJO MAGNÉTICO Y DENSIDAD DE FLUJO 

1. Vea la figura 12-41:
a. ¿Qué área, A1 o A2, utilizaría para calcular la densidad de flujo?
b. Si ϕ= 28 mWb, ¿cuál es la densidad de flujo en teslas?

![12-41 (2)](https://user-images.githubusercontent.com/84431598/126886643-80c096cf-bd16-4779-8d39-e03902271f5b.png)

3. El toroide de la figura 12-42 tiene una sección transversal circular y φ= 628
μWb. Si r1 = 8 cm y r2 = 12 cm, ¿cuál es la densidad de flujo en teslas?

![12-42 (2)](https://user-images.githubusercontent.com/84431598/126886620-5ce009dc-8d9e-44a0-8bf2-b2fffe087339.png)


### 3.2.5 ESPACIOS DE AIRE, DESBORDAMIENTO Y NÚCLEOS LAMINADOS 

5. Si la sección del nucleó en la figura 12-43 que mide 0.025 m por 0.04 m, tiene
un factor de apilamiento de 0.85 y B = 1.45 T, ¿qué valor tiene ϕ en webers?



### 3.2.6  ELEMENTOS EN SERIE Y EN PARALELO 
### 3.2.8 INTENSIDAD DE CAMPO MAGNÉTICO Y CURVAS DE MAGNETIZACIÓN 
### 3.2.9 LEY DE CIRCUITOS DE AMPÈRE 
### 3.2.10  CIRCUITOS MAGNÉTICOS EN SERIE: A PARTIR DE DETERMINAR NI 
### 3.2.11 CIRCUITOS MAGNÉTICOS SERIE-PARALELO
### 3.2.12 CIRCUITOS MAGNÉTICOS EN SERIE: A PARTIR DE NI DETERMINAR 
### 3.2.13 FUERZA DEBIDA A UN ELECTROIMÁN 
## 4. CONCLUSIONES
## 4.1 CARGA, DESCARGA DEL CAPACITOR Y CIRCUITOS FORMADORES DE ONDA SIMPLES 
## 4.2  MAGNETISMO Y CIRCUITOS MAGNÉTICOS 
-  Un electroimán es básicamente una bobina de alambre alrededor de un núcleo magnético.
-  Los materiales que pueden ser magnetizados se llaman ferromagnéticos.
-  Los polos magnéticos desiguales se atraen entre sí y los polos iguales se repelen uno a otro.
## 5. VIDEO
###  6. BIBLIOGRAFÍA
- Roobins, A y Miller, W. (2007). *Análisis de circuitos teoría y práctica (4ta ed),* México DF, México: Cengage Learning.
-  Floyd, T. (2007). *Principios de circuitos eléctricos (8va ed),* México DF, México: Pearson Educación.

