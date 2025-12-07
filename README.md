# lm393-esphome-soilsensor
LM393 Soil Sensor with ESPHome

I picked up a pack of these LM393 Soil Sensors from Amazon (Link Here: https://www.amazon.com/dp/B0DTHXKC1D?ref=ppx_yo2ov_dt_b_fed_asin_title)

These have a Digital Output and an Analog Output. For these sensors, I found that fully open produces 1.00000V, and a dead short produces 0.00098 V. I used the following YAML to make these cheap sensors work on an ESP01 board (Works on ESP32 as well, adjust Pins as needed)
