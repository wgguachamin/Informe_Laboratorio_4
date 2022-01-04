PRACTICA N°04 TEOREMA DE SUPERPOSICIÓN
1. OBJETIVOS DE LA PRÁCTICA

1.1. OBJETIVO GENERAL

Comprobar experimentalmente el Teorema de superposición, mediante la simulación de un circuito mixto utilizando laboratorios virtuales, para implementar los conocimientos adquiridos en clase y analizar de forma correcta el circuito planteado.

1.2. OBJETIVOS ESPECÍFICOS

- Determinar el fundamento que aplica el Teorema de superposición para el análisis de circuitos eléctricos que cuentan con varias fuentes.
- Establecer los pasos básicos que se necesitan para aplicar el Teorema de superposición.
- Determinar la utilidad del Teorema de superposición en el análisis de circuitos eléctricos.

2. MARCO TEÓRICO

TEOREMA DE SUPERPOSICIÓN

![Mapas mentales con líneas (3)](https://user-images.githubusercontent.com/94008521/147993609-55b34682-f166-41fd-8ea1-08ad98c6b7d9.png)

3. EXPLICACIÓN DEL PROCEDIMIENTO

MATERIAL Y EQUIPO REQUERIDO

![image](https://user-images.githubusercontent.com/94008521/147993753-01e39dd4-17ba-4d72-bc87-d87d110e2593.png)

3.1 Arme el circuito que se muestra en la figura 4.1.

![image](https://user-images.githubusercontent.com/93960809/147992556-2d947b99-ff88-47a2-b3ed-b39a5042cc23.png)

3.2 Con las dos fuentes conectadas, mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

Medición de voltaje y corriente en Tinkercad:

![image](https://user-images.githubusercontent.com/93960809/147992602-281d7017-8e54-4a6b-b571-62afa6a29a30.png)

Simulación Multisim: 

![image](https://user-images.githubusercontent.com/93960809/147992652-509c37e4-7c4d-4c8d-934a-e703924b43c6.png)

3.3 Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

Cuando V2: 12 V es cero

En primer lugar, redibujamos el circuito para analizarlo solo con la fuente de 20V.

![image](https://user-images.githubusercontent.com/93960809/147992731-2558c1ae-ea7d-4e65-90f9-1840ecf653b2.png)

Mediante el método de mallas calculamos la corriente y voltaje solicitado. 

![image](https://user-images.githubusercontent.com/93960809/147992965-fc8ef823-d502-43d3-b9d8-3221a15ac25a.png)

El sistema de ecuaciones para encontrar la corriente es: 

![image](https://user-images.githubusercontent.com/93960809/147992995-d92ff987-7b0e-4d85-a6d0-ed44eef49ccc.png)

![image](https://user-images.githubusercontent.com/93960809/147993016-87ef2ec7-ca87-495f-a57e-c1c65a163533.png)

Por tanto, los valores de las corrientes que pasa por cada una de las mallas son: 

![image](https://user-images.githubusercontent.com/93960809/147993038-952daa2e-5645-408f-bd89-9a732c7b3a9f.png)

Por lo que, calculando la corriente que pasa por Ix:

![image](https://user-images.githubusercontent.com/93960809/147993060-209e1eb3-aaec-43af-8431-655b9742ffaf.png)

Para calcular el voltaje VA usamos la ley de ohm: 

![image](https://user-images.githubusercontent.com/93960809/147993068-ca924b6e-b6c7-4447-b98b-b426c502d037.png)

A continuación, la captura de pantalla de corriente y voltaje medidos tanto en Tinkercad como en multisim: 

![image](https://user-images.githubusercontent.com/93960809/147993101-a735605e-818d-4e79-966a-30dee70c2775.png)

![image](https://user-images.githubusercontent.com/93960809/147993110-9e94ba5e-da95-4854-a8a8-198d2d1f648a.png)

3.4 Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

Primero redibujamos el circuito para analizar la corriente y voltaje solo con la fuente de 12V. 

![image](https://user-images.githubusercontent.com/93960809/147993127-739fc921-fb1a-4611-95e3-930f87c309e3.png)

Encontrando la resistencia equivalente para las resistencias de 1.1kΩ y 2.2 kΩ y redibujando el circuito para una mejor comprensión: 

![image](https://user-images.githubusercontent.com/93960809/147993158-2779b806-4711-48ab-9756-3fef8cc4ba14.png)

Realizando una suma de las resistencias que se encuentran en serie 0.6875kΩ y las de 0.82kΩ, y redibujando el circuito: 

![image](https://user-images.githubusercontent.com/93960809/147993169-9d694ac7-ec50-4fde-be7c-f75ab83431d2.png)

Encontrando la resistencia equivalente entre 1.51kΩ y 0.47kΩ que se encuentran en paralelo para obtener la resistencia total: 

![image](https://user-images.githubusercontent.com/93960809/147993183-18f6ee25-58a7-46de-8666-4d4a0f5eaf80.png)

Calculando la intensidad total del circuito: 

![image](https://user-images.githubusercontent.com/93960809/147993198-939b8e58-3fa0-4d9f-a27f-1da210a51b7b.png)

Aplicando la fórmula del divisor de corriente para encontrar Ix: 

![image](https://user-images.githubusercontent.com/93960809/147993221-7a844d6d-cc04-4b96-8806-f9d545ce8004.png)

Calculando la corriente que circula por la resistencia de 820Ω para luego encontrar el valor del voltaje. 

![image](https://user-images.githubusercontent.com/93960809/147993245-1b11995e-25c7-4a8d-8bbd-ac61e484d748.png)

Para calcular el voltaje VA usamos la ley de ohm: 

![image](https://user-images.githubusercontent.com/93960809/147993267-cb37087f-5aa0-4b4b-946c-c7eb6121e2db.png)

Pero, como estamos calculando el voltaje con la polaridad opuesta: 

![image](https://user-images.githubusercontent.com/93960809/147993302-c7fbb748-c62c-49e0-afc5-a1428c1737c1.png)

A continuación, la captura de pantalla de corriente y voltaje medidos tanto en Tinkercad como en multisim:

![image](https://user-images.githubusercontent.com/93960809/147993408-87f0739d-1a18-4de2-a732-15428e0bc1e8.png)

![image](https://user-images.githubusercontent.com/93960809/147993414-733c5b90-a263-431e-a9c1-fc19ef87e161.png)

Finalmente, el valor de la corriente y del voltaje del circuito es: 

![image](https://user-images.githubusercontent.com/93960809/147993320-6a45514e-1315-42b9-a159-3034470d4431.png)

A continuación, las tablas de medición de voltaje y de corriente:

![image](https://user-images.githubusercontent.com/93960809/147993420-fbc70703-a0e7-4144-a328-dcd528bbe856.png)

![image](https://user-images.githubusercontent.com/93960809/147993426-4b2fd6f4-c9df-4b8b-bd8d-548e8550d896.png)

4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR


5. VIDEO

https://youtu.be/HEL9fwg2MGc

6. CONCLUSIONES

-	El fundamento que emplea el Teorema de superposición se basa en que el voltaje o la corriente que pasa por cualquier elemento de un circuito puede obtenerse sumando algebraicamente todos los voltajes o corrientes individuales generados, a su vez para realizar el análisis se establece que en cualquier rama de un circuito con múltiples  fuentes, se puede calcular la corriente o voltaje reemplazando las fuentes por sus resistencias internas, recordando que para una fuente de voltaje su resistencia interna es cero y para una fuente de corriente su resistencia interna se considera infinita.
-	Los pasos básicos para poder implementar el teorema de superposición son 4: primero dejar una dejar una fuente de voltaje (o de corriente) a la vez en el circuito y reemplazar cada una de las demás fuentes de voltaje (o de corriente) con su resistencia interna. Segundo determinar la corriente (o el voltaje) particular que se desea justo como si hubiera sólo una fuente en el circuito. Tercero tomar la siguiente fuente que haya en el circuito y repetir los pasos 1 y 2. Hacer esto con cada una de las fuentes pertenecientes al circuito. Por último, el cuarto paso es sumar algebraicamente las corrientes producidas por cada fuente individual para encontrar la corriente real en una rama dada. (Si las corrientes poseen diferentes direcciones se restan de lo contrario se suman). Una vez determinada le corriente ya podemos aplicar Leyes de Ohm.
-	El Teorema de superposición es de mayor utilidad dentro de circuitos eléctricos que posean 2 o más fuentes de voltaje, dado que, nos permite reducir o redibujar nuestro circuito para analizar de forma individual la corriente o voltaje generado por las fuentes dentro del mismo, es decir que permite transformar un circuito complejo en uno más simple para analizar. 

7. BIBLIOGRAFÍA


