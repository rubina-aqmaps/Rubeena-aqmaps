This project showcases a compact, Arduino-compatible environmental monitoring system designed to collect real-time data on air quality, pollution, 
and weather conditions. The board integrates 6 sensors, each targeting a critical environmental parameter relevant to urban, rural, and indoor air quality applications.

Connected Sensors & Parameters
Sensor	Parameter Measured	Type
NO₂ Sensor (e.g., MiCS-2714 or equivalent)	Nitrogen Dioxide (NO₂)	Analog Gas Sensor
MQ135	CO₂, VOCs, NH₃, Benzene	Analog Gas Sensor
MQ136	Sulfur Dioxide (SO₂)	Analog Gas Sensor
MQ9	Carbon Monoxide (CO), Methane (CH₄), LPG	Analog Gas Sensor
PM2.5 Sensor (e.g., PMS5003/SDS011)	Particulate Matter (PM1.0, PM2.5, PM10)	UART-based Dust Sensor
DHT11	Temperature & Relative Humidity	Digital Sensor (1-wire)

Total Readings Captured: 7
NO₂ concentration – Measured via dedicated NO₂ analog sensor
CO₂ / VOCs concentration – From MQ135
SO₂ concentration – From MQ136
CO / CH₄ / LPG concentration – From MQ9
PM2.5 / PM10 concentration – From PM sensor (e.g., PMS5003)
Temperature (°C) – From DHT11
Humidity (% RH) – From DHT11

Application Use-Cases
Urban air quality monitoring
Indoor pollution assessment (homes, schools, offices)
Smart agriculture and greenhouse management
Health-focused environment tracking
Educational and citizen science projects

Modular Architecture
Each sensor connects via analog, UART, or digital GPIO pins.
Can operate in standalone mode (Serial Monitor) or integrated with LoRaWAN, Wi-Fi, or BLE for remote transmission.
Payload-ready for The Things Network (TTN) or IoT dashboards.
