<h1>MiBand 4 Font Customize</h1>
<h2><b>Requirements</b></h2>
Python 3
    
    sudo apt-get install python3    
    
Pillow

    sudo apt-get install python3-pil

<h2><b>Pack / unpack font<b></h2>
Unpack font

    mi4font.py unpack 'font.tf'

Pack font (must have bmp and latin folder at root)

    mi4font.py pack 'new_font.tf'
    
<h2><b>Install</b></h2>
Use Notify app and choose update firmware, choose the new font file (.tf)
