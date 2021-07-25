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


17. Para la figura 11-2, determine E, R y C si el capacitor tarda 5 ms en cargarse,
la corriente en 1 constante de tiempo después de que el interruptor se cierra es
de 3.679 mA, y el capacitor se carga a 45 volts en estado estable.


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

25. Un capacitor de 4.7 uF se carga a 43 volts. Si un resistor de 39 kΩ se
conecta al capacitor, ¿cuál es el voltaje, 200 ms después de que se conecta
el resistor?

![25 (2)](https://user-images.githubusercontent.com/84431598/126883416-c1907d84-2cdc-4619-9f37-269178632858.png)

### 3.1.5 CIRCUITOS MÁS COMPLEJOS 
### 3.1.6 UNA APLICACIÓN DE LA TEMPORIZACIÓN RC 
### 3.1.7 RESPUESTA AL PULSO DE CIRCUITOS RC 
### 3.1.8  ANÁLISIS TRANSITORIO POR COMPUTADORA 
## 3.2  MAGNETISMO Y CIRCUITOS MAGNÉTICOS 
### 3.2.1  LA NATURALEZA DE UN CAMPO MAGNÉTICO 
### 3.2.2 ELECTROMAGNETISMO
### 3.2.3 FLUJO MAGNÉTICO Y DENSIDAD DE FLUJO 
### 3.2.4 CIRCUITOS MAGNÉTICOS
### 3.2.5 ESPACIOS DE AIRE, DESBORDAMIENTO Y NÚCLEOS LAMINADOS 
### 3.2.6  ELEMENTOS EN SERIE Y EN PARALELO 
### 3.2.7  CIRCUITOS MAGNÉTICOS CON EXCITACIÓN DE CD 
### 3.2.8 INTENSIDAD DE CAMPO MAGNÉTICO Y CURVAS DE MAGNETIZACIÓN 
### 3.2.9 LEY DE CIRCUITOS DE AMPÈRE 
### 3.2.10  CIRCUITOS MAGNÉTICOS EN SERIE: A PARTIR DE DETERMINAR NI 
### 3.2.11 CIRCUITOS MAGNÉTICOS SERIE-PARALELO
### 3.2.12 CIRCUITOS MAGNÉTICOS EN SERIE: A PARTIR DE NI DETERMINAR 
### 3.2.13 FUERZA DEBIDA A UN ELECTROIMÁN 
### 3.2.14 PROPIEDADES DE LOS MATERIALES MAGNÉTICOS 
### 3.2.15 MEDICIÓN DE CAMPOS MAGNÉTICOS
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

