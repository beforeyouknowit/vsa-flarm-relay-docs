# Failure Modes & Error Handling

Issues encountered so far; solutions & procedures pending:

---

**Problem:** SDR radio dongle not able to communicate with Raspberry Pi over proposed USB-over-ethernet dongle/extender link.

**Solution:** Remove USB-over-ethernet dongles from system; resolve to deploy Raspberry Pi in radio mast box.

---

**Problem:** MPPT charge controller serial data (RS485 via RJ45 jack) only available via wifi dongle in host mode; not available in client wifi mode.

**Solution:** Remove wifi dongle from MPPT controller; deploy FTDI cable to RS485 "console" jack; connect to secondary (battery/brain box) Raspberry Pi.

---

**Problem:** MPPT charge controller serial data in proprietary encoding format; not sure if decoding library is available from manufacturer.

**Solution:** Poll/debug RS485 serial data and develop our own (minimalistic) serial polling, after deploying the system on the mountain top, via SSH'ing in from the clubhouse. (Ideally we'd have a way to VPN into the clubhouse from off-site!)

---