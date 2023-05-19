# digiandroid
 Adaptation of the (digistump digispark library)[https://github.com/digistump/DigistumpArduino] and the (CedArctic digispark keyboard scripts)[https://github.com/CedArctic/DigiSpark-Scripts] into one library, ready to by added to (ArduinoDroid)[https://play.google.com/store/apps/details?id=name.antonsmirnov.android.arduinodroid2] app.

 The goal of this library is to enable the user to quickly swap digispark rubber ducky scripts via OTG (On-The-Go) in the android app ArduinoDroid.
 
 Furthermore, inside the "keyboards" folder, a "scancode-ascii-table.h" file can be found for each of 11 different keyboards. To change keyboard, replace this file in the "src" folder (Attention: the default keyboard in "src" folder is not EN_US, but PT_PT).
 
 
 All credits go to the three links above mentioned.

# Usage

After downloading the .zip file in your android phone, got to the ArduinoDroid app, click Library->Add .ZIP Library->digiandroid.zip.
To get the examples, click Sketch->Library Examples->User Libraries->digiandroid->[example.ino]
To upload to the digispark, first you need to select the board, go to Settings->Board type->Digistump->Digispark (Default- 16.5mhz).