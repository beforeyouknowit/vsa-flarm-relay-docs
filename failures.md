# Failure Modes & Error Handling

Issues encountered so far; solutions & procedures pending:

---

!> **Problem:** Brain/box v1.0 MPPT charge controller's serial data is only consumable in proprietary encoding format. (Not sure if decoding library is available from the manufacturer.)
> **Solution:** Poll/debug RS485 serial data and develop our own (minimalistic) serial polling, after deploying the system on the mountain top, via SSH'ing in from the clubhouse. (If possible, securely VPN tunnel into the clubhouse network from off-site.)

---

!> **Problem:** OGN Raspberry Pi computer crashes; startup sequence failure, (i.e. can’t SSH in!)
> **Solution:** Defer to secondary brain/box Raspberry Pi for diagnostics and log inspection, otherwise; visit the mountain-top relay station, inspect and repair.

---

!> **Problem:** Solar charge controller failure.
> **Solution:** If the station is entirely offline, visit the mountain-top relay station; inspect and repair.

---

!> **Problem:** Power bus over- or under-voltage.
> **Solution:** Remotely log into MPPT charge controller; inspect logs. Compare with temperature sensor data from brain/box Raspberry Pi database.

---

!> **Problem:** Battery, charge controller, or brain/box internal over-temperature.
> **Solution:** Preempt with white brain/box covering, burying underneath larger thermal mass on-site. If still over-temp, 

---

!> **Problem:** Mast component over-temperature.
> **Solution:** Shutdown of the mast Raspberry Pi and SDR module for a few hours; i.e. disabling OGN to preserve the life of the components. If necessary, visit the mountain-top relay station; inspect and replace Pi if failed.

---

!> **Problem:** Battery failure.
> **Solution:** Visit the mountain-top relay station; inspect and repair.

--- 

!> **Problem:** PowerBeam (long-range wifi radio link) failure.
> **Solution:** Visit the mountain-top relay station; inspect and repair.

---

!> **Problem:** LAN relay failure.
> **Solution:** Visit the mountain-top relay station; inspect and repair.

---

!> **Problem:** Fire.
> **Solution:** Call 9-1-1 and report the fire, possibly electrical. Visit the mountain-top relay station; inspect and repair.

---

!> **Problem:** Physical damage, i.e. electrical or electrostatic discharge, data or power cabling, mast or support structure failure, animal disturbances or damage.
> **Solution:** Visit the mountain-top relay station; inspect and repair.

---

!> **Problem:** Theft / vandalism.
> **Solution:** Deploy vandal-resistant key locks on brain/box; cut-resistant physical security guy wire anchored to rock pinion.

---