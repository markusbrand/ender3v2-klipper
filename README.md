# klipper-backup 💾 

# Installation Instructions for Klipper

1. Use Raspberry Pi imager and create image (other Raspberry Pi images -> Raspberry Pi light (64 bit)
2. Set username pi and password,name, wlan settings and SSH access with password
3. Generate a private key - type <code>ssh-keygen -t rsa</code> in terminal
4. Copy public key to raspberry Pi: <code>ssh-copy-id pi@ender3.local</code>
5. Access raspberry pi via SSH with user: <code>ssh pi@ender3.local</code>
6. Install KIAUH: https://github.com/dw-0/kiauh
7. Install KAMP: https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging
8. Install klipper-backup: https://github.com/Staubgeborener/klipper-backup
9. Copy over config files from this GIT repository to Klipper on raspberry pi (https://github.com/markusbrand/ender3v2-klipper/tree/master/ender3v2-klipper)
