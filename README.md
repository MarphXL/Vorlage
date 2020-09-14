 
# CD74HC4067 - 16-Channel Analog/Digital Multiplexer/Demultiplexer

## Inhaltsverzeichnis
1. [x] [Inhaltsverzeichnis](#Inhaltsverzeichnis)
1. [x] [Beschreibung](#Beschreibung)
1. [x] [Technische Daten](#technische-daten)
  1. [x] [Datasheet](#datasheet)
1. [ ] Hardware
  1. [ ] EasyEDA
  1. [ ] Eagle
1. [ ] Software
1. [ ] 3D
1. [x] [Where to buy](#Where-to-buy)
1. [x] [Abbildungen](#Abbildungen)
1. [x] [Credits](#Credits)

## Beschreibung
This is a breakout board for the very handy 16-Channel Analog/Digital Multiplexer/Demultiplexer CD74HC4067. This chip is like a rotary switch - it internally routes the common pin (COM in the schematic, SIG on the board) to one of 16 channel pins (CHANxx). It works with both digital and analog signals (the voltage can't be higher than VCC), and the connections function in either direction. To control it, connect 4 digital outputs to the chip's address select pins (S0-S3), and send it the binary address of the channel you want (see the datasheet for details). This allows you to connect up to 16 sensors to your system using only 5 pins!
Since the mux/demux also works with digital signals, you can use it to pipe TTL-level serial data to or from multiple devices. For example, you could use it to connect the TX pins of 16 devices to one RX pin on your microcontroller. You can then select any one of those 16 devices to listen to. If you want two-way communications, you can add a second board to route your microcontroller's TX line to 16 device's RX lines. By using multiple boards, you can create similar arrangements for I2C, SPI, etc.
The internal switches are bidirectional, support voltages between ground and VCC, have low “on” resistance and low “off” leakage, and to prevent crosstalk, perform “break-before-make” switching. The board also breaks out the chip's “enable” pin, which when driven high, will completely disconnect the common pin (all switches “off”).
 
## Technische Daten
2V to 6V operation
“On” resistance: 70 Ohms @ 4.5V
6ns break-before-make @ 4.5V
Wide operating temperature range: -55C to 125C
Function: gathering all the way ADC 16 analog signals.
Use CD74HC4067 16-channel analog signal switch
Analog Input: C0-C15 16 channels
Analog output: DIG
Channel Control: S0-S3
CD74HC4067

## Datasheet
* [TI.com datasheet](https://www.ti.com/lit/ds/symlink/cd74hc4067.pdf)
* [snapshot](https://github.com/MarphXL/Vorlage/blob/master/cd74hc4067.pdf)

## Where to buy
~6 EUR for 10pcs: [AliExpress](https://www.aliexpress.com/item/32821800330.html)

## Abbildungen
![HP4067](https://raw.githubusercontent.com/MarphXL/Vorlage/master/HP4067_front.webp)
![HP4067](https://raw.githubusercontent.com/MarphXL/Vorlage/master/HP4067_back.webp)

## Credits
* :+1: [arduino](https://github.com/arduino)
* :+1: [adafruit](https://github.com/adafruit)
* :+1: [sparkfun](https://github.com/sparkfun)
* :+1: [Watterott](https://github.com/watterott) and @awatterott for great SW, HW and products
* :+1: [atom](https://github.com/atom) 
* :+1: @ikatyang for the [emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

# Vorlagen

#### Überschrift 4
##### Überschrift 5
###### Überschrift 6
Fettdruck **bold** 
Kursiv *italic* 

# Tabellen
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
   
# Blockquotes
As Kanye West said:

> We're living the future so
> the present is our past.

# Inline code
I think you should use an
`inline code` element here instead.

# Syntax highlighting
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

# Tabellen
First Header | Second Header
------------ | -------------
pushpin | :pushpin:
bulb | :bulb:
bomb | :bomb:
wastebasket | :wastebasket:
warning | :warning:
no_entry | :no_entry:
question | :question:
exclamation | :exclamation:
x | :x:
heavy_check_mark | :heavy_check_mark:
copyright | :copyright:
reg | :registered:
eingetragenes Warenzeichen | :tm:
lock | :lock:
key | :key:
gear | :gear:
eye_speech_bubble | :eye_speech_bubble:
thought_balloon | :thought_balloon:
speech_balloon | :speech_balloon:
vulcan_salute | :vulcan_salute:
ok_hand | :ok_hand:
thumbsup | :thumbsup:
thumbsdown | :thumbsdown:
point_right	| :point_right:	
fu | :fu:
Augen  | :eyes:
email | :email:
green_book | :green_book:
Verzeichnis  | :open_file_folder:
Kalender | :calendar:
Bier | :beer:
Home | :house:
Stoppuhr | :stopwatch:
Sanduhr | :hourglass_flowing_sand:
Hitze | :thermometer:
Bild | :art:
Sound | :loud_sound:
Mue | :mute:
Batterie | :battery:
Pfeil hoch | :arrow_up:
arrows_counterclockwise | :arrows_counterclockwise:
Soon | :soon:
twisted_rightwards_arrows | :twisted_rightwards_arrows:
Versus | :vs:
OK | :ok:
Neu | :new:
a | :a:
d | :d:
red_circle | :red_circle:
purple_square | :purple_square:
triangular_flag_on_post | :triangular_flag_on_post:
Atom | :atom:
