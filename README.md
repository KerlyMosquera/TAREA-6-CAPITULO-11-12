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

![1 (3)](https://user-images.githubusercontent.com/84431598/127395365-cc398bd2-1b9b-4674-bbdb-6b73dc35e833.png)

### 2.1.6 UNA APLICACIÓN DE LA TEMPORIZACIÓN RC 

![aplicacion (2)](https://user-images.githubusercontent.com/84431598/126885984-80544529-5afd-4704-bb26-bfd31cd314ae.png)

### 2.1.7 RESPUESTA AL PULSO DE CIRCUITOS RC 

![circuitos rc 1png](https://user-images.githubusercontent.com/84431598/127393196-69e96c36-0326-4fac-8faf-8aaa6d917179.png)

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

![23V (2)](https://user-images.githubusercontent.com/84431598/126917076-1fcc3873-4aeb-4c49-9a7d-a199d41919fc.png)

![23I (2)](https://user-images.githubusercontent.com/84431598/126917104-be1d7a68-268a-4857-bad4-055d4300e4db.png)

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

![image](https://user-images.githubusercontent.com/84458025/127579637-a1ee90f8-03bb-460d-9e52-8f9e3d54c6cc.png)

![image](https://user-images.githubusercontent.com/84458025/127579857-934c2997-1610-49f6-93f8-41f44e1cbeb7.png)

![image](https://user-images.githubusercontent.com/84458025/127579891-97bc0389-4e3b-4974-9113-e32daebca59b.png)

![image](https://user-images.githubusercontent.com/84458025/127579948-bc6cfc17-4376-4ded-a054-c6a779e7fc1f.png)

![image](https://user-images.githubusercontent.com/84458025/127579996-6a29a356-9e26-4a4e-847c-a27d9a1af639.png)

![image](https://user-images.githubusercontent.com/84458025/127580054-02e931c1-1363-4d55-b3c8-353804039719.png)

![image](https://user-images.githubusercontent.com/84458025/127580091-89f801b1-696d-4112-a157-0049dc22e0b5.png)






### 3.1.5 CIRCUITOS MÁS COMPLEJOS 

29.. Para la figura 11-54, C esta totalmente cargado antes de que el interruptor sea movido para la descarga. Justo despues que es movido, la corriente es iC _4 mA y C tarda 20 ms en descargarse. Si E _ 80 V, ¿que valores tienen R2 y C?

![image](https://user-images.githubusercontent.com/84458025/127580982-351de31c-fbc8-4b2e-992a-468c6bd6b240.png)

![image](https://user-images.githubusercontent.com/84458025/127581003-c636140a-dfe8-4c26-be76-3a10e0b1d769.png)

![image](https://user-images.githubusercontent.com/84458025/127581056-6ef4ae73-f7fb-441a-be6f-9b51ef0bc11c.png)

![image](https://user-images.githubusercontent.com/84458025/127581074-9d6d1207-b718-45d4-a739-f34824ade89f.png)

![image](https://user-images.githubusercontent.com/84458025/127581142-7e5ef64e-f7bd-4630-b874-9a97d9aff46b.png)

![image](https://user-images.githubusercontent.com/84458025/127581192-5a8b5272-0fae-4845-8546-47cefb2defca.png)


31.Los capacitores de la figura 11-55 estan descargados. El interruptor se cierra en t=0. Determine la ecuacion para vC. Calcule vC a una constante de tiempo usando la ecuacion y la curva de constante de tiempo universal. Compare sus respuestas.

![image](https://user-images.githubusercontent.com/84458025/127581295-11c5d237-5fe4-40f3-80fa-d6e714e319ff.png)

![image](https://user-images.githubusercontent.com/84458025/127581691-a2b1e690-c8be-4f22-9ea5-043ca180d3e2.png)

![image](https://user-images.githubusercontent.com/84458025/127581746-b541c4b1-c47b-435c-8ce5-3deba031d1e3.png)

![image](https://user-images.githubusercontent.com/84458025/127581787-1600c38e-6f35-45e7-8c4a-5df593f68cb1.png)

![image](https://user-images.githubusercontent.com/84458025/127581821-905dab2e-237f-4a4c-abb8-be636782d226.png)

![image](https://user-images.githubusercontent.com/84458025/127581874-ae00121c-824a-4718-a2ff-17d037cd4b39.png)


33. Para la figura 11-56, el interruptor se cierra en t =0. Si V0 =0 V.

![image](https://user-images.githubusercontent.com/84458025/127581940-dd0e2431-ce7e-463f-a4be-f616d879896a.png)

![image](https://user-images.githubusercontent.com/84458025/127582192-b7448459-e615-4b48-9978-9a32c388a1cc.png)

![image](https://user-images.githubusercontent.com/84458025/127582328-faa40768-159e-4683-9050-d23f0cb4dadc.png)

![image](https://user-images.githubusercontent.com/84458025/127582455-759103c8-66be-4a88-bf46-35a002b47965.png)

35.Repita el problema 30, del inciso (a) al (c) para el circuito de la figura 11-57.

![image](https://user-images.githubusercontent.com/84458025/127582785-bbd8625a-096f-4cad-a297-ade1c45f862b.png)

![image](https://user-images.githubusercontent.com/84458025/127582900-7cf543c6-b41d-4ee6-914d-7c6c2242d129.png)

![image](https://user-images.githubusercontent.com/84458025/127582992-b9a59d11-eb1b-47af-abf5-6860c647a3f1.png)

![image](https://user-images.githubusercontent.com/84458025/127583121-8d86e7f3-e4b8-4cb8-8879-ceffd34ebcc2.png)

![image](https://user-images.githubusercontent.com/84458025/127583265-fd8f49c9-903e-4085-a457-0115c3f22f09.png)

![image](https://user-images.githubusercontent.com/84458025/127583408-6d8ee4ea-f485-4417-8868-fe5f85b87d59.png)

![image](https://user-images.githubusercontent.com/84458025/127583489-d08f5440-caa7-4875-892d-be7b866aa15c.png)

### 3.1.6 UNA APLICACIÓN DE LA TEMPORIZACIÓN RC 

37.Determine los voltajes del capacitor y la corriente de la fuente para el circuito de la figura 11-60 despues de que se alcanzo el estado estable.

![image](https://user-images.githubusercontent.com/84458025/127583659-a54160a7-0423-4651-865b-3deef1ef2470.png)

![image](https://user-images.githubusercontent.com/84458025/127583788-715bc209-abdc-4398-9949-b93560b5f606.png)

![image](https://user-images.githubusercontent.com/84458025/127584115-fc7e1d9e-fe6c-408b-87f7-2de181dc686a.png)

### 3.1.7 RESPUESTA AL PULSO DE CIRCUITOS RC 

39.Para el circuito de alarma de la figura 11-32, si la entrada desde el sensor es de 5 V, R _ 750 k_ y la alarma es activada en 15 s cuando vC _ 3.8 V, ¿Qué valor tiene C.

![image](https://user-images.githubusercontent.com/84458025/127584283-60cec4a4-5cac-4118-9ed9-cef322304f01.png)

![image](https://user-images.githubusercontent.com/84458025/127584389-69821374-03a8-44c8-96c4-0747505f6901.png)

41.Considere la forma de onda de la figura 11-62!

![image](https://user-images.githubusercontent.com/84458025/127584504-d1ecbaa1-2902-4186-b549-2a50e7417c96.png)

a. ¿Cual es el periodo?

b. ¿Cual es el ciclo de trabajo?

c. ¿Cuál es el PPR?!

![image](https://user-images.githubusercontent.com/84458025/127584669-98d0a2da-663b-438c-93ca-443496ff056a.png)

43.Determine el tiempo de subida, de bajada y el ancho de pulso para el pulso de la figura 11-64

![image](https://user-images.githubusercontent.com/84458025/127584772-dc5da9d8-c366-4d47-b1eb-b7869147498d.png)

![image](https://user-images.githubusercontent.com/84458025/127584830-c74c187a-130b-44f2-aa3b-69de2cafc0d7.png)

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

![image](https://user-images.githubusercontent.com/84458025/127586272-24f29d0d-ba59-4b7a-b07b-56faa42da157.png)

3. El toroide de la figura 12-42 tiene una sección transversal circular y φ= 628
μWb. Si r1 = 8 cm y r2 = 12 cm, ¿cuál es la densidad de flujo en teslas?

![12-42 (2)](https://user-images.githubusercontent.com/84431598/126886620-5ce009dc-8d9e-44a0-8bf2-b2fffe087339.png)

![image](https://user-images.githubusercontent.com/84458025/127586316-ca243a06-a223-4b5b-a9a7-0b13e0e7ac4c.png)

### 3.2.5 ESPACIOS DE AIRE, DESBORDAMIENTO Y NÚCLEOS LAMINADOS 

5. Si la sección del nucleó en la figura 12-43 que mide 0.025 m por 0.04 m, tiene un factor de apilamiento de 0.85 y B = 1.45 T, ¿qué valor tiene ϕ en webers?

![image](https://user-images.githubusercontent.com/84458025/127586388-9aad9b3c-8949-41f9-b5ca-d5765907c487.png)

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

