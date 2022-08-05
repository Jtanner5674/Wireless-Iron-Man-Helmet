    Wireless Iron-Man Cosplay helmet code
    This code allows you to wirelessly control any iron man cosplay helmet that uses two servos as the turning mechanism.
    Written by Joshua Tanner
    current update date: 8/4/2022
    Please input your info in the #define section
    follow this guide for setting up arduino IDE: https://www.instructables.com/Wemos-ESP8266-Getting-Started-Guide-Wemos-101/
    The servos will need an external power source. I connected both of mine to a single usb cable to power them using a power bank.
    
   -=-=-=-=-=-=-==-=-=- INSTRUCTIONS -=-=-=-=-=-=-==-=-=-
   
   1. Install servos in helmet
   
   2. Wire servo power cabled to ONE usb port to connect to mobile power bank
   
   3. connect servos data line to D7 and D5 on Wesmos d1 mini
   
   4. Plug in the servos and wesmos board and wait for the servos to connect to the internet
      When they connect, the servos will move to the open position. 
   
   5. Connect 2 spare servo arms NOT THE MASK for initial test. 
   
   6. Send close command from sinric pro and watch the arms move. 
      If they are still together (in line with the other) then remove the arms and place the mask in the closed position. 
      If they are not together (pointing in different directions) then swap the data cable positions D7 -> D5 and vice versa
      At this point you may connect the arms to the helmet and unplug the board
   
   7. Open the helmet manually and screw the arms in
   
   8. Congratulations! You now have succesfully set up the helmet! Enjoy!
   
