# INFORME-8

</div>

# UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE

AUTORES

MEJIA CESAR

MONTALVO MARTIN

TOAPANTA ANABEL

NRC
  
5407

INGENIERO

Ing. Darwin Omar Alulema Flores

# PRÁCTICA No. 8 CARACTERÍSTICAS DE LA ONDA SENOIDAL
  
</div>

**1.OBJETIVOS**

Objetivo General

*Determinar experimentalmente las características de señales senoidales y su comportamiento.

Objetivos Específicos


**2.MARCO TEÓRICO**

![](https://github.com/Anabeltoapanta/INFORME-LABORATORIO8/blob/main/MARCO%20TEORICO%20LABORATORIO%208-convertido_page-0001.jpg)  
 

**3.EXPLICACIÓN DEL PROCEDIMIENTO**

<div align="center">
     
|**CANTIDAD**|       **MATERIAL O EQUIPO**      |
|    :---:   |              :---:               | 
|      1     |       Generador de Funciones     |
|      1     |           Osciloscopio           |
|      1     |            Multímetro            |
|      1     |         Resistor de 1 kΩ         |
|      1     |        Resistor de 2.2 kΩ        |
|      1     |            Protoboard            |
  
</div>

A continuación, procedemos a implementar el circuito en el simulador de DECACLAB con la ayuda del diagrama del circuito.

![image](https://user-images.githubusercontent.com/85134094/132283743-1a993907-65b8-4672-8140-dea81fba1947.png)

Ajustamos el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5 Khz.

![image](https://user-images.githubusercontent.com/85134094/132283756-cc92fa60-7eea-49b7-9685-eb118b4d7230.png)

Conectamos el osciloscopio al resistor de cara RL y observamos la señal que aparece en el osciloscopio.

![image](https://user-images.githubusercontent.com/85134094/132283777-6d4d7d5e-c3db-46b4-85e4-c1eeac8584d7.png)

**4.PREGUNTAS A INTERROGANTES**

A continuacion procedemos a responder las interrogantes con la ayuda del simulador.

**4.5.4. Responda las siguientes preguntas:**
¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?

Tiene aproximadamente 3 divisiones por cuadro

¿En qué valor está posicionada la perilla VOLTS/DIV?

En 2,25 Volts por cada división

¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida? 

Un ciclo completo abarca 4 divisiones por cuadro 

¿En qué valor está posicionada la perilla TIME/DIV?

En 0,1m Time/div

**4.5.5.¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?**

Para la amplitud de voltaje necesitamos medir cuantas divisiones tiene la amplitud máxima, la cual tiene 3 divisiones y como sabemos que cada división tiene 2,25 Voltios tenemos entonces:

![image](https://user-images.githubusercontent.com/85134094/132284064-bcc06f85-87e9-4d05-ba4c-de7ddd482f66.png)

Así mismo para el periodo tenemos que medir cuantas divisiones tiene un ciclo entero en este caso tiene 4 divisiones y como sabemos que cada división tiene 0,1ms tenemos entonces:

![image](https://user-images.githubusercontent.com/85134094/132284040-9a2ac751-3293-469e-bc9e-ef8eaec274c2.png)

**4.5.6. Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.**

Para la Frecuencia tenemos:

![image](https://user-images.githubusercontent.com/85134094/132284125-748a544a-0d50-4575-af63-eedc3fe1358e.png)

Para la Frecuencia Angular tenemos:

![image](https://user-images.githubusercontent.com/85134094/132284137-61aa1054-f584-4e98-9157-fd73825ad996.png)

**4.5.7. Con el multímetro digital mida el voltaje de salida en RL: 

![image](https://user-images.githubusercontent.com/85134094/132284158-de516378-b413-46ef-87e3-59ac6ad37517.png)

**4.5.8. Compare el voltaje medido en el punto 7.5.5. y el obtenido en el punto 7.5.7.**

¿Coinciden? 

No coinciden

![image](https://user-images.githubusercontent.com/85134094/132284182-fab50e89-cae2-4150-9f91-862ce0074db2.png)

¿Por qué?

No coinciden por que el multímetro mide el voltaje rms a través de la resistencia mientras que el osciloscopio mide el Voltaje pico o voltaje pico pico depende de cómo observemos la onda.

A continuación, demostramos como se calcula el voltaje pico y el voltaje rms para que ambos valores coincidan:

![image](https://user-images.githubusercontent.com/85134094/132284245-473abd91-81e4-44f4-b2c7-066354424e19.png)

Que se asemeja mucho al voltaje medido.

**5.VIDEO**

https://youtu.be/3ckObB7_Yo0

**6.CONCLUSIONES**

* Para la utilizacion del osciloscopio se debe tomar en cuenta como funciona cada perilla, estas miden y configuran la onda para que se pudea observar todo el ciclo y asi poder calcular los diferentes datos mostrados en la pantalla

* Los voltajes medidos en el osciloscopio no van a ser iguales a los voltajes que mida el multimetro debido a que el multimetro mide los voltajes rms y el osciloscopio mide los voltajes pico o voltajes pico a pico de la onda esto se puede asemejar utilizando una formula especifica para calcular el voltaje rms.

**7.BIBLIOGRAFÍA**

