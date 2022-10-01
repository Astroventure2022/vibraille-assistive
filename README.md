# ViBraille | An Assistive Device for The Blind and Deaf-Blind
ViBraille Glove is a digital tactility glove that lets it's users read text from any platform in the braille format.
6 Vibration motors mimic the configuration of the 3 by 2 dot matrix Braille Alphabet.

The glove is developed with ESP32 for it's packaged bluetooth connectivity features. It receives the texts as char arrays over the Bluetooth Serial and parses them into tactile signals through the motors.
