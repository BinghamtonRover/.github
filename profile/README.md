## Binghamton University Rover Team
<div align=center>
<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/BinghamtonRover/.github/main/burt-logo_black-text.svg">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/BinghamtonRover/.github/main/burt-logo_white-text.png">
  <img src="https://raw.githubusercontent.com/BinghamtonRover/.github/main/burt-logo_black-text.svg" height=200px/>
</picture>  
</div>

### About Us
We are the Binghamton University Rover Team (BURT), representing Binghamton University in the [University Rover Challenge](https://urc.marssociety.org). The competition consists of a variety of missions designed to test our rover's navigation, maneuverability, dexterity, and more. Our team is split into three mechanical teams (drive, arm, and science), an electrical team, a firmware team, and a software team. This repository is for the firmware and software teams. 

### The Firmware Team

Our firmware team specializes in low-level [Arduino]https://docs.arduino.cc/learn/) code running on [Teensy 4.1 boards](https://www.pjrc.com/store/teensy41.html). The code is designed to be as simple and error-free as possible, with no dynamic memory allocation, following all commands exactly, and reporting all sensor data. Firmware code uses our shared [networking](https://github.com/BinghamtonRover/Firmware-Utilities) and [motor](https://github.com/BinghamtonRover/TMC-Firmware) libraries. 

#### Firmware Repositories

All firmware repositories should follow the same rough structure as outlined in the [template](https://github.com/BinghamtonRover/Firmware-Template).

- **Shared libraries**: [Protobuf](https://github.com/BinghamtonRover/Protobuf) [Firmware Utilities](https://github.com/BinghamtonRover/Firmware-Utilities), [TMC](https://github.com/BinghamtonRover/TMC-Firmware)
- **On-rover firmware**: [Drive](https://github.com/BinghamtonRover/Drive-Firmware), [Electrical](https://github.com/BinghamtonRover/Electrical-Firmware), [Arm](https://github.com/BinghamtonRover/Arm-firmware), [Science](https://github.com/BinghamtonRover/Science-firmware)
- **Off-rover firmware**: [Antenna Control](https://github.com/BinghamtonRover/Antenna-Firmware), [Motor test board](https://github.com/BinghamtonRover/Motor-Test-Firmware)

### The Software Team

Our software team writes the high-level code that helps coordinate the firmware and other devices. The main component here is the [Dashboard](https://github.com/BinghamtonRover/Dashboard), our cross-platform Flutter application for testing, debugging, and operating the rover or any of its components individually. Each Dart program runs on a [Raspberry Pi](https://www.raspberrypi.com/) or similar Linux device and communicates with the other programs via UDP.

#### Software Repositories

- **Shared libraries**: [Protobuf](https://github.com/BinghamtonRover/Protobuf), [Networking](https://github.com/BinghamtonRover/Networking), 
- **User interfaces**: [Dashboard](https://github.com/BinghamtonRover/Dashboard)
- **Core programs**: [Subsystems](https://github.com/BinghamtonRover/Subsystems), [Video](https://github.com/BinghamtonRover/Video), [Autonomy](https://github.com/BinghamtonRover/Autonomy)
- **Helper programs**: [Lidar](https://github.com/BinghamtonRover/Lidar), [Computer Vision](https://github.com/BinghamtonRover/Computer-Vision), [Base Station](https://github.com/BinghamtonRover/Base-Station)
- **Pub packages**: [flutter_sdl_gamepad](https://pub.dev/packages/flutter_sdl_gamepad), [a_star](https://pub.dev/packages/a_star), [pub_cache](https://pub.dev/packages/pub_cache_server), [typed_isolate](https://pub.dev/packages/typed_isolate)

### Repositories
- [Dashboard](https://github.com/BinghamtonRover/Dashboard)
- Networking: [Protobuf](https://github.com/BinghamtonRover/Protobuf), [Networking](https://github.com/BinghamtonRover/Networking), [Firmware Utilities](https://github.com/BinghamtonRover/Firmware-Utilities)
- Onboard code: [Subsystems](https://github.com/BinghamtonRover/Subsystems), [Autonomy](https://github.com/BinghamtonRover/Autonomy), [Video](https://github.com/BinghamtonRover/Video)
- Firmware: [TMC](https://github.com/BinghamtonRover/TMC-Firmware), [Arm](https://github.com/BinghamtonRover/Arm-firmware), [Science](https://github.com/BinghamtonRover/Science-firmware), [Drive](https://github.com/BinghamtonRover/Drive-Firmware)
- Pis: [SubsystemsPi](https://github.com/BinghamtonRover/SubsystemsPi), [SecondaryPi](https://github.com/BinghamtonRover/SecondaryPi)

### Links
- [Our Wiki at GitBooks](https://bing-rover.gitbook.io/docs)
- [Our website](https://www.binghamton.edu/watson/competes/rover-team/index.html)
- [Our YouTube channel](https://www.youtube.com/@binghamtonuniversityroverteam)
- Contacts: [Email](mailto:rover@binghamton.edu) | [Instagram](https://www.instagram.com/bing_roverteam/) | [LinkedIn](https://www.linkedin.com/company/bingmarsrover)
