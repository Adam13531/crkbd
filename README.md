# Corne keyboard

The Corne keyboard is a split keyboard with 3x6 column staggered keys and 3 thumb keys,
based on [Helix](https://github.com/MakotoKurauchi/helix).
Crkbd stands for Corne Keyboard.

## Adam's updates

I wanted a very specific setup: a v3, 5-column choc keyboard. I forked this repo from https://github.com/daysgobye/crkbd/tree/choc-v3, so I got two of those things for free. I then modified this to chop off a column on both sides. I've ordered the PCBs, but I have no real experience with doing any of this, so I can't confirm that it'll work. I'll probably know in December, 2021, and hopefully I remember to update this then.

Note: I never touched the schematic file, just the PCB.

I derived a bill of materials based on [this reddit post](https://www.reddit.com/r/crkbd/comments/esv3i8/guide_corne_diy_kit/), [this GitHub page](https://github.com/ItsWaffIe/waffle_corne/wiki/Build-Log#parts), and [this great build guide](https://medwa.pl/docs/corne-lp-build-guide/#bom). Caveat: [I have no idea what I'm doing](https://knowyourmeme.com/memes/i-have-no-idea-what-im-doing). For a frame of reference, I ordered everything from AliExpress in October, 2021.

**Part**|**Quantity ordered**|**Cost (USD)**
:-----:|:-----:|:-----:
[Kailh 1.5u low-profile choc keycaps](https://www.aliexpress.com/item/33024722080.html)|30|$8.50
[Kailh 1u low-profile choc keycaps](https://www.aliexpress.com/item/33026798318.html)|60|$16.40
[Kailh low-profile choc red crystal](https://www.aliexpress.com/item/4001016150022.html)|70|$51.30
[Low-profile Kailh sockets](https://www.aliexpress.com/item/1005002695808124.html)|44|$4.40
[40-pin connector header pins](https://www.aliexpress.com/item/4001345538843.html)|5|$1.55
[40-pin connector header sockets](https://www.aliexpress.com/item/32847384633.html)|10|$1.80
[TRRS jack](https://www.aliexpress.com/item/33029465106.html)|10|$0.75
[Diodes](https://www.aliexpress.com/item/4000685043735.html)|100|$0.69
[Pro Micro microcontroller](https://www.aliexpress.com/item/32888212119.html)|2|$10.14
[Per-key LED](https://www.aliexpress.com/item/32830413032.html)|100|$9.12
[Underglow LED](https://www.aliexpress.com/item/4000475685852.html)|100|$10.58
Shipping to US|1|~$20
Tax|1|~$14

Full part names in case the links eventually die:

- Kailh 1.5u Low Profile Keycaps 1350 chocolate switch special cream white for gaming DIY mechanical keyboard ABS material 30PCS
- Kailh 1.0u Low Profile Keycaps 1350 chocolate switch special cream white for gaming DIY mechanical keyboard ABS material 30PCS
- Kailh Choc Red Crystal Switch low profile Switch Chocolate Mechanical Keyboard Switch RGB SMD white stem linear hand feeling
- Mechanical Keyboard Low Profile Switches Kailh PCB Socket CPG135001S30
- 5pcs 40 Pin Connector Header Round Needle 1x40 Golden Pin Single Row Male 2.54mm Breakable Pin Connector Strip
- 10pcs 1X40PIN 2.54MM 1x40 Pin 2.54 Round Female Pin Header Connector
- 10 Pcs TRRS 3.5 MM Audio Jack Connector Through Holes PCB Horizontal 4 Contact 4 Conductor Right Angle No Internal Switch 4 Pole
- 100pcs/lot 1206 1N4148W T4 1N4148 IN4148 SOD-123 IC
- Mini/Type-C/Micro USB Pro Micro ATMEGA32U4 5V/16MHZ module With the bootloader for arduino with 2 row pin header for arduino. Product properties: TYPE-C USB 3-6V
- 50-2000PCS SK6812 MINI-E RGB (similar with WS2812B) SK6812 3228 SMD Pixels LED Chip Individually Addressable Full Color DC 5V. Product properties: 100 PCS
- 50-1000pcs SK6812 WS2812B IC Bulit in 5050 3535 RGB SMD Addressable Digital RGB Full Color LED Chip Pixels Light Bead DC5V. Product properties: 5050 + White chip + 100pcs

## Lineup

- corne-classic([JP](corne-classic/doc/buildguide_jp.md)/[EN](corne-classic/doc/buildguide_en.md)):
    Corne for Cherry MX switches
- corne-cherry([JP](corne-cherry/doc/buildguide_jp.md)) ([tilting, JP](corne-cherry/doc/v2/buildguide_tilting_tenting_plate_jp.md)):
    Hotswappable Corne for Cherry MX switches by kailh PCB sockets.
- corne-chocolate([JP](corne-chocolate/doc/buildguide_jp.md)/[EN](corne-chocolate/doc/buildguide_en.md)):
    Hotswappable Corne for Chocolate switches using Kailh PCB hot-swap sockets.
- corne-light([JP](corne-light/doc/buildguide_jp.md)):
    Light-weight Corne (Easy build with a simple PCB).

## Photos

![cherry_01](https://user-images.githubusercontent.com/736191/47172655-0d0e9b80-d347-11e8-8a11-ccce9bf8d2b4.JPG)
![cherry_02](https://user-images.githubusercontent.com/736191/47172658-0da73200-d347-11e8-8ab5-6267faf3e447.JPG)
![cherry_03](https://user-images.githubusercontent.com/736191/47172661-0da73200-d347-11e8-95a5-4e978fbb70bb.JPG)
![cherry_04](https://user-images.githubusercontent.com/736191/47172662-0da73200-d347-11e8-8510-139a9ed94d9a.JPG)
![chocolate_01](https://user-images.githubusercontent.com/736191/49698496-0c3c0c80-fc08-11e8-87bc-4fd2aa7f3f78.jpg)
![chocolate_02](https://user-images.githubusercontent.com/736191/49698493-06462b80-fc08-11e8-95fd-8d18763b38ff.jpg)
![classic_01](https://user-images.githubusercontent.com/736191/43596530-8330e31e-96ba-11e8-8aee-4956470d2c3b.png)
![classic_02](https://user-images.githubusercontent.com/736191/43596538-8ab6be6a-96ba-11e8-90c5-13edd2eb7fb4.png)
![light_01](https://user-images.githubusercontent.com/736191/69654854-d615c800-10b8-11ea-8903-ebf019d7b125.png)
![light_02](https://user-images.githubusercontent.com/736191/69654882-df069980-10b8-11ea-8efe-069b68db3bc0.png)
