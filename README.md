
![161749018_282783820082534_115154827738176981_n](https://user-images.githubusercontent.com/62314932/112739017-1365c080-8f60-11eb-9d14-461a78fd183e.jpg)


The project is my idea made in KiCad The Floppy Drive is no different from those sold on Ebay or Alliexpres but to be honest, I do not know how these sold on the Internet work and, above all, they can be programmed without a problem, when I made the first project of this from the original scheme, I could not program STM32 because BOOT1 was not connected to the GND after connecting BOOT1 to GND STM32 it was possible to program it without any problems
After programming the drive did not want to run I started looking for information and found in the datasheed a note about BOOT0 that you need to connect to VDD I did so too, thanks to which the drive started
The station are motivated to the inside of the amiga, the station has a tape exit to the control panel outside the amiga

A1200 Internal Gotek Fix Elektroda.rar I add programer pins so we can very fast programing STM32 via programer st-Link or something
![165952232_3815843695128739_1778376234516182579_n](https://user-images.githubusercontent.com/62314932/112739025-27a9bd80-8f60-11eb-9521-6677727ebc1c.jpg)

We can also program as standard gotek from ebay via serial interface TX and RX
To put Stm32 into serial programming state we need to change the position of the jumpers 

BOOT_0 connect to 3V3

BOOT_1 connect to GND

![programowanie serial](https://user-images.githubusercontent.com/62314932/112739226-5a58b380-8f6a-11eb-8c31-2625225f94e0.jpg)

After programming the station, the jumpers must be put in the device operating mode 

BOOT_0 connect to GND

Remove the jumper from Boot_1 and put on DS0 if you want Gotek as DF0 drive or put on DS1 if you want DF1 as drive 

![DF0](https://user-images.githubusercontent.com/62314932/112739669-0bad1880-8f6e-11eb-8172-d3f564cc29a0.jpg)
![DF1](https://user-images.githubusercontent.com/62314932/112739754-c6d5b180-8f6e-11eb-9dba-cb3c79aa87db.jpg)

The station, as I mentioned at the beginning, has a front panel
![gotek amiga](https://user-images.githubusercontent.com/62314932/116167793-f22bf780-a6f8-11eb-9666-f4a8d5ddd459.jpg)
![165444419_222351239674462_3815302755646016310_n](https://user-images.githubusercontent.com/62314932/112740088-e15d5a00-8f71-11eb-86e1-806de4366f71.jpg)

The panel has a 0.96 "OLED display.

USB connector

Power Led

Bussy LED

Switch UP

Switch DOWN 

![164138724_135902738462599_5116543401497129945_n](https://user-images.githubusercontent.com/62314932/112739854-b1ad5280-8f6f-11eb-9e2c-4f11a4e21f5e.jpg)
![163427264_189899506000117_1002609077379487508_n](https://user-images.githubusercontent.com/62314932/112739855-b245e900-8f6f-11eb-9a3b-2e8171d77dfb.jpg)





