# Informe_tarea4

1.-Objetivos

General 

Identificar los conceptos de los capítulos 7 y 8 con la finalidad de resolver los ejercicios propuestos.

Específicos 

Analizar y aplicar los métodos expuestos en los capítulos siete y ocho.

Determinar las relaciones serie-paralelo de los circuitos resistivos.

Identificar el teorema de superposición, de Thevenin y el de Norton.

2.-Marco teórico

![image](https://user-images.githubusercontent.com/105823435/176978654-26c620e2-5864-42ce-baef-c8d42f17453d.png)
![image](https://user-images.githubusercontent.com/105823435/176978674-b9ba12cf-19b4-4c95-b114-c299195d9b42.png)

![image](https://user-images.githubusercontent.com/105823435/176978725-42707986-a4b7-4224-8a90-67aad56db5ae.png)
![image](https://user-images.githubusercontent.com/105823435/176978762-82f542e5-41ff-4662-97b6-625732f98b93.png)

3.-Resolucion de ejercicios

SECCIÓN 7–1 Identificación de relaciones en serie-paralelo 

2.Visualice y trace los siguientes circuitos en serie-paralelo: 

a)Una combinación en paralelo de tres ramas, cada rama con dos resistores en serie. 

![image](https://user-images.githubusercontent.com/105823435/176978922-792e4905-a0fc-4986-8e94-e3521f211c92.png)

b)Una combinación serie de tres circuitos en paralelo, cada circuito con dos resistores. 

![image](https://user-images.githubusercontent.com/105823435/176978941-40f057f1-dffa-466b-a88b-57677e86f968.png)

4.En cada uno de los circuitos de la figura 7-63, identifique las relaciones en serie-paralelo de los resistores vistas desde la fuente. 

![image](https://user-images.githubusercontent.com/105823435/176978966-d84f8398-21e5-4e12-bf70-7b14b1d73323.png)

a)La resistencia R1 está en serie y a su vez esta combinada con la resistencia R4 Y R5 que están en paralelo.

b)Las resistencias R4 Y R1 están en paralelo y estas están combinadas a las resistencias R2 y R3 que están en paralelo. Todas las resistencias están en paralelo.

c)Las resistencias R1 y R2 están conectadas en serie y están combinadas con las resistencias R3 y R4 que están en paralelo. Las resistencias R8 y R7 están en serie combinada con la resistencia R6 que está en paralelo con ellas mismo.

6.Desarrolle un diagrama esquemático de la tarjeta de circuito impreso de doble cara mostrada en la figura 7-65, y marque los valores de resistor.

![image](https://user-images.githubusercontent.com/105823435/176979009-2a8d92b0-474a-4c83-8e7b-3402b486afef.png)

![image](https://user-images.githubusercontent.com/105823435/176979031-58d3db5a-5bac-4cbc-87b0-76523858dee0.png)

SECCIÓN 7–2 Análisis de circuitos resistivos en serie-paralelo 

8.Un cierto circuito se compone de dos resistores en paralelo. La resistencia total es de 667 Ω. Uno de los resistores es de 1.0 kΩ. ¿Cuál es el otro resistor? 

RT = R1*R2/R1+R2

R2 = R1*RT/R1-RT

R2 = 1kΩ*0.667kΩ/1kΩ-0.667Ω = 2kΩ

10.Repita el problema 9 para cada uno de los circuitos mostrados en la figura 7-63.

![image](https://user-images.githubusercontent.com/105823435/176979144-792fcb04-3a2e-476e-b4b7-2b37a1f676fb.png)

a)RA = R1+R2+ (R3*R4/R3+R4)

RA = 1kΩ+1kΩ+ (10kΩ*4.7kΩ/10kΩ+4.7Ω) = 5.2kΩ

RB = R5+R6+ (R6*R7/R6+R7)

b)RB = 3.3kΩ+1.8kΩ+(6.8kΩ/2kΩ) = 8.5kΩ

RT = 1/(1/RA + 1/RB) 

RT = 1/(1/5.2kΩ + 1/8.5kΩ) = 3.23kΩ

c)RT = 1/(1/R1 + 1/R2 + 1/R3 + 1/R4)

RT = 1/(1/1MΩ + 1/1MΩ + 1/3.3MΩ + 1/6.2MΩ) = 406kΩ

12.Determine la corriente a través de cada resistor en cada circuito de la figura 7-63; luego calcule cada caída de voltaje. 

![image](https://user-images.githubusercontent.com/105823435/176979186-355f3649-6fa8-4b22-96f5-ca84621d489c.png)

a)Corriente

IT = (1V/699Ω) = 1.43mA

IR1 = (2.32kΩ/3.32kΩ)*1.43mA = 1mA

IR2 = (1kΩ/3.32kΩ)*1.43mA = 431µA

IR3 = (3.3kΩ/5.5kΩ)*341µA = 259µA

IR4 = (570mV/3.3kΩ) = 173µA

Caída de voltaje 

VR1 = (1mA)*(1kΩ) = 1V

VR2 = (431µA)*(1kΩ) = 431mV

VR3 = (259µA)*(2.2kΩ) = 570mV

VR4 = VR3 =  570mV

b)Corriente 

IR1 = (1V/1MΩ) = 2µA

IR2 = (2V/3.3MΩ) = 606nA

IR3 = (2V/6.2MΩ) = 323nA

IR4 = (2V/1MΩ) = 2µA

Caída de voltaje 

VR4=VR4=2V

c)Corriente

IT = (5V/3.23kΩ) = 1.55mA

IR1 = IR2 = (8.5kΩ/13.7)*1.55mA = 962 µA

IR3 = (4.7kΩ /14.7kΩ)*962 = 308µA

IR4 = (10kΩ/14.7kΩ)*962 = 654µA

IR5 = (5.2kΩ/13.7kΩ)*1.55mA = 588µA

IR6 = IR7 = (588µΩ/2) = 294µA

IR8 = IR5 = 588µA

Caída de voltaje 

VR1 = VR2 = (962µA)*(1 kΩ) = 962mA

VR3 = VR4 = (308µA)*(10 kΩ) = 3.08V

VR5 = (588 µA)*(3.3 kΩ) =1.94V

VR6 = VR7 = (294µA)*(6.8 kΩ) = 2V

VR8 = (588 µA)*(1.89 kΩ) = 1.06V

14.Determine la resistencia entre A y B en la figura 7-67 sin la fuente.

![image](https://user-images.githubusercontent.com/105823435/176979260-1a7165dd-73fb-42b6-a993-4db0182986a1.png)

RAB = (10kΩ+5.6 kΩ)

RAB = 15.6 kΩ /4.7 kΩ = 3.31 kΩ

16.Determine el voltaje en cada nodo con respecto a tierra en la figura 7-68.

![image](https://user-images.githubusercontent.com/105823435/176979278-1c7c72f9-0c8d-40da-a076-2afdade16f64.png)

VA = (56kΩ/716kΩ) * 50V = 3.91V

VB = (616kΩ/716kΩ) * 50V = 43V

VC = 50V

VD = (100kΩ/1.1MΩ) * 50V = 4.55V

18.Determine la resistencia del circuito mostrado en la figura 7-67 como se ve desde la fuente de voltaje. 

![image](https://user-images.githubusercontent.com/105823435/176979289-d8bd6805-365a-4ac7-b25a-6acfd9d266ef.png)

RT = (10 kΩ/4.7 + 5.6 kΩ)+ (1.8 kΩ/81 kΩ+1 kΩ)

RT = 6.02 kΩ

20.Determine el voltaje, VAB, en la figura 7-69. 

![image](https://user-images.githubusercontent.com/105823435/176979307-f0057134-52ad-4974-9e74-55407208f562.png)

Rama derecha

RR = (R2+1/(1/R5+1/R7)+R8)

RR = 330Ω+ (1/1/600Ω+1/680Ω)+100Ω = 1710Ω

Rama izquierda 

RL = R3+R4
RL = 470Ω+560Ω = 1030Ω

RT = (R1+Rb/Ra) 

RT = 10kΩ+643Ω/1710Ω = 1.64kΩ

IT = 100V/1.64kΩ = 60.9mA

Corriente de la rama derecha 

IR = (RL/RL+RR)*IT

IR = (1030Ω/2740Ω)*60.9mA = 22.9mA

Corriente de la rama izquierda 

IL = (RR/RL+RR)*IT

IL = (1710 Ω/274 Ω)*60.9mA = 38mA

22.En la figura 7-71, determine la resistencia entre el nodo A y cada uno de los demás nodos (RAB, RAC, RAD, RAE, RAF, y RAG). 

![image](https://user-images.githubusercontent.com/105823435/176979333-72d10a18-b743-4263-9eb5-8944cc91e68a.png)

RAB=R1 ‖(R2+R7+R8)=(1kΩ)‖(2.2kΩ+3.3kΩ+4.7kΩ)=911kΩ


















