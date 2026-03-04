# Backup of my 3d printing files
I use the script backup_script.sh to automatically upload my Klipper files as a backup. If someone wants to use this: 

Source code and workflow: "klipper-backup"

# Setup
+ Printer: Ender 5 Plus w/ Mercury One.1 CoreXY Conversion
  - Firmware: Klipper
  - Interface: Mainsail
  - Mainboard: BIGTREETECH Octopus v1.1 STM32F446ZET6
  - Host: Raspberry Pi 5 8GB w/ 1tb NVME M.2
  - Camera: Anycubic Live View Camera
  - Stepper Drivers: TMC2209 Autotune TMC
  - Extruder: EBB36 Canbus V6 Ceraminc Volcano
  - Probe: Eddy Duo Probe Canbus
  - Slicer of choice: Cura 5.10.1
  - Planned Mods:
    - ZeroG Hydra Bed Mod
    - EVA 2.4
    - Orbiter 1.5
    - Enclosure
    - Rear Mount Electronics
    - Enclosure Heater
    - Sexbolt Nozzle Probe

# klipper-backup 💾 
Klipper backup script for manual or automated GitHub backups 

This backup is provided by [klipper-backup](https://github.com/Staubgeborener/klipper-backup).
