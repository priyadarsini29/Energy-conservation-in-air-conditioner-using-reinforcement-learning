# Energy-conservation-in-air-conditioner-using-ML and RL
This project implements a smart, energy-efficient air conditioner (AC) control system using Machine Learning (ML) and Reinforcement Learning (RL). It reads historical and real-time temperature data, detects room occupancy, and adjusts the AC/fan settings to reduce energy consumption while maintaining comfor

Features

Predicts AC operation using historical temperature data (ML).

Adjusts AC/fan settings in real-time based on occupancy and temperature (RL).

Supports PWM fan speed control for precise cooling.

Monitors temperature and humidity using DHT22 sensor.

Detects presence of people with PIR sensor to avoid unnecessary cooling.



Hardware Requirements

ESP32 or ESP8266

DHT22 Temperature & Humidity Sensor

PIR Motion Sensor

Fan + L298N Motor Driver

12V Adapter for fan


Software Requirements

MicroPython (for ESP32/ESP8266),python

---

How It Works

1. Data Collection: Historical temperature, humidity, and occupancy data are collected.


2. ML Prediction: Predicts initial AC/fan actions based on past patterns.


3. RL Adjustment: Continuously monitors real-time temperature and occupancy to optimize energy usage.


4. Fan Control: PWM signal adjusts fan speed for precise cooling.


5. Energy Optimization: Balances comfort and electricity consumption.




