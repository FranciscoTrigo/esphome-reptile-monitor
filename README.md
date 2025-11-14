# esphome-reptile-monitor
An Esphome based temperature and humidity sensor for reptile enclosures

This is a device I made to monitor the temperature and humidity in my chameleon gecko's enclosure. It reads the sensor values every minute and displays the data nicely in a 4.2 inch e-ink screen.

## Features

- The displays shows the current temperature and humidity values
- The displays shows whether the environment is too hot, cold, dry, or humid, or ideal.

## Materials

- [ESP32 board](https://www.amazon.com/dp/B0C9THDPXP?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)
- [Waveshare 4.2inch E-ink display](https://www.amazon.com/dp/B074NR1SW2?ref=ppx_yo2ov_dt_b_fed_asin_title)
- [Waveshare BME280](https://www.amazon.com/dp/B07P4CWGGK?ref=ppx_yo2ov_dt_b_fed_asin_title)
- [Suction cup](https://www.amazon.com/dp/B09BTW2148?ref=ppx_yo2ov_dt_b_fed_asin_title)
- 3D printed case

## Customization

### Display content

You might want to change a few things in the yaml file:

- Change the display language (default is Spanish)
- Temperature and humidity ranges

## 3D Printed case

This is the first 3D thing that I design (and it shows!), so its not very good, the first version turned out to be too big.