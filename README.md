# Vaja8-I2C-ADS1115-STM32F0

c) V kategoriji Connectivity izberite in omogočite I2C komunikacijo. Kateri pini se
aktivirajo? __PB7___ in ___PB6__. Koliko različnih I2C komunikacij vaša razvojna
plošča omogoča? __2___.

e) Sedaj ADS1115 modul povežite z ustreznimi pini na STM32F0. Ne pozabite na
upore in kondenzator. Katere pine ste izbrali
SCL(ADS1115)-PB6(STM32F0),
SDA(ADS1115)-PB7(STM32F0),
ADDR(ADS1115)-GND(STM32F0),
ALRT(ADS1115)-ni povezan,
VDD(ADS1115)-3V(STM32F0)

f) V Parameter Settings protokola I2Cspremenite Speed Mode na Fast. Koliko
znaša sedaj frekvenca?______8MHz________.

Komentar:Naloga žal ni delovala po pričakovanjih. Meniva, da je težava v vzpostavitvi komunikacije.
