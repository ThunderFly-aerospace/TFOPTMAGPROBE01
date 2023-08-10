# TFPROBE01A - Omnipolar magnetic and reflective optical sensor probe

![KiCad](https://github.com/ThunderFly-aerospace/TFPROBE01/workflows/KiCad/badge.svg)

The sensor is designed for RPM measurement with [TFRPM01 sensor board](https://github.com/ThunderFly-aerospace/TFRPM01). The probe consists dual sensing technique - optical or magnetic. Therefore the user should select the one most suitable for the application.

<p float="center">
<img src="/doc/img/TFPROBE01A_connector.jpg" width="48%" />
<img src="/doc/img/TFPROBE01A_sensors.jpg" width="48%" />
</p>

> This module (TFGPS01A) was developed by [ThunderFly s.r.o.](https://www.thunderfly.cz) and is published as OpenSource hardware with a [GPLv3](LICENSE) license. It is possible to buy on request. For a quote contact us by email at info@thunderfly.cz. Or together with a [TFRPM01](https://github.com/ThunderFly-aerospace/TFRPM01) sensor at [Tindie store](https://www.tindie.com/products/thunderfly/tfrpm01-drone-rpm-tachometer-sensor/).


### Magnetic Sensing

The magnetic Hall-effect sensor mounted on the probe board is able to sense both directions of the magnetic field. The strength of the magnetic field is a decisive parameter for the probe's correct function. The magnetic flux is expected to be perpendicular to the sensor PCB surface. The detailed requirements of magnetic flux density are described in [AH3572 datasheet page 4](/doc/datasheets/AH3572-1483253.pdf).

In magnetic sensing, it is recommended to cover the probe in a black shrinking tube.  The covering blocks function of a reflective sensor.

### Optical Sensing

An optical sensor is sensitive to the infrared reflectance of material (usually a rotating disc with marks).
To details see the [VCNT2020 datasheet page 2](/doc/datasheets/vcnt2020.pdf)

## Hardware
TFPROBE01A is designed as Open-Hardware (GPL v3). All documentation is located in this repository.

The TFPROBE01 is sold and shipped without a soldered header, because its orientation may depend on the customer's use. Connecting cable and two headers (one straight and one right-angled) are included.

![Shipping content](/doc/img/TFPROBE01A_shipping_content.jpg)

### PCB

<p float="center">
<img src="/doc/img/TFPROBE01A_top_big.png" width="48%" />
<img src="/doc/img/TFPROBE01A_bot_big.png" width="48%" />
</p>

#### PCB dimensions

![TFPROBE01A PCB dimensions](doc/img/TFPROBE01A_dimensions.png)


##### Optical probe position

![TFPROBE01A optical probe position](doc/img/optical_sensor_position.png)

### Electronic schema

Full schema is available in [PDF](/doc/gen/TFPROBE01A-schematic.pdf)

[![schema](/doc/gen/TFPROBE01A-schematic.svg)](/doc/gen/TFPROBE01A-schematic.pdf)
