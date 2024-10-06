# V2.6514 Klipper Config Backup
VORON V2.6514 Backup from SeaSpotter (Discord)

# Features
- [BTT Manta M8P with CB1](https://t4kuuy4.github.io/Voron-Documentation/build/electrical/V2_M8P_Wiring.html)
- [Mellow Fly SB2040 CAN](https://github.com/cruiten/Voron-Related/tree/main/CANbus/Documentation)
- [Stealthburner](https://vorondesign.com/voron_stealthburner)
- [Galileo 2](https://github.com/JaredC01/Galileo2)
- [Zero Offset GE5C](https://github.com/TorxFighter/Voron-Mods/tree/main/Zero-Offset_Clamped_GE5C)
- [Mellow CNC Tap]
- [Top corner cable cover](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Dr-Info/corner_cable_cover_with_drop_down_holes)
- [Bedpan with Wiper](https://www.printables.com/model/659369-voron-24-purge-bucket-silicon-brush-wiper)
- [Rear Y Endstop](https://github.com/RepRapster/Voron2.4-Rear-Gantry-Y-Endstop-Mount)
- [BTT HDMI5](https://www.printables.com/model/586475-hdmi5-case-for-voron-24-300)
- [Hex Skirts](https://www.printables.com/model/474406-voron-24-skirts-with-hex-infill-250-300-and-350mm-)
- [BFI Frontidler](https://github.com/clee/VoronBFI)
- [Nevermore v6](https://github.com/nevermore3d/Nevermore_Micro/tree/master/V6)
- [Bedfans](https://mods.vorondesign.com/detail/28xgztUufAtAfV4XUL5l4w)


# Software and Config
- [Git backup](https://github.com/th33xitus/kiauh/wiki/How-to-autocommit-config-changes-to-github%3F)
- [SB2040 Can Install](https://mellow-3d.github.io/fly_sb2040_v2_canboot_can.html)
- [Air Filter Timer](https://github.com/MapleLeafMakers/KlipperMacros/blob/main/air_filter_timer.cfg)
- [A Better Print_start](https://github.com/jontek2/A-better-print_start-macro)
- [Clean Nozzle](https://github.com/VoronDesign/VoronUsers/blob/master/orphaned_mods/printer_mods/edwardyeeks/Decontaminator_Purge_Bucket_%26_Nozzle_Scrubber/Macros/nozzle_scrub.cfg)
- [KAMP](https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging)
- [LED Effects](https://github.com/julianschill/klipper-led_effect/blob/master/docs/LED_Effect.md)
  

# Must Have
- [Ellis Print Tuning](https://ellis3dp.com/Print-Tuning-Guide/)

# Flashing Klipper

For MantaM8P

![image](https://github.com/seaspotter/Voron_Backup_V2.6514/assets/5041760/650695d0-e523-415d-858f-74806050f8d6)

- make flash FLASH_DEVICE= /dev/serial/by-id/usb-Klipper_stm32h723xx_1E0016001951313236343430-if00

For SB2040 CAN

(https://mellow-3d.github.io/fly_sb2040_v2_canboot_can.html)

- python3 ~/katapult/scripts/flash_can.py -i can0 -f ~/klipper/out/klipper.bin -u 27d65112b208
