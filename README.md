Radio occupies first SPI bus so I make second SPI bus using free GPIO pin
CS- Chip select, LOW to start talking, HIGH to stop
SCK- sync time using master(ESP32) to help data transfer
MISO- Master In Slave Out, read operations from slave(reader) to master(esp32)
MOSI- Master Out Slave In, write operations from master to slave

