# vibracer_code
Flora code for controlling timed buzzer

This is the code for controlling a 'vibracer'. This was created for the Acedemy of Eblana LARP. 

Pressing any button will cause a one second buzz immediately and another buzz n seconds later. The current version is set to 10, 15, 20, 25 for testing purposes. The end version will be 10 seconds, 30 seconds, 1 minute, and 5 minutes.

Durations in the code are all reduced by one second as the 'oscillate' function starts in the same state you want it to finish in, in this case, off. Starting one second earlier seemed the neatest way around this.

COMPONENTS:
https://www.adafruit.com/product/659
https://www.adafruit.com/product/1201
https://www.adafruit.com/product/1332
Some, like, connecty bits (our current prototype uses crocodile clips)

LIBRARIES:
https://www.facebook.com/stevenkavanagh404?fref=jewel
