
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




