# ServoAmplifier-LTSpice
Simulación en LTSpice de un servo amplificador para alimentación y control de motores brushless de distinta potencia

<img src="https://github.com/aglora/ServoAmplifier-LTSpice/blob/main/imgs/1.png" width="700" />

# RESUMEN
El control de motores brushless (sin escobillas) ha ganado importancia en múltiples aplicaciones en los últimos años. En el área de la robótica juegan un papel fundamental en multitud de sistemas. En concreto son muy usados en robots aéreos como los conocidos drones y en alternativas en auge como los ornitópteros.

Además, existen aplicaciones que requieren de mayor potencia tales como transporte o industria donde este tipo de motores son usados. Esto es debido a que ofrecen un rendimiento superior en términos de eficiencia, velocidad, torque y vida útil en comparación con los motores de corriente continua convencionales.

Sin embargo, para aprovechar al máximo su potencial, es esencial contar con sistemas de control precisos y eficientes. En este contexto, los servo amplificadores desempeñan un papel fundamental.

Los servo amplificadores son dispositivos electrónicos diseñados para controlar y gestionar el funcionamiento de motores brushless en aplicaciones que requieren un alto grado de precisión y respuesta dinámica.

En el presente trabajo se implementará este tipo de sistema en LTSpice, siguiendo una línea de trabajo progresiva de más ideal a más realista.
Comenzaremos desarrollando el circuito mediante interruptores ideales con modelos de motor básicos, para pasar posteriormente a su sustitución por MOSFETs de potencia para uso en motores relativamente pequeños. Tras esto, usaremos
dispositivos de mayor potencia como son los IGBTs con vistas a aplicaciones que requieran de motores con mayor demanda de consumo.

Llevaremos a cabo distintos análisis de funcionamiento de los dispositivos y sistemas completos para ofrecer comparativas entre ellos. 
Además, introduciremos el uso de modelos de motor externos más realistas.

<img src="https://github.com/aglora/ServoAmplifier-LTSpice/blob/main/imgs/2.png" width="700" />
<img src="https://github.com/aglora/ServoAmplifier-LTSpice/blob/main/imgs/3.png" width="700" />
<img src="https://github.com/aglora/ServoAmplifier-LTSpice/blob/main/imgs/4.png" width="700" />
<img src="https://github.com/aglora/ServoAmplifier-LTSpice/blob/main/imgs/5.png" width="700" />
<img src="https://github.com/aglora/ServoAmplifier-LTSpice/blob/main/imgs/6.png" width="700" />
<img src="https://github.com/aglora/ServoAmplifier-LTSpice/blob/main/imgs/7.png" width="700" />
<img src="https://github.com/aglora/ServoAmplifier-LTSpice/blob/main/imgs/8.png" width="700" />
<img src="https://github.com/aglora/ServoAmplifier-LTSpice/blob/main/imgs/9.png" width="700" />
<img src="https://github.com/aglora/ServoAmplifier-LTSpice/blob/main/imgs/10.png" width="700" />
