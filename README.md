# voron v0
Config repo for voron v0 to save the configuration and monitor changes made.

# Buildlog
26.07.2024
- Fixing Wiring
- Removed Display
- Removed BTT Pi1

27.07.2024
- Added Raspberry Pi 4B with MainsailOS
- 1st Startup
- Install updates for MainsailOS
- Upload first config
- Added main values for motors
- Added main vaules for thermistors
- Fixed macros
- Adjusted bed direction
- Adjusted StallGuard
- PID-Tuning für bed and nozzle

29.07.2024
- Added Display
- Added KlipperScreen

30.07.2024
- Added Shaketune
- Added Input Shaper LIS2DW
- Added frequencies
- Adjust frequencies

04.08.2024
- Disabled LIS2DW
- Layout Adjustments
- Configure Crowsnest
- Configure Neopixel

08.08.2024
- Added macro to control chamber led
- Better names

09.08.2024
- Adjust wait-time before print start
- Adjust value
- Added excluded_objects and adjusted run_current for X & Y
- Adjust Z-Endstop-Position
- Change invert on X & Y
- Added v0.2 CAD-File to .gitignore

13.08.2024
- Renamed comment
- Revert neopixel changes
- Adjusted neopixel color
- Adjusted position_endstop and max_temp

14.08.2024
- Enabled Line_Purge, Voron_Purge & Smart_Park
- Added KAMP for automatic Update

15.08.2024
- Changed chain_count for Neopixel
- Added better position after homing
- Added timelapse

14.09.2024
- Update temperatur for extruder and extrude distance
- Removed wait time and changed retract on print end

22.10.2024
- Moved Config folder to new folder Config_SKR-Pico
- Added config folder Config_Manta-M5P
- Added printer.cfg for Manta M5P after MCU change
- Removed uart_address

26.10.2024
- Added fan configuration
- Fixed neopixel pin

27.10.2024
- Added chamber thermistor

04.11.2024
- Fixed printer-section
- ReEnabled Sensorless homing

05.11.2024
- Added temperature sensors for mcu and host
- Added stepper config
- Fixed extruder

# Filelog
26.07.2024
- Added RPi_or_BTT-Pico_Mount.STL
- Added Images
- Added Image for MainsailOS to install
- Added display_mount.stl
- Added [a]_display_cover_hex_logo_x1.stl

27.07.2024
- Added rear_panel.3mf
- Added default printer.cfg for BTT SKR Pico

29.07.2024
- Added printfiles for handles
- Added new pictures
- Added KlipperScreen
- Added MFNano

30.07.2024
- Added ADXL Mount to printfiles

04.08.2024
- Removed MFNano
- Added Thermistormount in Chamber V0.2_NTC_10k_B3950_Mount.stl
- Added crowsnest.conf

06.08.2024
- Added waveshare-43-inch-display-mount-for-the-voron-v01-model_files

07.08.2024
- Added printfiles for LED-brackets, bottom hinge and Cam mount

14.08.2024
- Added moonraker.conf
- Added KAMP_Settings.cfg

15.08.2024
- Added diffuser print files
- Added print file for Front_Top_Right_Hinge_x1.stl

08.09.2024
- Added print files for Endstops

14.09.2024
- Added print files for 1515 end caps
- Added print files for Dragon Burner v8 with Orbiter v2
- Added print files for Dragon Burner v8 with Sherpa Mini

22.10.2024
- Added additional printfiles

26.10.2024
- Added printfiles for endstops

27.10.2024
- Added printfile for upper rear filament sensor

05.11.2024
- Added printfiles for foot corner
- Added printfiles for skirts