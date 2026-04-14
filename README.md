# SwtoCentrala

SwtoCentrala is an application designed for the automated management and coordination of telecommunication system components. Based on FreePBX, the project is designed to allow for the rapid deployment of a complete environment with a default configuration, eliminating the need for manual parameter setup.

## Project Purpose
This project is intended for environments that require fast deployment of a telephone exchange, specifically for:
* Testing VoIP phones and devices.
* Development laboratories.
* Rapid prototyping of telecommunication services.

## Key Features
* Automated Installation: Full configuration of the system environment and services.
* Service Readiness: Immediate preparation of basic telecommunication services.
* Extension Management: Automatic creation of basic internal numbers (extensions).
* Voicemail Support: Activation of voice message recording and playback functions.

## Default Configuration
After installation, the system is ready to operate with the following settings:
* Extension: 100
* Password: 123
* Recording/Playback: Number *777

## Installation

To install SwtoCentrala, clone the repository and run the installation script:

```bash
git clone [https://github.com/Emka98/Centrala.git](https://github.com/Emka98/Centrala.git)
cd Centrala
chmod +x Install
./Install
