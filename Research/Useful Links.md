### Useful Links

* [Etendue](https://en.wikipedia.org/wiki/Etendue)
* [Fresnel Web Simulator](https://phydemo.app/ray-optics/gallery/fresnel-lens)
* [Luminus 51V 20,000 COB LED](https://www.digikey.com/en/products/detail/luminus-devices-inc/CXM-32-40-80-54-AC40-F5-3/15198244)
* [Analog Devices 60V, Synchronous Step-Down High Current LED Driver](https://www.analog.com/en/technical-articles/60v-synchronous-step-down-high-current-led-driver.html)
* [AliExpress 300mm Fresnel Lens](https://www.aliexpress.us/item/2251832628415712.html?spm=a2g0o.productlist.main.31.1f113ddeb9tH3N&algo_pvid=a1f6df46-a8d6-4ca2-82e5-49793ad79313&algo_exp_id=a1f6df46-a8d6-4ca2-82e5-49793ad79313-15&pdp_npi=4%40dis%21USD%2126.98%2115.65%21%21%2126.98%21%21%402103224117048672573401020ee459%2164614171461%21sea%21US%211674932255%21&curPageLogUid=t92vTPvIzuQ7&utparam-url=scene%3Asearch%7Cquery_from%3A)
* [Coilcraft Working Voltage Ratings Applied to Inductors](https://www.coilcraft.com/getmedia/393e18e1-adbc-45b6-bbe7-5923255e72fc/doc712_inductor_voltage_ratings.pdf)
* [Log Amp Basics](https://www.analog.com/media/en/training-seminars/tutorials/MT-077.pdf)
* [AD Logarithmic Transimpedance Amplifiers](https://www.analog.com/en/product-category/translinear-logarithmic-amplifiers.html)
* [AD High Frequency Log Amps](https://www.analog.com/media/en/training-seminars/tutorials/MT-078.pdf)
* [Nonlinear Circuits Handbook, 1976](https://www.analog.com/en/resources/technical-books/nonlinear-circuits-handbook.html)



### Part Selection

Power Converter:

* [LM5169FDDAR](https://www.digikey.com/en/products/detail/texas-instruments/LM5169FDDAR/16893914)
  * Pretty cheap: $2.06 @ QTY 10
  * Synchronous COT
    * Integrated FETs
  * 120V Max Input
  * 1.2V Min Output

MCU:

* [ESP32-C6-WROOM-1-N8](https://www.digikey.com/en/products/detail/espressif-systems/ESP32-C6-WROOM-1-N8/17728866)

#### LED Drivers

* [LM3409HVMYX/NOPB](https://www.ti.com/lit/ds/symlink/lm3409.pdf)
  * 75V Max Input
  * Current Sense Resistor?: [TLRP3A30DR050FTE](https://www.digikey.com/en/products/detail/te-connectivity-passive-product/TLRP3A30DR050FTE/14652237)
    * 50m
    * 3W
  * PFET: [SQJ479EP-T1_GE3](https://www.digikey.com/en/products/detail/vishay-siliconix/SQJ479EP-T1-GE3/6708893)
    * 80V Vsd
    * 32A
    * 33mOhm

ADC:

* [ADS1015IDGSR](https://www.digikey.com/en/products/detail/texas-instruments/ADS1015IDGSR/2231559)
  * 12 bit
  * I2C
  * 4 Channel
  * Not rubbish

LED Temperature Sensor:

* RTD: [P0K1.520.6W.A.010](https://www.digikey.com/en/products/detail/innovative-sensor-technology-usa-division/P0K1-520-6W-A-010/13686722)
* PT100
* 3850ppm/°C

Photodiode:

* [VTP9812FH](https://www.digikey.com/en/products/detail/excelitas-technologies/VTP9812FH/5885875)
  * 580nm peak sensitivity
  * 0.034A/W @ 580nm
  * IR Blocking
  * Will it have enough dynamic range?

Op-Amps:

* [MCP6009T-E/SL](https://www.digikey.com/en/products/detail/microchip-technology/MCP6009T-E-SL/12807435)
  * Cheap as fuck: $0.31 at QTY 25
  * OK slew rate: 1.9V/us
  * 1MHz GWBP
  * OK max input offset voltage: 1.6mV

Generic Transistors:

* NPN: [MMBT2222A-TP](https://www.digikey.com/en/products/detail/micro-commercial-co/MMBT2222A-TP/717279)
  * 600mA
  * 40V Vce
* NFET: [T2N7002AK,LM](https://www.digikey.com/en/products/detail/toshiba-semiconductor-and-storage/T2N7002AK-LM/5298028)
  * 200mA
  * 60V Vds