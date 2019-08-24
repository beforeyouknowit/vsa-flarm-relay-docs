# Changelog

### 2019-08-24: Review & Configure eMPPT PoE Port Scheduling
- Configured `cron` on Pi 3 up on south ridge station; via `sudo crontab -e` and added `45 20 * * * sudo shutdown -h` to automatically safely power down at 9:45 PM local time.
- Configured SolarMAX MPPT PoE port to Relay Pi 3 to power on at 8:00 AM local, and power off at 8:00 PM local.
- Configured G3-Flex webcam to power on at 8:00 AM local, and power off at 8:00 PM local.
- Configured PowerBeam-5AC radio on remote station to power on at 8:00 AM local, and power off at 10:30 PM local.
- Changed relay Pi 3 `hostname` to `flarm-relay-pi` and rebooted.
- All systems have been functioning as expected for this past week; consistently reviewed by James and Ashley remotely.
- Suggestion of another mountaintop venture to reposition the solar panels; we'll see how we go with the scheduled overnight power-offs of high-drain devices on the station over this next week, and make decisions from next weekend's review.
- Challenges with G3-Flex webcam; PoE power being provided, but no link being established. Suspect physical disconnect or issue with 50ft CAT7 cable from brain/box to webcam. Will have to check on a tentative/upcoming mountaintop visit.
- Also discussed solar panel optimization; we're currently getting a consistent "dip" in power ouput around noon, and we suspect that a tree is casting a shadow during our peak "earning" time.

### 2019-08-17: Tower deployment expedition day!
- Added third 50ft CAT7 outdoor-grade ethernet cable to brain/box, in preparation to run to tree-trunk-deployment of FLARM antenna.
- Added 20ft 10AWG solar panel cables to brain/box, terminated internal bare wires in MC4 connectors.
- Team packed up station, tools, expedition equipment, multiple electric dirt bikes etc. into a pickup truck and trailer and headed up the mountain.
- Secondary (battery temperature monitoring) Raspberry Pi 3 not deployed as hoped, but will safe for next remote station deployment, and/or an update to first station in Spring 2020.
- Prepared hangar PowerBeam radio dish for alignment and maintained communicatinos on our airband VHF radios and Apple Messages.

### 2019-08-10: MPPT Upgrade
- Upgraded from previous MPPT charge controller to SunMAX SolarPoint MPPT charge controller.
- Removed previous wifi router, PoE injectors/adapters from remote station brain/box, tidied up internal cabling.
- Disassembled solar panel frame and prepared for deployment expedition.
- Modified tower Raspberry Pi configuration further; to disable Wifi, Bluetooth, enable `avahi` network discovery, general system software updates, etc.

### 2019-07-21: System Update
- System has been running next to the clubhouse, fully off-grid, for the past few weeks.
- Last bench-testing steps; pending the addition of a secondary Raspberry Pi and thermal sensors, deployed inside the battery brain/box.
- Involved club members on the project are anxious to deploy the relay on the mountaintop soon; we'll will send out an email to involved club members to organize an installation party. 
- Updated pole-mounted Raspberry Pi 3 software packages. Updated this documentation.