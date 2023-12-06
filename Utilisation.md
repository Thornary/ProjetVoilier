## Récapitulatif de l'utilisation des pins de la nucléo


| Pin utilisée | Element | Description |
|---|---|---|
|B5|Moteur| Sens de rotation du moteur avec le GPIOB 5|
|B0|Moteur| PWM pour la rotation du plateau|
|B6|Servo| PWM pour le bordage des voiles|
|A4|Girouette| Interruption externe du Zero (External Interrupt)|
|A0| Girouette| Signal de la girouette TI1|
|A1| Girouette| Signal de la girouette TI2|
|B1| Batterie| Voie 9 de l'ADC1 --> Récupération de la tension|
|PA9| Xbee|Emission USART1|
|PA10| Xbee|Reception USART1|
|A5|Roulis|SPI SCK|
|A6|Roulis|SPI MISO|
|A7|Roulis|SPI MOSI|
|B6|Roulis|SPI CS|


## Récapitulatif de l'utilisation des éléments internes


| Element | Permanent | Description |
|---|---|---|
|ADC1| Oui | Utilisation pour la tension de la batterie|
|TIM2| Oui |Utilisation pour le calcul de l'angle de la girouette|
|TIM4| Non | Utilisation pour la PWM du bordage des voiles|
|USART1| Oui | Utilisation pour Xbee|
