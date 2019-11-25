# Things-to-do

## Things on Raspberry Pi  3B+ 

- [ ] Implement automatic sniffing and decoding NEXA remote codes through matplotlib (Might be through a Flask api)
  - [ ] Send them to Cloud Firestore after decoding and testing
- [ ] Try to decode the NEXA dimmer
  - [ ] See if the speed of the dimmer can be changed (pulse modulation?)

## Things on Raspberry Pi  Zero #1

- [ ] Move the Flask switch-api from RiPi3B+ to a docker container on Raspberry Pi zero 
- [ ] Setup HomeAutomation-ConfigurationAPI in docker container (will move to separate Pi in the future)
- [ ] Setup a arc-scan crontab that reports which phones that are home to firebase through HomeAutomation-ConfigurationAPI

## Things on Raspberry Pi  Zero #2

- [ ] Setup automatic deployment when pushing to a branch in HomeAutomation-hub repo

- [ ] Implement firebase directly into the React app


## Other

- [ ] Build the ergodox
- [ ] Solder antennas to the 433MHz RF senders
- [ ] Finish https://www.udemy.com/course/react-the-complete-guide-incl-redux/
- [ ] Look into building a React native app for light switches for both Android and iOS
  - [ ] Implement both apps with firebase authentication and Cloud Firestore