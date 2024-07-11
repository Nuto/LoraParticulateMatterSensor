# LoraParticulateMatterSensor
[ELV LoRaWAN® Feinstaubsensor, ELV-LW-SPM](https://de.elv.com/p/elv-lorawan-feinstaubsensor-elv-lw-spm-P160408)

A fine dust sensor that transmits sensor values via the LoRaWAN network. The power supply can be from 5-40V DC. A Sensirion SPS30 sensor is installed inside.

## Power Consumption
We have tested the power consumption of the ELV sensor. It requires approx. 60mA, which is unfortunately quite a lot if you want to operate it via a battery. A constant power supply is therefore required. Since the sensor could be used quite independently via LoRa, it would be really great if ELV could make improvements here. According to the documentation, the SPS30 would also support "low-power operation", in which it would only require 38 μA in idle mode. The sensor is currently running in continuous operation and you can hear the fan all the time.

![powersconsumption](docs/powerconsumption.png)

## The Things Network

To register the sensor in "The Things Network" you still need these settings. Unfortunately, there is currently (July 2024) no possibility to select the device directly via the search.

![thethingsnetwork](docs/thethingsnetwork.png)
