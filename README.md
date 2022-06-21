# T-PicoC3_tft_setup
 
This is for LilyGo T-Pico3: https://www.tindie.com/products/lilygo/lilygo-t-picoc3-esp32-c3-rp2040-wireless-wifi/
Need TFT_eSPI library to work: https://github.com/Bodmer/TFT_eSPI

To use
1. Put this file in the library path:
   ...\Documents\Arduino\libraries\TFT_eSPI\User_Setups\Setup138_LilyGo_TPicoC3.h
2. Edit ...\Documents\Arduino\libraries\TFT_eSPI\User_Setup_Select.h
   Comment out: #include <User_Setup.h> 
   Add line below: #include <User_Setups/Setup138_LilyGo_TPicoC3.h>           // Setup file for Lilygo TPicoC3 and ST7789 135 x 240 TFT
