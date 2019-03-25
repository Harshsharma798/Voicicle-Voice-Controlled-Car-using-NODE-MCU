# Voicicle-Voice-Controlled-Car-using-NODE-MCU
Voicicle is a voice controlled car that could be controlled using Google Assistant and at the backend a lot much of IoT platforms are running to process the voice signals to do some actions in NODE-MCU

It would accept voice command from user through the best available Speech to Text converter i.e. Google Assistant and that even be having a good UI.
The signals would go to IFTTT from Google Assistant and from that it would be transferred to Adafruit platform.

From Adafruit, MQTT buffer based Protocol would be used for fetching the values to ESP8266 mounted at the board in the vehicle side.

For using the project make account from same google account on Adafruit, IFTTT.
Use your Adafruit UID and secret key instead of mine.
Sign-in with same account on your phone's Google Assistant.

Flash the code to Arduino Board and enjoy commanding the vehicle from google assistant.
