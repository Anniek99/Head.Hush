# HeadHush

A beanie that eases headaches with heat and vibration, controlled by touch patches sewn into the hat or by a web app.

## Description

About 40 million Americans get migraines. HeadHush gives drug-free relief you can use anywhere, built into something that just looks like a beanie. Vibration motors and a heating pad target pressure points around the head. You control them with touch patches sewn into the beanie or with a web app hosted on the ESP32, so it works with or without a phone.

Built as a team of four in Leffell's E² (Engineering & Entrepreneurship) course, 2024-2025.

## Components

- ESP32
- Mini disc vibration motors, heat-shrunk onto bent aluminum
- Heating pad
- Boost regulator
- IRF9640 P-channel MOSFET and 2N2222 transistor (heater switch), 10 kΩ pull-up
- 3.7V LiPo battery
- Touch patches made from conductive thread and Velostat
- Beanie with a sewn zipper pocket that hides the electronics

## Code

hotspot.ino is the final version, connected to the web app. 
