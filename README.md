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

RAG=R8 ‖(R1+R2+R7)=(4.7kΩ)‖(1kΩ+2.2kΩ+3.3kΩ)=2.73kΩ

RAC=R1+R2 ‖(R7+R8)=(1kΩ+2.2kΩ)‖(3.3kΩ+4.7kΩ)=2.29kΩ

RAD=RAC R3 ‖(R4+R5+R6)=(2.29kΩ+1kΩ)‖(10.2kΩ)=3.20kΩ

RAE=RAC+R3+R4 ‖(R5+R6)=(2.29kΩ+3.2kΩ)‖(8kΩ)=4.58kΩ

RAF=RAC+R6 ‖(R3+R4+R5)=(2.29kΩ+4.7kΩ)‖(6.5kΩ)=5.02kΩ

24.Determine el valor de cada resistor mostrado en la figura 7-73. 

![image](https://user-images.githubusercontent.com/105823435/176979453-4e5703d7-407e-4267-896f-d3682f34ce20.png)

V2=V5-V6=5V-1V=4V

I2=I6=2Ω/4V==0.5A

I5=I8-I6=1A-0.5A=0.5A

I1=I2+I5+I4=0.5A+0.5A+1A=2A

I3=IT-I1=40V-20V=20V

V1=20Ω/2A=10V

V4=V3-V1=10V

V8=V4-V5=5V

R1=(10V/2A)=5Ω

R2=(4V/0.5A)=8Ω

R3=(20V/2A)=10Ω

R4=(10V/1A)=10Ω

R5=(5V/0.5A)=10Ω

R6=(1V/0.5A)=2Ω

R7=(20V/4A)=5Ω

R8=(5V/1A)=5Ω

SECCIÓN 7–3 Divisores de voltaje con cargas resistivas

26.La salida de una batería de 12 V se divide para obtener dos voltajes de salida. Se utilizan tres resistores de 3.3 kΩ para proporcionar dos tomas. Determine los voltajes de salida. Si se conecta una carga de 10 kΩ a la más alta de las salidas, ¿cuál será su valor con carga?

VA=6.6kΩ/9.9kΩ*12V=8V

VB=3.3kΩ/9.9kΩ*12V=4V

Se conecta una resistencia de 10kΩ conectada desde la toma A a tierra:

RAB=(6.6kΩ*10kΩ)/(6.6kΩ+10kΩ)=3.

V(A (carga))=3.98kΩ/7.28kΩ*12V=6.56V

28.En la figura 7-74, determine el voltaje de salida sin carga entre las terminales de salida. Con una carga de 100 kΩ conectada de A a B, ¿cuál es el voltaje de salida?

![image](https://user-images.githubusercontent.com/105823435/176979576-f0f15fa6-78eb-428b-8ea0-8b21eed9338f.png)

RT=10kΩ+5.6kΩ+2.7kΩ=18.3kΩ

Vsalida=(R2+R3)/(R1+R2+R3 )

Vsalida=8.3kΩ/18.3kΩ*22V=9.98V

Con una carga de 100kΩ conectada de A a B

RT=R1+((R2+R3)RL)/(RL+R2+R3 )

RT=10kΩ+((8.3kΩ)+(100kΩ))/108.3kΩ=17.7kΩ

Vsalida=7.7kΩ/17.7kΩ*22V=9.57V

30.En la figura 7-74, determine la corriente continua extraída de la fuente sin carga entre las terminales de salida. Con una carga de 33 kΩ, ¿cuál es la corriente extraída? 

![image](https://user-images.githubusercontent.com/105823435/176979641-170cf54f-c4bd-4a54-a2c7-c3257c161043.png)

RT=10kΩ+5.6kΩ+2.7kΩ=18.3kΩ

I=22V/18.3kΩ=1.2mA

RT=10kΩ+((8.3kΩ)+(33kΩ))/(8.3kΩ+33kΩ)=16.6kΩ

I=22V/16.6kΩ=1.33mA

32.El divisor de voltaje de la figura 7-75 tiene una carga controlada por interruptor. Determine el voltaje en cada toma (V1, V2 y V3) para cada posición del interruptor. 

![image](https://user-images.githubusercontent.com/105823435/176979654-ce00bbd4-b3c3-4027-9c14-21de8956a888.png)

Posición 1:

RT=10kΩ+20.82kΩ=30.8kΩ

V1=20.8kΩ/30.8kΩ*120V=81V

V2=((20kΩ))/30kΩ*81V=54V

V3=10kΩ/30kΩ*81V=27V

Posición 2:

RT=20kΩ+15.5kΩ=35.5kΩ

V1=(10kΩ+15.5kΩ)/335.5kΩ*120V=86.2V

V2=((15.5kΩ))/35.5kΩ*81V=52.4V

V3=10kΩ/20kΩ*52.4V=26.2V

34.Diseñe un divisor de voltaje que produzca una salida de 6 V sin carga y un mínimo de 5.5 V entre los extremos de una carga de 1.0 kΩ. El voltaje de fuente es de 24 V y la corriente extraída sin carga no debe exceder de 100 mA.   

Imax=10mA

RT=24V/100mA=240Ω

R2/RT *24V=6V

24R2=6RT

R2=(6*240Ω)/24=60Ω

R1=240Ω-60Ω=180Ω

SECCIÓN 7–4 Efecto de carga de un voltímetro 

36.Determine la resistencia interna de un voltímetro de 20,000 Ω/V en cada uno de los siguientes ajustes de intervalo. 

a) Rinterna=(20,000 Ω/V)(0.5V)=10kΩ

b) Rinterna=(20,000 Ω/V)(1V)=20kΩ

c) Rinterna=(20,000 Ω/V)(5V)=100kΩ

d) Rinterna=(20,000 Ω/V)(50V)=1MΩ

e) Rinterna=(20,000 Ω/V)(100V)=2MΩ

f) Rinterna=(20,000 Ω/V)(100V)=20MΩ

38.Repita el problema 37 si se utiliza el voltímetro para medir voltaje entre los extremos de R4 en el circuito de la figura 7-62(b).

![image](https://user-images.githubusercontent.com/105823435/176979749-2eabca4c-c8cd-437e-9813-847ece3c0dcd.png)

V_R4=3V*(R_2 ‖R_3 ‖R_4)/(R_4+R_1 ‖R_2 ‖R_3 )

V_R4=3V*99.4Ω/779.4Ω=0.383V (actual)

a)Se utiliza 0,5V para medir 0,383V.
  
b)Rinterna=(20,000 Ω/V)(0.5V)=10kΩ
  
99.4Ω ‖ 10kΩ=98.4Ω

VR4=3V*98.4Ω/778.4Ω=0.379V

c)0.383V-0.379V=0.004V

SECCIÓN 7–5 Redes en escalera 

40.Determine la resistencia total y el voltaje en los nodos A, B y C de la red en escalera mostrada en la figura 7-78. 

![image](https://user-images.githubusercontent.com/105823435/176979792-85b564cb-b565-412a-afd4-2997baedd21b.png)

RT=6.66kΩ

VA=1.06kΩ/6.66kΩ*18V=2.86V

VB=1.05kΩ/2.05kΩ*2.86V=1.47V

VC=1kΩ/2kΩ*1.47V=735mV

42.En la figura 7-79, ¿cuál es el voltaje entre los extremos de cada resistor con 10 V entre A y B? 

![image](https://user-images.githubusercontent.com/105823435/176979944-a3cc5fed-c457-49e0-a419-02d0e7266600.png)

V1=IT*R1=(16.1mA)(100Ω)=1.51V

V_2=I2*R2=(8.27mA)(820Ω)=6.78V

V3=I3*R3=(7.84mA)(220Ω)=1.73V

V4=I4*R4=(4.06mA)(820Ω)=3.33V

V5=I5*R5=(3.78mA)(100Ω)=0.37V

V6=I6*R6=(3.78mA)(680Ω)=2.57V

V7=I7*R7=(3.78mA)(100Ω)=0.37V

V8=I8*R8=(7.84mA)(220Ω)=1.73V

V9=I9*R9=(16.1mA)(100Ω)=1.61V

44.Determine VSALIDA para la red R/2R en escalera mostrada en la figura 7-81 para las siguientes condiciones:

![image](https://user-images.githubusercontent.com/105823435/176980034-85581b4d-77a8-4038-ad12-497ef11f6f6e.png)

a)Interruptor SW2 conectado a 12 V y los demás conectados a tierra 

Vsalida = V/8 = 12V/2 = 1.5V

b)Interruptor SW1 conectado a 12 V y los demás conectados a tierra.

Vsalida = V/16 = 12V/16 = 0.75V

SECCIÓN 7–6 El puente Wheatstone 

46.Se conecta un resistor de valor desconocido a un circuito puente Wheatstone. Los parámetros del puente en equilibrio se establecen como sigue: RV  18 kΩ y R2/R4 = 0.02. ¿Cuál es RX? 

Rx = RV*R2/R4

Rx = (18kΩ)*(0.052) = 360Ω

48.Determine el voltaje de salida para el puente desequilibrado mostrado en la figura 7-83 a una temperatura de 60o C. La característica de resistencia según la temperatura del termistor se muestra en la figura 7-60. 

![image](https://user-images.githubusercontent.com/105823435/176980053-caf45b36-80e9-498f-8c19-5f6803549fa1.png)

At 60 grados centígrados = 5kΩ

Vizq = (R3/R1+R3) = (27kΩ/32kΩ) = 7.59V

Vder = (R4/R2+R4) = (27kΩ/54kΩ) = 4.50V

Vafu = Vizq - Vder = 7.59V - 4.50V = 3.09V

SECCIÓN 7–7 Localización de fallas 

50.¿Son correctas las lecturas del medidor mostrado en la figura 7-85? 

![image](https://user-images.githubusercontent.com/105823435/176980062-14234aac-6ff1-423d-bccf-18124c3600b0.png)

RBG=((10kΩ+47kΩ)(100kΩ))/(10kΩ+47kΩ+100kΩ)=((57kΩ)(100kΩ))/(57kΩ+100kΩ)=5700MΩ/157kΩ=36.6kΩ

RAG=33kΩ+R_BG=33kΩ+36.3kΩ=69.3kΩ

RT=27kΩ+R_AG=27kΩ+69.3kΩ=96.3kΩ

VAG=(RAG/RT) VS=(69.3kΩ/96.3kΩ)(18V)=12.95V

VCG=(47kΩ/57kΩ) VBG=(0.8)(6.79V)=5.6V

VAC=VAG-VCG=12.95V-5.6V=7.35V

Las lecturas tomadas son correctas.

52.Vea los medidores ilustrados en la figura 7-87 y determine si hay una falla en el circuito. Si la hay, identifíquela. 

![image](https://user-images.githubusercontent.com/105823435/176980100-fdf98342-546d-4c05-91ac-0bc4b8c121c6.png)

VA=((12kΩ||12kΩ)/((12kΩ|├|12kΩ)+10kΩ))*VS

VA=(((12kΩ)(12kΩ)/(12kΩ+12kΩ))/(((12kΩ)(12kΩ)/(12kΩ+12kΩ))+10kΩ))*(150V)

VA=((144kΩ/24kΩ)/((144kΩ/24kΩ)+10kΩ))(150V)

VA=(6kΩ/(6kΩ+10kΩ))(150V)=(6kΩ/16kΩ)(150V)

VA=(0.38)(150V)=56.25V

La medida de 81.8V es incorrecta y la falla puede encontrarte entre uno de los resistores de 12Ω.

54.Si en la figura 7-89 R2 se abre, ¿qué voltajes se leerán en los puntos A, B y C?

![image](https://user-images.githubusercontent.com/105823435/176980129-ea65eb36-c9c4-46ea-bf06-c1d9d7fe00c2.png)

VA = 15V

VB = 0V

VC = 0V 

SECCIÓN 8–3 Conversiones de fuente 

2.Convierta las fuentes de voltaje prácticas de la figura 8-67 en fuentes de corriente equivalentes.

![image](https://user-images.githubusercontent.com/105823435/176980143-7442890b-f9d7-400e-b217-d287f01a84c3.png)

a)Is = 5Kv/100Ω = 50A

b)Is = 12V/2.2Ω = 5.45A

4.Trace los circuitos equivalentes de fuentes de voltaje y corriente para la batería tipo D del problema 3. 

![image](https://user-images.githubusercontent.com/105823435/176980150-4dd9813f-fd13-4fd9-bd3f-f8092cdbe1fa.png)

Rs = 1.6V/8A = 0.2 Ω

6.Convierta las fuentes de corriente prácticas de la figura 8-68 en fuentes de voltaje equivalentes.

![image](https://user-images.githubusercontent.com/105823435/176980159-e7a5ceb4-4032-406a-b25e-1f2dbec042c6.png)

a)Vs = (10mA)*(4.7kΩ) = 47V

b)Vs = (0.1A)*(2.7kΩ) = 27V

SECCIÓN 8–4 El teorema de superposición 

8.Use el teorema de superposición para determinar la corriente a través, y el voltaje entre, los extremos de la rama R2 de la figura 8-69.

![image](https://user-images.githubusercontent.com/105823435/176980175-d807a2d3-40c6-408b-813d-f23576139a26.png)

Para 2V

R_T=1.955 kΩ y I_T=1.02mA

I2=(1.69kΩ/(1.69kΩ+2.2kΩ))(1.02mA)

I2=(0.4)(1.02mA)=0.443mA=443µA

Para 3V

RT=1.955 kΩ y I_T=1.53mA

Izq=(2.2kΩ/(1.69kΩ+2.2kΩ))(1.53mA) 

Iizq=(0.6)(1.02mA)=0.865mA=865µA 

I2=(1kΩ/(1kΩ+2.2kΩ))(865µA)    

I2=(0.3)(1.02µA)=0.443mA=257µA
 
Corriente T en R2

R2=443µA+257µA=713µA

10.Con el teorema de superposición, determine la corriente de carga en cada uno de los circuitos mostrados en la figura 8-71.

![image](https://user-images.githubusercontent.com/105823435/176980224-50b49236-ad21-4705-9c11-5013e4690dcd.png)

a) Para 1

IL=(2.2kΩ/(3.9kΩ+2.2kΩ))(1A)   

IL=(0.361)(1A)=0.361A=361mA
 
Para 2A con 1A abierto

IL=0A

Corriente T en IL

IL=361mA+0A=361mA

b) Para 40V con 60V cerrado

I_L=0A

Para 0.5A con 60v cerrado

I_L=0A

Para 60V

VL=(1.5kΩ/(0.56kΩ+1.5kΩ))(60V)    

VL=(0.73)(60V)=43.7V

IL=VL/(RL)   

IL=43.7V/1.5kΩ=29.1mA
 
Corriente T en IL

IL=29.1mA+0A+0A=29.1mA

12.Repita el problema 11 si R2 es de 10 kΩ.

![image](https://user-images.githubusercontent.com/105823435/176980276-aaa8a7ed-31b0-49d6-9ba8-5c7922d401b5.png)

Vref(max) = (R2+R3/R1+R2+R3)*30V-15V 

Vref(max) = (16.8kΩ /21.5kΩ)* 30V-15V = 5.44V

Vref(min) = (R3/R1+R2+R3)*30V-15V 

Vref(min) = (6.8kΩ/21.5kΩ)* 30V-15V = -5.51

14.Los interruptores mostrados en la figura 8-74 se cierran en secuencia, SW1 primero. Determine la corriente a través de R4 después del cierre de cada interruptor.

![image](https://user-images.githubusercontent.com/105823435/176980296-39e307fd-d6b3-4ef3-bd9d-a38ff1cb0e3a.png)

IL = 12V/5.6kΩ+18kΩ = 508 mA

RT = R1+R2+1/(1/RL) = 5.6kΩ+8.2kΩ+1/(1/8.2kΩ) = 11.2kΩ

IT = 12V/11.2kΩ = 1.07mA

IL2 = (8.2kΩ/26.2kΩ)*1.07mA = 335µA

SECCIÓN 8–5 Teorema de Thevenin 

16.Para cada uno de los circuitos de la figura 8-76, determine el equivalente de Thevenin como se ve desde las terminales A y B.

![image](https://user-images.githubusercontent.com/105823435/176980316-b2170cb4-05c9-430c-8ccc-3cd88df78c68.png)

![image](https://user-images.githubusercontent.com/105823435/176980319-db5a6468-cec8-4296-87a7-3327ced14ee5.png)

18.Con el teorema de Thevenin, determine el voltaje entre los extremos de R4 en la figura 8-78.

![image](https://user-images.githubusercontent.com/105823435/176980331-fd10bb4a-eb6f-4bbd-8ee8-801f19fbd574.png)

![image](https://user-images.githubusercontent.com/105823435/176980335-c49103b2-0060-464d-8841-afd000ea5e89.png)

VTh =(2.65kΩ/5.6kΩ+2.65kΩ)*50v = 16.1V

V4 = (R4/RTh+R4)* VTh 

V4 = (10kΩ/11.8kΩ)*16.1V = 13.6V

20.Determine la corriente que se dirige al punto A cuando R8 es de 1.0 kΩ, 5 kΩ, y 10 kΩ en la figura 8-80.

![image](https://user-images.githubusercontent.com/105823435/176980347-cc099214-2fe2-4d5d-a61e-4594569e9e0d.png)

0=(va-vd)/1k+va/1.2k+(va-ve)/8.2k

0=va*(593/491000)+vd*(-1/1k)+ve (-1/8,2k)

Va(1,06)=vd*(1/1k)

d=va (53/50)

0=vd*((Vd-Vc)/4,7k)+((Vd-Va)/1k)+(Vd/10k)

vd*(617/470k)=vc (1/4,7k)+Va(1/4.7k)+(1/1k)

vd=va(1,07m)=0.81va

0=((Ve-Va)/8.2k)+(Ve/R4)

ve (1/(8.2k+1k))=va (1/8.2k)=Va(46/41)

0=((Vb-Vc)/6.8k)+(Vb/9.1k)+((Vb+Vd)/10k)

0=Vc(357u)-va (1/8.2k)

Vc=va (25/73)

48=((Vc-Vb)/6.8k)+Vc+((Vc+Vd)/4.7k)

48=(63943/63920)+Vb(-1/6.2k)+Vd(-1/4.7k)

48=Va(0.34)+Va(-1/6.2k)+Va(-81/470000)

48=Va(0.34)

48/3.4=Va

14.1=Va

15.83=Ve

I4=(15.83/1k)=15.83mA

I4=(15.83/5k)=3.1mA

I4=(15.83/10k)=1.58mA

22.Determine el equivalente de Thevenin del circuito mostrado en la figura 8-82 visto desde las terminales A y B.

![image](https://user-images.githubusercontent.com/105823435/176980400-475c1b18-49e3-461d-9602-25abfc84e389.png)

vTH=vA-vB=(R2/(R1+R2 )) vs-(R4/(R3+R4 ))*vs

vTH=(12k/(10k+12k))⋅10-(35k/(15k+35k))⋅10

VTH=5.45-7

VTH=-1.54v

RTH=├ (R_1+R_2 )┤||(R3+R7 )

RTH=(10k+12k)||(15k+35k)

RTH=15.27k

24.Con el teorema de Norton, determine la corriente que circula a través del resistor de carga RL en la figura 8-77. 

![image](https://user-images.githubusercontent.com/105823435/176980449-f5332c79-5358-409b-b848-c7169ef7dfa4.png)

0=(va-vb)/10k+(va-vb)/5.6k

va (53/140k)-vb*(1/10k)

va=32/10k

0=(vb-va)/10k+vb/5.6k

vb (53/140k)-va*(1/10k)=0

va=9.08v

vb=2.4v

I_n=2.4/10k

In=240μA

Rn=10k+(10k||5.6k)+(10k||5.6k)

Rn=17.17k

IL=128.1μA

26.Con el teorema de Norton, determine la corriente que circula a través de R1 en la figura 8-80 cuando R8 = 8 kΩ. 

![image](https://user-images.githubusercontent.com/105823435/176980474-b605a0af-5564-485f-8f9e-757dbfd2575d.png)

0=(v_a⋅v_d)/1k+v_a/12k+(v_a⋅v_e)/8.2k

0=v_a (593/492k)+v_d (-1/1k)+v_e (-1/8.2k)

Va (1.06mv)=V_d (1/1k)

Vd=Va (53/50)

0=(vd-vc)/4.7k+(vd-va)/1k+vd/10k

vd (617/470k)=vc*(1/4.7k)+va*(1/1k)

Vd=Va (1.07mv)

Vd=0.81Va

0=(ve-va)/8.2k+ve/R4 

Ve (1/(8.2k+1k))=V_a (1/8.2k)

ve=va (46/41)

0=(vb-vc)/6.8k+v_b/9.1k+(v_b-v_d)/10k

0=vc (357μ)+v_a (-1/8.2k)

vc=va*(25/73)

48=(vc-vb)/6.8k+vc+(vc-vd)/4.7k

48=vc (63943/63920)+vb*(-1/6.2k)+v_d (-1/4.7k)

48=Va (0.34)+Va*(-1/6.2k)+Vd*(-81/470k)

48=Va (3.4)

va=14.1v

Ve=15.83

I1=11.2/9.1k

I1=1.23mA

28.En la figura 8-83, reduzca el circuito entre las terminales A y B a su equivalente Norton.

![image](https://user-images.githubusercontent.com/105823435/176980532-aff4e65e-19e5-49ed-a54b-bbcc08cf9758.png)

RN=R4 |(|(R3+(R2 ||R1 ))=10kΩ|)|(15kΩ+(8.2kΩ||22kΩ))

RN=10kΩ|(15kΩ+(8.2kΩ)(22kΩ)/(8.2kΩ+22kΩ))=10kΩ|(15kΩ+180.4kΩ/30.2kΩ)

RN=10kΩǁ(15kΩ+5.97kΩ)=10kΩǁ20.97kΩ

RN=(10kΩ)(20.97kΩ)/(10kΩ+20.97kΩ)=209.7kΩ/30.97kΩ=6.77kΩ

RT=(R2 ǁR3 )+R1=(8.2kΩǁ15kΩ)+22kΩ=(8.2kΩ)(15kΩ)/(8.2kΩ+15kΩ)+22kΩ

RT=123kΩ/23.2kΩ+22kΩ=5.3kΩ+22kΩ=27.3kΩ

IT=12v/27.3kΩ=0.440mA=440μA

IN1=(8.2kΩ/23.3kΩ)(440μA)=(0.35)(440μA)=156μA

I(N2 )=(15kΩ/20.97kΩ)(10mA)=(0.715)(10mA)=7.15mA

IN=I_N1+I*(N2)=0.156mA+7.15mA=7.31mA

SECCIÓN 8–7 Teorema de transferencia de potencia máxima 

30.En cada circuito mostrado en la figura 8-85, se tiene que transferir potencia máxima a la carga RL. Determine el valor apropiado de RL en cada caso.

![image](https://user-images.githubusercontent.com/105823435/176980567-4cd7f392-9c47-4e63-96c1-809dd962555f.png)

a)RL = Rs = 12Ω

b)RL = Rs = 8.2kΩ 

c)RL = Rs = 4.7Ω + (1Ω*2Ω) = 4.7Ω + (1Ω)*(2Ω)/1Ω+2Ω = 5.37Ω

d)RL = Rs =  47 Ω +680 Ω = 727 Ω

32.¿Cuánta potencia se suministra a la carga cuando RL es un 10% más alta que su valor para transferencia de potencia máxima en el circuito de la figura 8-86?

![image](https://user-images.githubusercontent.com/105823435/176980583-8a41fd98-5c0d-47af-b190-546c030bf5ae.png)

RL = Rs = RTh = 8.2 Ω+2.94 Ω = 11.1 Ω

RLH = R2+0.1RL = 11.1 Ω+0.1 Ω*11.1 Ω = 12.21 Ω

Para 1.5V

VTH=(15Ωǁ16.4Ω/(4.7Ω+(15Ωǁ16.4Ω) ))(1.5v)=(((15Ω)(16.4Ω)/(15Ω+16.4Ω))/(4.7Ω+(15Ω)(16.4Ω)/(15Ω+lb⋅4Ω)))(1.5v)

vTH=((((15Ω)(16.4Ω)/(15Ω+16.4Ω))/(4.7Ω+(15Ω)(16.4Ω) ))/(15Ω+16.4Ω))(1.5v)=((246Ω/31.4Ω)/(4.7Ω+246Ω/31.4Ω))(1.5v)

VTH=(7.83Ω/(4.7Ω+7.83Ω))(1.5v)=(7.83Ω/12.53Ω)(1.5v)=(0.63)(1.5v)=0.936V=936mV

IL=vTH/(RTH+RLH )=936mA/(11.1Ω+12.21Ω)=936mv/23.31Ω=40mA

Para 1 mA

I15Ω=(4.7Ωǁ16.4Ω/(15Ω+14.7Ωǁ16.4Ω))(1mA)=(((4.7Ω)(16.4Ω)/(4.7Ω+16.4Ω))/(15Ω+(4.7Ω)(16.4Ω)/(4.7Ω+16.4Ω)))(1mA)

I15Ω=((77.08Ω/21.1Ω)/(4.7Ω†77.08Ω/21.1Ω))(1mA)=(3.65Ω/(4.7Ω+3.65Ω))(1mA)=(3.65Ω/8.35Ω)(ln⁡A )

I15Ω=(0.196)(1mA)=0.196mA=196μA

VTH=(196μA)(15Ω)=2940μV=2.94mV

IL=vTH/(R(TH)⋅RLH )=2.94mV/(11.1Ω+12.21Ω)=2.94mV/23.31Ω=0.126mA

ILH=40mA+0.126mA=40.126mA

PL=ILT^2⋅RLH=(40.126mA)^2 (12.21Ω)=19.7mW

SECCIÓN 8–8 Conversiones delta a Y (Δ a Y) y Y a Δ 

34.En la figura 8-88, convierta cada red delta en una red Y.

![image](https://user-images.githubusercontent.com/105823435/176980667-f56a66b8-591a-445d-856c-d0ef761c4914.png)

a) 
Rx=(R_C⋅R_A)/(R_A+R_B+R_C )

Rx=(1.0MΩ⋅0.56MΩ)/(0.56MΩ+1.5MΩ+1.0MΩ)

Rx=0.5MΩ/3.06MΩ

Rx=0.16MΩ

Ry=(RC⋅*RB)/(RA+RB+RC)

Ry=(1.0MΩ⋅1.5MΩ)/(0.56MΩ+1.5MΩ+1.0MΩ)

RY=1.5MΩ/3.06MΩ

Ry=0.49MΩ

Rz=(RA⋅*RB)/(RA+RB+RC )

Rz=(0.56MΩ⋅1.5MΩ)/(0.56MΩ+1.5MΩ+1.0MΩ)

Rz=0.84MΩ/3.06MΩ

R_z=0,27MΩ

b)
Rx=(RA⋅*RB)/(RA+R*B+RC )

Rx=(1.0⋅2.7)/(1.0+2.7+2.2)

Rx=2.7Ω/5.9Ω

Rx=0.46Ω

Ry=(RA*⋅RB)/(RA+RB+RC )

Ry=(1.0*⋅2.2)/(1.0+2.7+2.2)

Ry=2.2/5.9

Ry=0.37Ω

Rz=(RC*⋅RB)/(RA+RB+RC)

Rz=(2.2*2.7)/(1.0+2.7+2.2)

Rz=5.94/5.9

Rz=1.0Ω

36.Determine todas las corrientes que circulan en el circuito de la figura 8-90.

![image](https://user-images.githubusercontent.com/105823435/176980864-85d84e84-2ac1-4b88-bf58-cfacfe1a76fb.png)

Ley de corrientes de Kirchhoff 

I1+I3+I4=0

v(B-V1 )/R1 +vB/R3 +vB/R4 =0

(vB-136)/10+vB/22+vB/12=0

(66(vB-136)+30vB+55vB)/660=0

66vB-8976+30vB+55vB=0

151vB-8976=0

151VB=8976

vB=59,44v

I2+I3^'+I5=0

(vC-v1)/R2 +vC/R3 +vC/R5 =0

(vC-136)/39+vC/22+vC/9.1=0

vc/39-136/39+vc/22+vc/9.1 =0

Vc(1/39+1/22+1/9,1)-3,49=0

vC(0,18)=3,49

vC=3,49/0,18

v_C=19,38v

I1=(v_B-v_1)/R_1 =59,44/10=-7,65A

I2=vB/R3=59,44/22=2,70A

I3=VB/R4 =59.44/12=4.95A

I4=(vc-v1)/R2 =(19.38-136)/39=-2.99

I3^'=vc/22=19.38/22=0.88

I3^'=vc/22=19.38/22=0.88

I5=vc/Rs =19.38/9.1=2.12

I3+I3´=4.95+0.88

I3=5.83

Sumatoria de I entran = Sumatoria de I salen

7.65+2.99=5.83+2,70+2.12

10.646=10.646A

4.-Video



5.-Conclusiones 

Se analizó y aplico los métodos expuestos en los capítulos siete y ocho.

Se determino las relaciones serie-paralelo de los circuitos resistivos.

Se identificó el teorema de superposición, de Thevenin y el de Norton.

6.-Bibliografía

Alarcon, L. (4 de Septiembre de 2017). lafisicayquimica. Obtenido de lafisicayquimica: https://lafisicayquimica.com/que-son-los-circuitos-en-serie-y-en-paralelo/
Torres, H. (15 de Julio de 2018). hetpro-store. Obtenido de hetpro-store: https://hetpro-store.com/TUTORIALES/divisor-de-voltaje/#:~:text=Un%20divisor%20de%20voltaje%2C%20es,resistencias%20involucradas%20en%20el%20divisor.

