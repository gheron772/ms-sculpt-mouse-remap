# ms-sculpt-mouse-remap
Remap microsoft sculpt mouse tilt wheel (left, right) to (backward, forward) in windows

### Way 1 - Use below autohotkey script
```Autohotkey
WheelLeft::
BlockInput, on
Send {Browser_Back}
BlockInput, off
sleep 500
return

WheelRight::
BlockInput, on
Send {Browser_Forward}
BlockInput, off
sleep 500
return
```
### Way 2 - Reigster compiled file to shell:startup
2-1. Download [(mouse.exe)](https://github.com/gheron772/ms-sculpt-mouse-remap/raw/main/mouse.exe)  
2-2. Press windows + r then type shell:startup and open  
2-3. Copy mouse.exe into shell:startup window  
2-4. Reboot  

### Donation
If this repository is helpful  
<a href='https://ko-fi.com/D1D02VFSG' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://cdn.ko-fi.com/cdn/kofi2.png?v=2' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
