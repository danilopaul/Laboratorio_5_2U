# Laboratorio_5_2U

                                                  Universidad de las Fuerzas Armadas - ESPE
                                                   Fundamentos de Circuitos Electróinicos
        Integrantes:
        - Cholca Paul
        - Sandal Andrés
        - Vasquez Lady
 
1.OBJETIVOS

1.1 Objetivo General

Determinar el concepto del teorema de Thevenin, por medio del planteamiento de sus características en relación a la resistencia y tensión resultante al aplicar este teorema, con el fin de simplificar el análisis y resolución de un circuito


1.2 Objetivo  Especificos

- Establecer el proceso de análisis y/o resolución que abarca el teorema de Thevenin para hallar la tensión.

- Establecer el proceso de análisis y/o resolución que abarca el teorema de Thevenin para hallar la resistencia.

- Analizar el circuito resultante después de aplicar el teorema de Thevenin, y como este puede llegar a facilitar la resolución de un circuito.

2.MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/105687213/177677385-88625e4f-ea07-43b1-b410-ee8f07080cf7.png)

3.REQUISITOS PREVIOS


![image](https://user-images.githubusercontent.com/105687375/177696876-aa87a40b-00f2-47b7-b6c2-952bb05d6cf9.png)

![image](https://user-images.githubusercontent.com/105687375/177696911-fea2d4c6-5051-4530-ad8c-8c8b060fbdc4.png)

![image](https://user-images.githubusercontent.com/105687375/177696965-09805bf1-6e01-4829-8bfa-e1ffe74ca799.png)

![image](https://user-images.githubusercontent.com/105687375/177696985-cd3ef2fe-b47b-4cd0-a7a0-a4c62e93d3e4.png)

![image](https://user-images.githubusercontent.com/105687375/177697014-d14edd79-b935-4fe2-87dc-33706094db51.png)

Utilizando un potenciomentro 

![image](https://user-images.githubusercontent.com/105687375/177711070-00826ed2-448e-49d5-9e08-0dc82aa8a71a.png)

![image](https://user-images.githubusercontent.com/105687375/177711114-6538ae17-8f1a-425e-a756-91a9fc70f824.png)


4.MATERIALES Y EQUIPOS REQUERIDOS

![image](https://user-images.githubusercontent.com/105687213/177677519-8239d745-b2f8-425d-82f5-569636ba5072.png)

5.RESOLUCIÓN

Hacemos que R5 este en cortocircuito

![image](https://user-images.githubusercontent.com/105687213/177700606-86a7cbb9-a179-4c6c-ac4f-bfb39d796353.png)


Calculamos la RTH

R1||R2=(560*4700)/(560+4700)= 500.38 Ω

RT=(1/(1/500.38+1/330))+100 

RT=198.86+100 

RTH=298.86 Ω



Calculamos las corrientes por metodo de lazo

![image](https://user-images.githubusercontent.com/105687213/177700845-3a436d1a-4cf3-4dd6-83e5-c0f930257bea.png)


Lazo A

560IA+4700(IA-IB)=10 

560IA+4700IA-4700IB=10 

IA=(4700IB+10)/5260      (1)

Lazo B

330IB+4700(IB-IA)=2 

330IB+4700IB-4700IA=2    (2)

Remplazamos IA en la ecuación 2

5030IB-4700((4700IB+10)/5260  )=2 

830.39IB=10.94 

IB=0.0131 A 

IB=13.1 mA 

Remplazamos la IB en la ecuación (1)

IA=(4700(13.1)+10)/5260 

IA=11.70 mA 

Calculamos el VR3 mediante la ley de ohm

![image](https://user-images.githubusercontent.com/105687213/177701015-f9c3093e-1959-46a6-9836-8825ee175cd0.png)

VR3=R3*IB 

VR3=330*0.0131 

VTH=4.323 V

![image](https://user-images.githubusercontent.com/105687213/177701237-cca0dd1a-8390-4b45-88fc-c9c7cb715f62.png)

Calculamos VR5 y I5

![image](https://user-images.githubusercontent.com/105687213/177701373-45ce677b-2a61-47ab-9935-d66b46115574.png)

I=VTH/RTH

I=3.325 mA

VR5=(100/1298.86)(4.32)

VR5=3.325 V



- Tabla 5.1. Valores del Circuito Equivalente de Thévenin

![image](https://user-images.githubusercontent.com/105684550/177697622-4b8a73ed-760a-48df-8c73-f770a2a35dc0.png)

- Tabla 5.2. Comprobación del Teorema de Thévenin.

![image](https://user-images.githubusercontent.com/105684550/177697676-5a868844-8ada-4bad-8947-84ff02eabe6f.png)

6.VIDEO

https://youtu.be/JeJOKdRS7zw

7.CONCLUSIONES:

- En definitiva se logro apreciar que tras aplicar el teorema de Thevenin la resitencia resultante, también denominada Resistencia Thevenin, se obtendría posteriormente de reemplazar las fuentes de voltaje por circuitos cerrados, las fuentes de corriente por circuitos abiertos y finalmente la resistencia que se desea calcular se la cortocircuitaria para así obtener un nuevo circuito con solo resistencias de las cuales se obtendria la Resistencia Total.

- También se pudo observar que posteriormente de aplicar el teorema de Thevenin el voltaje resultante, también denominada Voltaje Thevenin, se obtendría tras cortocircuitar la resistencia que se desea calcular, y por medio de los métodos aprendidos (mallas, ramas y nodos) se resolvería el circuiton para obtener el voltaje.

- Se ha podido deducir que el Teorema de Thevenin es una herramiento de gran ayuda que permite simplificar o reducir un circuito amplio a uno más sencillo, compuesto por un Vontaje de Thevenin y una Resistencia de Thevenin, siendo específicos quedaría como resultado un circuito en serie.

8.BIBLIOGRAFÍA

Floyd, TL (2007). Principios de Circuitos Eléctricos. CDMX: Persona Educación.
