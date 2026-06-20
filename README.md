# Sensor_Data_Logging
This project demonstrates sensor data acquisition and logging using Arduino.
     Environmental sensor values (temperature and light) are sampled at fixed intervals and stored as timestamped CSV entries on an SD card.

Working Principle :

Sensors are read at a fixed sampling interval.
RTC provides current date and time.
Each reading is stored as a new row in a CSV file:
Timestamp, Temperature, Light
Data is appended until required samples are collected.

Sampling Rate & Power Considerations :

Sampling interval is set using delay() / timer logic.
Lower sampling rates reduce:
Power consumption
SD card write cycles
SD card is accessed only during write operations to save power.

Skills Demonstrated :

Sensor interfacing
SD card data logging
SPI communication
RTC usage
Embedded system design considerations

https://drive.google.com/file/d/1G7gOVF-IecMebCaVpWAKeRvcYq7chQcY/view?usp=drive_link
