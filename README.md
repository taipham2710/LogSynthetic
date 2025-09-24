# Synthetic IoT Log Generator

This repository generates synthetic logs for IoT devices (ESP32, ESP8266, Raspberry Pi) to support testing and training anomaly detection models.

## Directory Structure

```
LogSynthetic/
 ├── generator/
 │    ├── esp32_logs.py
 │    ├── esp8266_logs.py
 │    ├── raspi_logs.py
 │    └── utils.py
 ├── datasets/
 │    ├── sample_esp32.json
 │    ├── sample_esp8266.json
 │    └── sample_raspi.json
 ├── tests/
 │    └── test_generator.py
 ├── requirements.txt
 ├── README.md
 └── .github/workflows/
      └── ci.yml
```

## How to Use

1. Install Python 3.8+
2. Install packages: `pip install -r requirements.txt`
3. Run generator scripts in the `generator/` folder
4. Generated logs are saved under `datasets/`