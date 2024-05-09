This is a Home Assistant integration for two KACO solar power inverters via a ESPHome.
The ESP8266 works as Data logger for KACO Powador Inverters 2500xi and 4500xi via two interfaces:
- Interface 1: S0 imupls count interface for Supplied Power to Grid (the number of counts per 1 kW is configurable in Inverter-Setup)
- Interface 2: RS485 serial bus communication protocol for various data provided from the inverter (Inverter State, PV-Voltage, PV-Current, PV-Power, Grid-Voltage, Grid-Current, Supplied Power to Grid, Inverter Temperature, Daily Energy, Inverter Type Name)

The ESPHome YAML configuration does also have an additional DHT11 sensor for Temperature and Humidity to measure the environment close to the Inverters.
<img src="https://github.com/GernotAlthammer/HA-ESPHome-KACO-Powador-4500xi-S0-RS485/blob/main/Pictures/Pic1_Steuerelemente.png">
<img src="https://github.com/GernotAlthammer/HA-ESPHome-KACO-Powador-4500xi-S0-RS485/blob/main/Pictures/Pic2_Sensoren.png">
<img src="https://github.com/GernotAlthammer/HA-ESPHome-KACO-Powador-4500xi-S0-RS485/blob/main/Pictures/Pic3_Konfiguration.png">
<img src="https://github.com/GernotAlthammer/HA-ESPHome-KACO-Powador-4500xi-S0-RS485/blob/main/Pictures/Pic4_Diagnose.png">
