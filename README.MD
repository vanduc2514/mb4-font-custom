<h1>MiBand 4 Font Customize</h1>

![Screenshot Test](https://github.com/vanduc2514/mb4-font-custom/blob/master/rsz_img_20210404_152428.jpg)

<h2>Requirements for edit font</h2>

**Python 3**
    
    sudo apt-get install python3    
    
**Pillow**

    sudo apt-get install python3-pil

<h2>Pack / unpack font</h2>

Unpack the font (leave font at project root)

    mi4font.py unpack "name of the file follows by .tf"

Pack the font (must have bmp and latin folder at root)

    mi4font.py pack "name of the file follows by .tf"
    
<h2>Install</h2>
1. Pack the font (must have bmp and latin folder at root)
    
    mi4font.py pack custom_vi_v1.9.3.tf

2. Copy the packed font to your phone

3. Use Gadgetbridge, open the copied font by Gadgetbridge

https://f-droid.org/en/packages/nodomain.freeyourgadget.gadgetbridge/

4. Install and wait for the flash to complete

<h2>UTF-16 Hex Lookup</h2>
https://www.compart.com/en/unicode

<h3>Special Thanks:</h3>

https://github.com/amazfitbip/font_tool

https://geekdoing.com/forums/
