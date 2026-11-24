# Hi, I'm ls6777

Fun with firmware. I build small, free tools in my spare time: embedded C++ libraries for
ESP32 and RTOS projects, and smartwatch faces for Garmin and Wear OS.

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/ls6777)

## Projects

**Embedded**
- [PrintfTask](https://github.com/ls6777/PrintfTask): buffers `printf` output in RAM and
  sends it from a low-priority task, so `printf` returns quickly
- [TaskMonitor](https://github.com/ls6777/TaskMonitor): checks that every registered task
  keeps running
- [Esp32DisplayLogger](https://github.com/ls6777/Esp32DisplayLogger): ESP32 app that turns
  an LCD into a terminal of the UART output, built on the two libraries above
- [M5Dial](https://github.com/ls6777/M5Dial): Heat Troller for the M5Stack Dial (ESP32-S3
  with a round LCD and a rotary encoder), built on PrintfTask and TaskMonitor. Work in
  progress

**Watch faces**
- [DataDial](https://github.com/ls6777/garmin-datadial): analog watch face for Garmin fēnix 9
  with eight live stats and goal gauges, free on the Connect IQ Store
- [DataDial for Wear OS](https://github.com/ls6777/wearos-datadial): DataDial ported to the
  Pixel Watch 5, with analog or digital time, weather and UV, and stats from Google Health
- [Night Dial](https://github.com/ls6777/NightDial): handless Wear OS face for the Pixel
  Watch 5 that marks the hour, minute and second on the dial, with weather, heart rate, UV
  and four gauges
- [FitbitWatchAnalogClock](https://github.com/ls6777/FitbitWatchAnalogClock): analog clock
  with stats for the Fitbit Versa

If something here saved you time, a [coffee](https://buymeacoffee.com/ls6777) is a nice way
to say thanks.
