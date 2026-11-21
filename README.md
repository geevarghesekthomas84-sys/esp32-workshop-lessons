<div align="center">

<a href="https://esp32.itgg.space"><img src="screenshots/esp32-board.png" alt="ESP32 DevKit" width="150"></a>

# ESP32 Workshop

**A visual guide to 50 hands-on ESP32 lessons.**

Learn circuits, sensors, wireless communication, and connected projects through an interactive 3D workshop.

<a href="https://esp32.itgg.space"><strong>Open the live workshop →</strong></a>

</div>

---

## About

ESP32 Workshop is a browser-based learning experience created by **Geevarghese K Thomas**. It guides learners from the ESP32 board and basic circuits to sensors, networking, IoT security, and complete projects.

The live lessons pair a 3D workspace with a lesson guide and interactive experiments. This public repository is a **read-only showcase** with lesson explanations and screenshots; it contains no project source code or Arduino materials.

**Website:** [esp32.itgg.space](https://esp32.itgg.space)

## At a glance

- **50 lessons** from beginner circuits to IoT capstones
- **Topics:** GPIO, sensors, displays, motors, Wi-Fi, Bluetooth, MQTT, and device security
- **Screenshots:** one selected-lesson view for every lesson
- **Format:** lesson guide and images only

## Workshop preview

<p align="center">
  <img src="screenshots/esp32-workshop.png" alt="ESP32 Workshop lesson interface" width="860">
</p>

<p align="center"><sub>The ESP32 workspace, lesson guide, and lesson browser.</sub></p>

## Browse the lessons

Open a lesson below to see its screenshot and explanation. Select an image to view it full size.

### Start here · Lessons 01–10

Meet the board, learn the first circuit patterns, and explore Wi-Fi and simple inputs.

<details>
<summary><strong>01 · Meet the ESP32</strong></summary>

<a href="screenshots/lessons/01-board.jpg"><img src="screenshots/lessons/01-board.jpg" alt="Lesson 01: Meet the ESP32 in the ESP32 workshop" width="900"></a>

The ESP32 is a tiny, powerful microcontroller with Wi-Fi and Bluetooth built in. This DevKit puts it on a board with USB-C and two rows of pins, ready for your circuits.

[View full-size screenshot ↗](screenshots/lessons/01-board.jpg)

</details>

<details>
<summary><strong>02 · Flash two LEDs</strong></summary>

<a href="screenshots/lessons/02-blink.jpg"><img src="screenshots/lessons/02-blink.jpg" alt="Lesson 02: Flash two LEDs in the ESP32 workshop" width="900"></a>

Your first circuit: two LEDs that take turns, like the lights at a level crossing. Each has its own pin and resistor; the sketch switches one on and the other off, waits, then swaps them. The board’s blue LED, also on GPIO 2, flashes with the left one.

[View full-size screenshot ↗](screenshots/lessons/02-blink.jpg)

</details>

<details>
<summary><strong>03 · Guard the fridge</strong></summary>

<a href="screenshots/lessons/03-button.jpg"><img src="screenshots/lessons/03-button.jpg" alt="Lesson 03: Guard the fridge in the ESP32 workshop" width="900"></a>

Left the fridge open again? A reed switch is a pair of springy contacts in a glass tube that touch when a magnet comes close. Stick it on top of the fridge with the magnet on the door: shut, the contacts are closed and GPIO 4 reads LOW. Leave the door open too long and the alarm LED comes on.

[View full-size screenshot ↗](screenshots/lessons/03-button.jpg)

</details>

<details>
<summary><strong>04 · Use Wi-Fi</strong></summary>

<a href="screenshots/lessons/04-wifi.jpg"><img src="screenshots/lessons/04-wifi.jpg" alt="Lesson 04: Use Wi-Fi in the ESP32 workshop" width="900"></a>

The ESP32 can join your Wi-Fi and serve a tiny web page. Open it on your phone and tap the button: the phone asks for <code>/toggle</code>, and the board switches the LED.

[View full-size screenshot ↗](screenshots/lessons/04-wifi.jpg)

</details>

<details>
<summary><strong>05 · Sound a siren</strong></summary>

<a href="screenshots/lessons/05-sound.jpg"><img src="screenshots/lessons/05-sound.jpg" alt="Lesson 05: Sound a siren in the ESP32 workshop" width="900"></a>

A passive buzzer clicks every time its pin flips; flip it hundreds of times a second and you hear a note. Sweep that note up and down in a loop and you have a siren — with a red and a blue lamp swapping over on every sweep.

[View full-size screenshot ↗](screenshots/lessons/05-sound.jpg)

</details>

<details>
<summary><strong>06 · Build a mini piano</strong></summary>

<a href="screenshots/lessons/06-piano.jpg"><img src="screenshots/lessons/06-piano.jpg" alt="Lesson 06: Build a mini piano in the ESP32 workshop" width="900"></a>

Eight of the ESP32’s pins can feel a fingertip. Wire each one to a copper key and the board plays a note with <code>tone()</code> when you touch it — no buttons needed.

[View full-size screenshot ↗](screenshots/lessons/06-piano.jpg)

</details>

<details>
<summary><strong>07 · Fill a ring of LEDs</strong></summary>

<a href="screenshots/lessons/07-knob.jpg"><img src="screenshots/lessons/07-knob.jpg" alt="Lesson 07: Fill a ring of LEDs in the ESP32 workshop" width="900"></a>

A potentiometer is a resistor with a slider: turning it moves its OUT pin anywhere from 0 V to 3.3 V, and the ESP32’s 12-bit ADC reads that as 0 to 4095. Here the reading fills a ring of twelve RGB LEDs like a gauge — all of them driven by one data wire.

[View full-size screenshot ↗](screenshots/lessons/07-knob.jpg)

</details>

<details>
<summary><strong>08 · Make a mood lamp</strong></summary>

<a href="screenshots/lessons/08-rgb.jpg"><img src="screenshots/lessons/08-rgb.jpg" alt="Lesson 08: Make a mood lamp in the ESP32 workshop" width="900"></a>

An RGB LED is three LEDs — red, green and blue — in one. Put it inside a frosted ball and the whole ball glows in their mix. Three buttons out in front each pick a colour: press one and the lamp switches to it.

[View full-size screenshot ↗](screenshots/lessons/08-rgb.jpg)

</details>

<details>
<summary><strong>09 · Light up in the dark</strong></summary>

<a href="screenshots/lessons/09-light.jpg"><img src="screenshots/lessons/09-light.jpg" alt="Lesson 09: Light up in the dark in the ESP32 workshop" width="900"></a>

A light-dependent resistor (LDR) lets more current through the more light falls on it. On this little board it’s paired with a fixed resistor, so its OUT pin gives a voltage that rises with the light. The ESP32 reads it and switches the table lamp on when the room gets dark, like a night light. Slide the cap over the sensor to make it night.

[View full-size screenshot ↗](screenshots/lessons/09-light.jpg)

</details>

<details>
<summary><strong>10 · Distance meter</strong></summary>

<a href="screenshots/lessons/10-sensor.jpg"><img src="screenshots/lessons/10-sensor.jpg" alt="Lesson 10: Distance meter in the ESP32 workshop" width="900"></a>

A pocket tape measure with no tape. The HC-SR04P times an ultrasonic echo, and a little OLED screen on its own stand shows the distance in big digits over a bar that grows as the obstacle moves away. Click the obstacle to swap it, or drag it.

[View full-size screenshot ↗](screenshots/lessons/10-sensor.jpg)

</details>

### Motors and automation · Lessons 11–20

Build movement and control projects with motors, servos, relays, and multi-part circuits.

<details>
<summary><strong>11 · Drive a wheel</strong></summary>

<a href="screenshots/lessons/11-motor.jpg"><img src="screenshots/lessons/11-motor.jpg" alt="Lesson 11: Drive a wheel in the ESP32 workshop" width="900"></a>

A pin can’t power a motor, and a single transistor can only turn it one way. A motor driver holds an H-bridge: four switches that can send the current through the motor in either direction — forwards, backwards, at any speed PWM asks for. It’s how robot cars steer.

[View full-size screenshot ↗](screenshots/lessons/11-motor.jpg)

</details>

<details>
<summary><strong>12 · Laser barrier gate</strong></summary>

<a href="screenshots/lessons/12-servo.jpg"><img src="screenshots/lessons/12-servo.jpg" alt="Lesson 12: Laser barrier gate in the ESP32 workshop" width="900"></a>

A red laser shines across the road onto a receiver. When a car drives into the beam, the receiver goes dark and the ESP32 swings a servo’s striped boom up. Once the car has gone through, it lowers it again.

[View full-size screenshot ↗](screenshots/lessons/12-servo.jpg)

</details>

<details>
<summary><strong>13 · Talk over Bluetooth</strong></summary>

<a href="screenshots/lessons/13-bluetooth.jpg"><img src="screenshots/lessons/13-bluetooth.jpg" alt="Lesson 13: Talk over Bluetooth in the ESP32 workshop" width="900"></a>

No router needed: the ESP32 can pair with your phone directly. A Bluetooth serial app sends “on” or “off”, and the board reads it just like the serial monitor.

[View full-size screenshot ↗](screenshots/lessons/13-bluetooth.jpg)

</details>

<details>
<summary><strong>14 · Board to board</strong></summary>

<a href="screenshots/lessons/14-espnow.jpg"><img src="screenshots/lessons/14-espnow.jpg" alt="Lesson 14: Board to board in the ESP32 workshop" width="900"></a>

ESP-NOW lets ESP32 boards message each other directly: no router, no pairing, and a message lands in milliseconds. Both boards run the same sketch, and each BOOT button switches the LED on the other one.

[View full-size screenshot ↗](screenshots/lessons/14-espnow.jpg)

</details>

<details>
<summary><strong>15 · Smart parking bay</strong></summary>

<a href="screenshots/lessons/15-project.jpg"><img src="screenshots/lessons/15-project.jpg" alt="Lesson 15: Smart parking bay in the ESP32 workshop" width="900"></a>

Put it all together. The distance sensor watches a parking bay, a traffic light guides the driver in — green, then yellow, then red to stop — and the bay tells your phone whether it is free or taken, over Wi-Fi. Click the lights to move the thresholds.

[View full-size screenshot ↗](screenshots/lessons/15-project.jpg)

</details>

<details>
<summary><strong>16 · Automatic water pump</strong></summary>

<a href="screenshots/lessons/16-pump.jpg"><img src="screenshots/lessons/16-pump.jpg" alt="Lesson 16: Automatic water pump in the ESP32 workshop" width="900"></a>

A tank that fills itself. A probe in the lid measures the water; at the low mark the ESP32 clicks a relay that runs a mains pump, and at the high mark it stops. Your phone shows the level over Wi-Fi.

[View full-size screenshot ↗](screenshots/lessons/16-pump.jpg)

</details>

<details>
<summary><strong>17 · Keypad door lock</strong></summary>

<a href="screenshots/lessons/17-keypad.jpg"><img src="screenshots/lessons/17-keypad.jpg" alt="Lesson 17: Keypad door lock in the ESP32 workshop" width="900"></a>

Type the right code and the safe opens. A keypad is a grid of buttons wired in rows and columns: the ESP32 drives one column at a time and listens on the rows, so seven wires read twelve keys. Get the code right and a servo swings its latch away from the handle; get it wrong three times and the buzzer sounds the alarm.

[View full-size screenshot ↗](screenshots/lessons/17-keypad.jpg)

</details>

<details>
<summary><strong>18 · Sun-tracking solar panel</strong></summary>

<a href="screenshots/lessons/18-solar.jpg"><img src="screenshots/lessons/18-solar.jpg" alt="Lesson 18: Sun-tracking solar panel in the ESP32 workshop" width="900"></a>

A solar panel makes the most power when it faces the sun, so this one turns to follow it. Two light sensors sit on top, either side of a small divider: facing the light, they read the same; turned away, the divider shades one of them. The ESP32 compares the two and turns the servo a degree towards the brighter side, again and again.

[View full-size screenshot ↗](screenshots/lessons/18-solar.jpg)

</details>

<details>
<summary><strong>19 · Ultrasonic radar</strong></summary>

<a href="screenshots/lessons/19-radar.jpg"><img src="screenshots/lessons/19-radar.jpg" alt="Lesson 19: Ultrasonic radar in the ESP32 workshop" width="900"></a>

An HC-SR04P tells you how far away something is, but only straight ahead. Put it on a servo and sweep it from side to side, taking a reading every degree, and you have a radar: the OLED beside it plots each echo where it came from, so the box, the ball and the toy car show up as dots in the right places.

[View full-size screenshot ↗](screenshots/lessons/19-radar.jpg)

</details>

<details>
<summary><strong>20 · Pick and place</strong></summary>

<a href="screenshots/lessons/20-stepper.jpg"><img src="screenshots/lessons/20-stepper.jpg" alt="Lesson 20: Pick and place in the ESP32 workshop" width="900"></a>

A stepper motor doesn’t just spin: every pulse turns it exactly one step, 200 to a turn. Put it on a lead screw and you have one axis of a CNC machine, accurate to a twenty-fifth of a millimetre. This one carries an electromagnet: press a button and it picks a steel ball off the feeder and drops it in that bin.

[View full-size screenshot ↗](screenshots/lessons/20-stepper.jpg)

</details>

### Sensors and network basics · Lessons 21–28

Read the environment, work with control inputs, and learn how devices share data.

<details>
<summary><strong>21 · Climate monitor</strong></summary>

<a href="screenshots/lessons/21-climate.jpg"><img src="screenshots/lessons/21-climate.jpg" alt="Lesson 21: Climate monitor in the ESP32 workshop" width="900"></a>

Read temperature and humidity from a DHT22 and show both on an OLED. Click the sensor to change the simulated room conditions. The board LED warns when either reading reaches its limit.

[View full-size screenshot ↗](screenshots/lessons/21-climate.jpg)

</details>

<details>
<summary><strong>22 · Motion alarm</strong></summary>

<a href="screenshots/lessons/22-motion.jpg"><img src="screenshots/lessons/22-motion.jpg" alt="Lesson 22: Motion alarm in the ESP32 workshop" width="900"></a>

A PIR module detects changes in infrared radiation from moving warm objects. Its digital output drives an alarm without stopping the rest of the program. Click the sensor to introduce motion, then clear it and watch the hold timer.

[View full-size screenshot ↗](screenshots/lessons/22-motion.jpg)

</details>

<details>
<summary><strong>23 · Smart plant monitor</strong></summary>

<a href="screenshots/lessons/23-plant.jpg"><img src="screenshots/lessons/23-plant.jpg" alt="Lesson 23: Smart plant monitor in the ESP32 workshop" width="900"></a>

A capacitive soil probe produces an analog voltage that changes with moisture. Convert the ADC reading into a calibrated percentage, show it on an OLED, and light the board LED when the soil is dry. Click the plant to change moisture.

[View full-size screenshot ↗](screenshots/lessons/23-plant.jpg)

</details>

<details>
<summary><strong>24 · Rotary encoder controller</strong></summary>

<a href="screenshots/lessons/24-encoder.jpg"><img src="screenshots/lessons/24-encoder.jpg" alt="Lesson 24: Rotary encoder controller in the ESP32 workshop" width="900"></a>

A rotary encoder sends two digital pulse sequences as you turn it. Their order tells the ESP32 the direction. Drag the outside of the knob to change the counter, and press its centre to reset it. The OLED shows the setting.

[View full-size screenshot ↗](screenshots/lessons/24-encoder.jpg)

</details>

<details>
<summary><strong>25 · Wi-Fi connection manager</strong></summary>

<a href="screenshots/lessons/25-wifi-manager.jpg"><img src="screenshots/lessons/25-wifi-manager.jpg" alt="Lesson 25: Wi-Fi connection manager in the ESP32 workshop" width="900"></a>

A device should recover when its router disappears. Follow connection attempts, authentication failures, signal strength, and the assigned IP address. Change the router controls while the sketch runs and watch it reconnect.

[View full-size screenshot ↗](screenshots/lessons/25-wifi-manager.jpg)

</details>

<details>
<summary><strong>26 · Internet clock</strong></summary>

<a href="screenshots/lessons/26-internet-clock.jpg"><img src="screenshots/lessons/26-internet-clock.jpg" alt="Lesson 26: Internet clock in the ESP32 workshop" width="900"></a>

An NTP server supplies a reference time over the network. After synchronization, the ESP32 system clock keeps ticking during a Wi-Fi outage. This lab uses a simulated time service based on the browser clock.

[View full-size screenshot ↗](screenshots/lessons/26-internet-clock.jpg)

</details>

<details>
<summary><strong>27 · Live sensor dashboard</strong></summary>

<a href="screenshots/lessons/27-sensor-dashboard.jpg"><img src="screenshots/lessons/27-sensor-dashboard.jpg" alt="Lesson 27: Live sensor dashboard in the ESP32 workshop" width="900"></a>

Turn the climate monitor into a small web server. A browser requests JSON readings and updates its dashboard. Watch requests and responses, then test outages and stale readings. All network traffic in this lab is simulated.

[View full-size screenshot ↗](screenshots/lessons/27-sensor-dashboard.jpg)

</details>

<details>
<summary><strong>28 · MQTT sensor publisher</strong></summary>

<a href="screenshots/lessons/28-mqtt-publisher.jpg"><img src="screenshots/lessons/28-mqtt-publisher.jpg" alt="Lesson 28: MQTT sensor publisher in the ESP32 workshop" width="900"></a>

MQTT separates a device that publishes readings from applications that consume them. Connect to a simulated broker, publish JSON to a topic, and observe what happens when the broker goes offline.

[View full-size screenshot ↗](screenshots/lessons/28-mqtt-publisher.jpg)

</details>

### Connected device security · Lessons 29–35

Practice safer credential handling, trusted connections, update checks, and network scanning.

<details>
<summary><strong>29 · Protect Wi-Fi credentials</strong></summary>

<a href="screenshots/lessons/29-credential-security.jpg"><img src="screenshots/lessons/29-credential-security.jpg" alt="Lesson 29: Protect Wi-Fi credentials in the ESP32 workshop" width="900"></a>

Wi-Fi passwords should never be committed to a public sketch. Practice keeping credentials in a local secrets.h file, excluding it from version control, and joining a WPA2 or WPA3 network. This lab is simulated and never reads or stores a real password.

[View full-size screenshot ↗](screenshots/lessons/29-credential-security.jpg)

</details>

<details>
<summary><strong>30 · Verify HTTPS certificates</strong></summary>

<a href="screenshots/lessons/30-https-certificates.jpg"><img src="screenshots/lessons/30-https-certificates.jpg" alt="Lesson 30: Verify HTTPS certificates in the ESP32 workshop" width="900"></a>

HTTPS encrypts traffic, while certificate validation helps confirm the server identity. Explore how a trusted, current certificate connects and how an unknown or expired certificate is rejected. The lab is simulated and makes no real network requests.

[View full-size screenshot ↗](screenshots/lessons/30-https-certificates.jpg)

</details>

<details>
<summary><strong>31 · Secure MQTT access</strong></summary>

<a href="screenshots/lessons/31-mqtt-access.jpg"><img src="screenshots/lessons/31-mqtt-access.jpg" alt="Lesson 31: Secure MQTT access in the ESP32 workshop" width="900"></a>

An MQTT broker can check a client identity and limit which topics it may publish to. Test rejected logins and topic permissions, then deliver a message with an authorized client. The broker and traffic are simulated.

[View full-size screenshot ↗](screenshots/lessons/31-mqtt-access.jpg)

</details>

<details>
<summary><strong>32 · Verify firmware updates</strong></summary>

<a href="screenshots/lessons/32-firmware-security.jpg"><img src="screenshots/lessons/32-firmware-security.jpg" alt="Lesson 32: Verify firmware updates in the ESP32 workshop" width="900"></a>

A device should verify an update before installing it, then confirm the new firmware boots correctly. Explore signature rejection, failed-install rollback, and a successful signed update. This lab simulates the update flow and downloads nothing.

[View full-size screenshot ↗](screenshots/lessons/32-firmware-security.jpg)

</details>

<details>
<summary><strong>33 · Secure IoT capstone</strong></summary>

<a href="screenshots/lessons/33-security-capstone.jpg"><img src="screenshots/lessons/33-security-capstone.jpg" alt="Lesson 33: Secure IoT capstone in the ESP32 workshop" width="900"></a>

Prepare a small connected device for a safe deployment. The gateway checks private Wi-Fi credentials, a trusted TLS certificate, MQTT topic permission, and a signed firmware update. Fix each gate in order; the simulation sends no real traffic.

[View full-size screenshot ↗](screenshots/lessons/33-security-capstone.jpg)

</details>

<details>
<summary><strong>34 · ESP32 physical security</strong></summary>

<a href="screenshots/lessons/34-physical-security.jpg"><img src="screenshots/lessons/34-physical-security.jpg" alt="Lesson 34: ESP32 physical security in the ESP32 workshop" width="900"></a>

Physical access can expose debug interfaces and data in flash. Check debug access, flash encryption, and recovery-key backup before approving a device. Permanent security settings are difficult to reverse, so verify recovery plans before applying them to real hardware.

[View full-size screenshot ↗](screenshots/lessons/34-physical-security.jpg)

</details>

<details>
<summary><strong>35 · Nearby Wi-Fi scanner</strong></summary>

<a href="screenshots/lessons/35-wifi-scanner.jpg"><img src="screenshots/lessons/35-wifi-scanner.jpg" alt="Lesson 35: Nearby Wi-Fi scanner in the ESP32 workshop" width="900"></a>

Use the ESP32 station radio to passively scan nearby Wi-Fi access points. Compare SSIDs, channels, signal strength, and whether each network advertises encryption. The simulation shows a busy neighborhood with twelve routers; it never probes or joins a real network.

[View full-size screenshot ↗](screenshots/lessons/35-wifi-scanner.jpg)

</details>

### Displays and sensing · Lessons 36–43

Add color, numeric, and matrix displays alongside motion, air quality, RFID, and pressure sensors.

<details>
<summary><strong>36 · TFT color display</strong></summary>

<a href="screenshots/lessons/36-tft.jpg"><img src="screenshots/lessons/36-tft.jpg" alt="Lesson 36: TFT color display in the ESP32 workshop" width="900"></a>

Drive a 1.8" ST7735 color TFT over SPI. Draw a title bar, a large value, and a bar gauge. Click the screen to change the value, switch between a cool and a warm palette, rotate the display, or swap between gauge and shapes demos. The board LED lights when the gauge is full.

[View full-size screenshot ↗](screenshots/lessons/36-tft.jpg)

</details>

<details>
<summary><strong>37 · 7-segment clock</strong></summary>

<a href="screenshots/lessons/37-seg7.jpg"><img src="screenshots/lessons/37-seg7.jpg" alt="Lesson 37: 7-segment clock in the ESP32 workshop" width="900"></a>

A TM1637-driven 4-digit 7-segment display speaks a simple two-wire protocol. Set the hours and minutes, dim the display, and blink the colon like a real digital clock. The board LED lights at maximum brightness.

[View full-size screenshot ↗](screenshots/lessons/37-seg7.jpg)

</details>

<details>
<summary><strong>38 · NeoPixel strip animations</strong></summary>

<a href="screenshots/lessons/38-neopixel.jpg"><img src="screenshots/lessons/38-neopixel.jpg" alt="Lesson 38: NeoPixel strip animations in the ESP32 workshop" width="900"></a>

An eight-pixel WS2812 strip reads one data wire. Switch between a solid color, a travelling chase, and a full rainbow, then dial in the brightness and the speed. The board LED lights when the rainbow runs at high brightness.

[View full-size screenshot ↗](screenshots/lessons/38-neopixel.jpg)

</details>

<details>
<summary><strong>39 · Dot-matrix scrolling sign</strong></summary>

<a href="screenshots/lessons/39-matrix.jpg"><img src="screenshots/lessons/39-matrix.jpg" alt="Lesson 39: Dot-matrix scrolling sign in the ESP32 workshop" width="900"></a>

A MAX7219-driven 8×8 LED matrix scrolls text across its grid. Pick the message, set brightness and speed, and watch the sign crawl. The board LED lights at high brightness.

[View full-size screenshot ↗](screenshots/lessons/39-matrix.jpg)

</details>

<details>
<summary><strong>40 · Accelerometer tilt</strong></summary>

<a href="screenshots/lessons/40-accel.jpg"><img src="screenshots/lessons/40-accel.jpg" alt="Lesson 40: Accelerometer tilt in the ESP32 workshop" width="900"></a>

An MPU6050 reports 3-axis acceleration over I2C. Compute pitch and roll from gravity, and catch a shake with a quick spike in total acceleration. The board LED lights when the device is tilted past the alert angle or shaken.

[View full-size screenshot ↗](screenshots/lessons/40-accel.jpg)

</details>

<details>
<summary><strong>41 · Air quality monitor</strong></summary>

<a href="screenshots/lessons/41-airq.jpg"><img src="screenshots/lessons/41-airq.jpg" alt="Lesson 41: Air quality monitor in the ESP32 workshop" width="900"></a>

An MQ-135 sensor’s analog output rises as volatile organic compounds build up. Read it on an ADC pin, convert to an approximate ppm, and turn on the warning LED when the air gets stuffy.

[View full-size screenshot ↗](screenshots/lessons/41-airq.jpg)

</details>

<details>
<summary><strong>42 · RFID door badge</strong></summary>

<a href="screenshots/lessons/42-rfid.jpg"><img src="screenshots/lessons/42-rfid.jpg" alt="Lesson 42: RFID door badge in the ESP32 workshop" width="900"></a>

An MFRC522 reader talks to a 13.56 MHz badge over SPI. When a card appears, read its UID and compare it against an allowlist — open the lock LED only when the UID matches.

[View full-size screenshot ↗](screenshots/lessons/42-rfid.jpg)

</details>

<details>
<summary><strong>43 · Barometric altimeter</strong></summary>

<a href="screenshots/lessons/43-baro.jpg"><img src="screenshots/lessons/43-baro.jpg" alt="Lesson 43: Barometric altimeter in the ESP32 workshop" width="900"></a>

A BMP280 reports atmospheric pressure over I2C. Compare it with the sea-level reference and compute altitude with the barometric formula. The board LED lights above the alert altitude.

[View full-size screenshot ↗](screenshots/lessons/43-baro.jpg)

</details>

### Integrations and capstones · Lessons 44–50

Connect the workshop ideas to webhooks, Home Assistant, OTA updates, time-series data, and complete builds.

<details>
<summary><strong>44 · Webhook to Discord</strong></summary>

<a href="screenshots/lessons/44-webhook-discord.jpg"><img src="screenshots/lessons/44-webhook-discord.jpg" alt="Lesson 44: Webhook to Discord in the ESP32 workshop" width="900"></a>

A webhook URL lets any device post a message into a Discord channel — no bot, no OAuth. Send an HTTPS POST with a tiny JSON body and the message appears instantly. In this lab, flip the Send toggle to fire a message; watch delivery, failures, and the delivered count.

[View full-size screenshot ↗](screenshots/lessons/44-webhook-discord.jpg)

</details>

<details>
<summary><strong>45 · Home Assistant MQTT discovery</strong></summary>

<a href="screenshots/lessons/45-home-assistant.jpg"><img src="screenshots/lessons/45-home-assistant.jpg" alt="Lesson 45: Home Assistant MQTT discovery in the ESP32 workshop" width="900"></a>

Home Assistant listens on a well-known MQTT topic for device descriptions. Publish one JSON payload to <code>homeassistant/sensor/&hellip;/config</code> and the device appears on the dashboard, then stream state to its own topic.

[View full-size screenshot ↗](screenshots/lessons/45-home-assistant.jpg)

</details>

<details>
<summary><strong>46 · OTA update over the LAN</strong></summary>

<a href="screenshots/lessons/46-ota-update.jpg"><img src="screenshots/lessons/46-ota-update.jpg" alt="Lesson 46: OTA update over the LAN in the ESP32 workshop" width="900"></a>

The ESP32 can download and install new firmware from an HTTP server, verify its signature, and reboot into the new image. In this lab, toggle Start update to walk through downloading, verifying, and installing — flip Signature valid off to see a rollback.

[View full-size screenshot ↗](screenshots/lessons/46-ota-update.jpg)

</details>

<details>
<summary><strong>47 · InfluxDB time-series</strong></summary>

<a href="screenshots/lessons/47-influxdb.jpg"><img src="screenshots/lessons/47-influxdb.jpg" alt="Lesson 47: InfluxDB time-series in the ESP32 workshop" width="900"></a>

A time-series database stores every reading with a timestamp and lets you plot it over time. The ESP32 buffers samples in RAM and flushes them to InfluxDB in batches; when Wi-Fi drops, samples pile up until the link returns.

[View full-size screenshot ↗](screenshots/lessons/47-influxdb.jpg)

</details>

<details>
<summary><strong>48 · Smart mailbox</strong></summary>

<a href="screenshots/lessons/48-smart-mailbox.jpg"><img src="screenshots/lessons/48-smart-mailbox.jpg" alt="Lesson 48: Smart mailbox in the ESP32 workshop" width="900"></a>

A capstone that combines the motion sensor from lesson 22 with the Wi-Fi webhook from lesson 44. A PIR watches the mailbox; on motion it fires a notification to your phone — subject to a quiet period so one visit does not spam the channel. Toggle mute to stop alerts without disabling the sensor.

[View full-size screenshot ↗](screenshots/lessons/48-smart-mailbox.jpg)

</details>

<details>
<summary><strong>49 · Plant watering scheduler</strong></summary>

<a href="screenshots/lessons/49-plant-scheduler.jpg"><img src="screenshots/lessons/49-plant-scheduler.jpg" alt="Lesson 49: Plant watering scheduler in the ESP32 workshop" width="900"></a>

A capstone that mixes the plant monitor from lesson 23 with a simple time schedule and a relay. The pump runs only inside the scheduled window AND when soil moisture is below the threshold — so a daily check won’t over-water. In this sim, 1 simulated minute passes per real second so you can watch the schedule tick.

[View full-size screenshot ↗](screenshots/lessons/49-plant-scheduler.jpg)

</details>

<details>
<summary><strong>50 · Weather station</strong></summary>

<a href="screenshots/lessons/50-weather-station.jpg"><img src="screenshots/lessons/50-weather-station.jpg" alt="Lesson 50: Weather station in the ESP32 workshop" width="900"></a>

The grand capstone — combines the climate sensor (DHT22), the barometric altimeter (BMP280), the OLED, and a browser dashboard. Readings refresh locally every second and are POSTed as JSON to the dashboard. The project pulls together sensors, display, Wi-Fi, and a web endpoint.

[View full-size screenshot ↗](screenshots/lessons/50-weather-station.jpg)

</details>

---

<p align="center"><strong>Ready to explore?</strong><br><a href="https://esp32.itgg.space">Visit the ESP32 Workshop →</a></p>
