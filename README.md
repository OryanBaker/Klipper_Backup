# Backup of my 3d printing files
I use the script backup_script.sh to automatically upload my Klipper files as a backup. If someone wants to use this: 

Source code and workflow: "klipper-backup"

# Setup
+ Printer: Ender 5 Plus w/ Mercury One.1 CoreXY Conversion
  - Interface:
    - Klipper: v0.13.0-734-gfe4eb865
    - Mainsail: v2.18.2
    - Mainsail Config: v1.2.1-1-gff3869a6
    - Moonraker: v0.10.0-31-gd5ee1712
    - Crowsnest: v4.2.0-1-gcf936dab
    - Sonar: v0.2.0-1-g0d1d7c89
    - Timelapse: v0.0.1-143-gc7fff11e
    - Katapult: v0.0.1-113-gec59b9bb
    - KlipperScreen: v0.4.7-149-ged40799f
    - Klipper TMC Autotune: v0.2.0-385-gb6c7cfa9
    - Klipper Backup: v1.3.6-1-g77d83ac3
    - Mobilraker: v0.5.0-10-gd455af67
    - Octoeverywhere: v5.3.0-0-g5738b78d
    - Z Calibration: v1.1.3-1-g374d487f
    - OS: Bookworm
    - Kernel: 6.12.96+rpt-rpi-2712
  - Mainboard: BIGTREETECH Octopus v1.1 STM32F446ZET6
  - Host: Raspberry Pi 5 Model B Rev 1.1  8GB
    - Boot Drive 512GB NVME M.2
    - Storage Drive: 1TB NVME M.2
  - Camera: Anycubic Live View Camera
  - Stepper Drivers: TMC2209 Autotune TMC
  - Extruder: EBB36 Canbus V6 Ceraminc Volcano
  - Probe: Eddy Duo Probe Canbus
  - Power: APC Battery Backup with Web Interface & Lithium Ion Batteries
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
