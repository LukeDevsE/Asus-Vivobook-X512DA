# Asus-Vivobook-X512DA
Efi files for X512DA vivobook, hackintosh

# Dont forget to change device info things
- MLB
- ROM
- SystemProductName
- SystemSerialNumber
- SystemUUID
heres a guide: https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html
# do after install
after you install, build this https://github.com/ChefKissInc/NootedRed
then put it in kexts, and do oc clean snapshot using https://github.com/corpnewt/ProperTree, on dialog press yes, it will be laggy until you put nooted red
# Tested on
Ventura (13)
# Things that work
- [x] Wifi Intel AC 7265
- [x] Bluetooth Intel AC 7265
- [x] Ports
- [x] Audio Realtek ALC256
- [ ] Microphone (you could just buy a external mic and plug it in)
- [x] accelerated graphics & iGPU
- [ ] Camera
- [x] Touchpad
- [x] Keyboard
- [x] Battery Status
- [x] Cpu: Ryzen 3 3500U
- [x] Sleep & Shutdown & Restart
