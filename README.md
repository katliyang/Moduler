# Orbital-2017

A browser application for users to plan their modules across semesters and share it with their academic advisors and friends. Source code for http://orbital.darklyght.com.

## Install
On a clean Ubuntu system, run the following commands:

```
wget https://git.katliyang.com/darklyght/Orbital-2017-Install/raw/03bfde8eff853eff1fb8aa40e304fa5d64818d11/moduler-install.sh
```
```
chmod +x moduler-install.sh
```
```
bash moduler-install.sh
```
If you require an Ubuntu system to test the script on, do consider using my [DigitalOcean referral link](https://m.do.co/c/c9881f486a87). It is greatly appreciated and will support future development.

## Usage
Run the following commands to run the application
```
screen -dmS horizon bash -c 'hz serve --dev --bind all'
```
```
screen -dmS quasar bash -c 'PORT=80 quasar dev'
```
The application will utilise two separate screen sessions, one for Horizon and one for Quasar.

## Disclaimer
This application was made for a student project and is not ready for production use under any cirumstances. Quasar and Horizon are run under development mode. Use at your own risk.