# semestre
Proyecto reactor
Para este proyecto se utilizó el microcontrolador MKL25Z128VLK4 el cual provee NXP.
Los GPIOs son configurables.
El canal de ADC esta codificado para funcionar con el sensor LM35 o con termopar.
Para escoger que sensor de temperatura usar, dirigite a conversion_ADC.h y descomenta #define TERMOPAR.
El baudrate utilizado para la comunicacion serial es de 9600 bps.
