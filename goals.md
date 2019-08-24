# VSA FLARM Relay Project Goals
- **Increase local glider pilot and regional powered pilot aircraft safety.**
- **Improve situational awareness of our club aircraft.**
- Create visibility of our club aircraft to on-site and off-site VSA club members and the public.

### Separation of Concerns:
- Receiving and decoding FLARM radio data.
- Retransmitting FLARM radio data to OGN.
- Updating and maintaining RTL/OGN relay daemon.
- Updating and maintaining the Raspberry Pi that the relay daemon runs on.
- Broadband IP communications link between VSA clubouse network and off-grid relay station on a nearby (~3.5km) mountain-top.
- Power management:
  - Displaying live and historical battery charge status.
  - Displaying live solar charge status.
  - Displaying live electrical load status.
  - Reading relay station subsystems power status.
  - Displaying relay station subsystem power scheduling.
  - Controlling relay station subsystem power, i.e. for our communications radio link, SDR/Raspberry Pi, and webcam.
- IP camera (ie. viewing visual weather conditions from mountain-top) for our gliding club members only.

### Future "Nice to Have" Features:
- Weather station; mast-mounted temperature, barometer, wind vane/impeller, humidity, precipitation, etc.
- One flat control plane for our communications network, Power-over-Ethernet remote control, IP camera DVR integration, etc.
- Displaying live and historical remote station battery temperature and health status.
