# Atrix v0.2
A simple Apple 30pin breakout that just gives you sync and serial. Atrix was designed to both replace and simplify the old PodBreakout, which has been discontinued for a while.

#### Please note; At this time, I have not received these parts yet for testing, so use at your own risk.

# Mockup
<img src="./mockups/Atrix_breakout_board_top.png" width="140" height="300">
<img src="./mockups/Atrix_breakout_board_bottom.png" width="140" height="300">

# How-to
### What you'll need;
1. FTDI Basic aka FTDI Friend (Sparkfun, Adafruit, Amazon, etc.)
2. 6-pin header (Sparkfun, Adafruit)
3. 470k resistor (Sparkfun, Adafruit; usually sold in resistor kits)
4. USB micro-B SMD connector (Sparkfun)
5. Male 30-pin iPod connector (Sparkfun)

### Serial
1. Prepare three 2 inch lengths of colored wire preferably green, white, and black
2. Solder accordingly to Atrix;
  * Green to TX
  * White to RX
  * Black to GND
3. Solder accordingly to the FT232RL board
  * Green to RX
  * White to TX
  * Black to GND
4. Solder a 470k resistor between one of the GNDs and the ACC pin
5. You're all set.

### Sync
1. Prepare a USB-A to USB mini-B cable by cutting the USB-B side off, exposing the four wires (red, black, green, white)
2. Solder accordingly to Atrix;
  * Red to 5v
  * Green to D+
  * White to D-
  * Black to GND (GND1 is provided to you because it's easier to solder these pins right next to each other)
3. You're all set, try plugging in the USB into your computer and the 30pin into your target device to see if your computer identifies your target device.
