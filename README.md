# SHARING SENSE 

_Este sentido te permite percibir el sonido y la música en tu piel mediante vibraciones._

## REQUISITOS

### `Software`
* IDE 

### `Hardware`
* Arduino Nano	* 1	Unidad.
* Micro			* 1 Unidad.
* WS2812		* 2 Unidades.
* Led RGB		* 1 Unidad.
* Motor			* 3 Unidades.
* Diodo			* 3 Uidades.
* 330 ohm		* 3 Unidades.
* 33 uF			* 1 Unidad.
* Power 5v		* 1 Unidad.

### `E/S`


|	Nano		|		POWER		|		Micro	|		WS2812		|		Motor		|	
|		----	|		----		|		----			|		----		|		----		|
|	PB4			|		GND			|		GND	-			|		GND	-		|		GND	-		|
|	PB8			|		VCC			|		5V	+			|		5V	+		|		5V	+		|
|	PB3	ADC3	|		x			|		OUT				|		x			|		x			|
|	PB1 PCNINT1	|		x			|		x				|		DATA		|DATA->FlyBack Diode|