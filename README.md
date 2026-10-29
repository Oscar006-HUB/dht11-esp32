# DHT11 Temperature & Humidity Reader

Arduino sketch that reads temperature (°C) and relative humidity from a DHT11 sensor and prints them to the serial monitor every 2 seconds.

## Hardware
- ESP32 (or other Arduino-compatible board)
- DHT11 sensor, data pin on GPIO 11 (change `DHTPIN` to match your wiring)

## Software
- Arduino IDE
- **DHT sensor library** by Adafruit (plus Adafruit Unified Sensor)

## Usage
1. Open `dht11_esp32/dht11_esp32.ino` in the Arduino IDE.
2. Select your board and port, then upload.
3. Open the Serial Monitor at **9600 baud**.

Sample output:
```
Humidity: 55.00%  Temp: 28.00°C
```

## License

Released under the [MIT License](LICENSE).
