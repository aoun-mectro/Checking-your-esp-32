# Checking-your-esp-32
This is a small tutorial to know wheter your new esp 32 is working correctly. Most veterans know this but many new commers don't.

When you power your esp32 with your laptop or desktop, the red led light should light up(this may be different color depending on your manufacturer).
To see if your esp32 is actually getting the code and the pins are working correctly you can use this. 
I will also be giving the simple code and a YouTube video for those who may not understand what to do and are new to this world. 

disclaimer: for all reading this, pin 2 on esp32 is reserved for the onboard led on esp32. if you are trying this code for an external LED change the #define LED 2 , with a different pin such as #define LED 16 etc. 
And make sure to use a resistor or else the LED will blow up. 