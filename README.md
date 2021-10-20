
# About
En este repositorio se expone la construcción de un robot.

El objetivo de este robot es implementan diversos algoritmos de:

+ Visión por Computadora
+ Robotica
+ Inteligencia artificial
+ GNU/Linux
+ Electrónica (ESP32,Arduino)


# Hardware

## Robot
En cuestion a la base del robot, se reutilizo un carrito
de control remoto, desmontando el carcase y 
haciendo uso de los motores, ruedas y base de este mismo.
<p align="center">
<img src="https://bn1303files.storage.live.com/y4m8oi9xlMJJVYcFKc0pAKiDHFXCi9shxnq9x2w84GIW2VJjYQwGV7n_ci2uY4FOEpEd8Z69GidC1svz0ZgNtPSDjwofM8z0dPghWUy5REeV3QWcdmG_sUcer8VB0yWtk4nmONg7Lc8h7NA5gAb2Zhol1BLrKoigCYnIaIKHVKI-y3-PVA1_KU3NzbJsD90pP00?width=256&height=192&cropmode=none" width="256" height="192" />
</p>
<p align="center">
Carrito de control remoto
</p>


Ademas se le instalo una plataforma de plastico al carrito
para poder adaptar otros componentes.

En la siguiente imagen se muestra el carrito modificado
<p align="center">
<img src="https://bn1303files.storage.live.com/y4mK1Ttk7agSXeIwAn8bG0puEQ5E1qL7cGFT5FeWWJrJIZKjhKSOSEhw8vWwru_xU3FlPuF_gocKFG0pLuTjrsne39l9g4LBB0tz-api5b106OGRfCYWxHdZhr4sF4eDdEW2YFrDHdrNblR6avk3cP3BSgkEEPgqfGQseYhf-N_bUsziuf07iXQSrfa_oukfd1f?width=256&height=256&cropmode=none" width="256" height="256" />
</p>
<p align="center">
a) Vista uno, b)Vista dos
</p>

## Fuente de poder

Para seleccionar la fuente de poder se considera los siguientes aspectos:
+ Energia para los motores
+ Energia para microcontrolador principal
+ Energia para los dos microcontroladores de visión estereo
+ Otros sensores

En el control de los motores se esta trabajando con el modulo L298N, este modulo permite controlar dos motores
en DC y ademas trabajar con entradas PWM para controlar la velocidad de los motores.

<p align="center">
<img src="https://bn1303files.storage.live.com/y4m41Rl7E4yngTNF5NI74Njvo8b5yK4QSx3YZXqa3oAxAvSVVXrMaGmjEn4fPbEfeRYQy3JvS2bJWohxLVacMhKtlpHTCUFgZnOFTkzd-myDeUIw7aKuXre8bQFtowS1Pwd1bblFoSoJc9tCUbDJ6YeBpOsBgFA9jwDBDjxNMABt0p-D-nbDVjLP0C09fj-mvaY?width=256&height=231&cropmode=none" width="256" height="231" />
</p>
<p align="center">
Modulo L298N
</p>


Para el microcontrolador principal se utilizara el ESP32 DEVKIT v1:
<p align="center">
<img src="https://bn1303files.storage.live.com/y4mWXdVxOMs5o_1PokCBFx6exu042EjAIR5gtV9Yl50UigxFOd_5YvLA0_y53gajzzm0BibWDz3HGPewOo5fG5OTx76OGTWmK3scNTT0Hht68ZUIshyuhf8ujoTeN_35Z0r_cowXXO324su1OJWWqQtHRIzclIm2yPHaKpRERRletfeq_RSOLVGvZNnbAFHXQy1?width=256&height=198&cropmode=none" width="256" height="198" />
</p>
<p align="center">
Esp 32 dev kit v1.0, a) Vista superior, b) Vista inferior
</p>


## Bateria

Para las baterias se reutilizaron las celdas de una bateria de laptop:
<p align="center">
<img src="https://bn1303files.storage.live.com/y4maXW9KKpFP_KXupHJMT0_boiF3wdqJYftFCR3hTmXWRerqlaegOn6d_dRhBoY3IREW8-h7LLr6PX2_nFABQJ3m2spIKhXdMsmepWlFzYLenvpcot6w70K51bcxl74WU2SzOlNkN9emsOgQDC96ogM7hZgrBVwILn3cAg_z0PVhoEe1hOJ-hURU-1HYfTk65sx?width=256&height=146&cropmode=none" width="256" height="146" />
</p>
<p align="center">
Baterias de 3 volts cada una
</p>

El robot debe tener la posibilidad de recargar estas celdas, por ello se ha invertido en el siguiente modulo de cargador de celdas:



# Desarrollador
+ Ing. Noé Vásquez Godínez
