## # Mintlify Office Printer Package Documentation

---

## About the Builder

Hi! I’m Maddie (GitHub/X: @maddiedreese).

I made this printer system so the Mintlify team can have a fun, reliable way to print incoming messages. If anything needs clarification or you want help extending the project, just let me know.

---

## Project Info

### Gmail Account

I had to set up a number of accounts for this, so I set up a Gmail account as well.

- **Email:** [mintlifyprinter@gmail.com](mailto:mintlifyprinter@gmail.com)  

- **Password:** Password1#

### GitHub Repository

The full printer project repo is currently hosted at:

- https://github.com/mintlify/mintlify-printer

**GitHub Login:**

- **Username:** mintlifyprinter  

- **Password:** Mprintpassword1

### Convex Database Project

This project uses a Convex database to log all messages.

When someone presses the Print Ticket button, Convex stores their message even if the printer is offline, out of paper, or temporarily unavailable. Nothing is lost.

**Convex Login:**

- Uses GitHub

### Netlify Frontend Deployment

The frontend is deployed at:

- https://message-mintlify.netlify.app

I recommend that Mintlify puts this behind a custom domain for long-term use.

**Netlify Login:**

- Uses GitHub

### Ngrok

Uses Ngrok for tunnel.

**Ngrok Login:**

- Uses GitHub

---

## Printer Details

- **Model:** NETUM Bluetooth Receipt Printer, Portable 58mm Mini Thermal POS Printer

- **Paper:** 57 mm x 30 mm thermal paper

- **Paper Included:** 5 rolls of phenol-free thermal receipt paper

- **Ink:** Not required, since it’s a thermal printer

- **Charging:**

  - Printer is labeled **A**

  - Use the included charger labeled **A**

- **Battery:** Advertised to last 7 days when fully charged; I have never had it die during use. I charged it up fully for you guys!

---

## Raspberry Pi Details

- **Model:** Raspberry Pi 4B

- **Program:** Fully configured on the included 32 GB SD card

- **Power:** Must be plugged in for the system to operate

  - Use the power cable labeled **B** (the Pi is labeled **B** as well)

- **Behavior:**

  - Once both the Pi and the printer are turned on, they automatically pair via Bluetooth

  - The printer program launches on boot

  - Messages begin printing as soon as both devices are on and connected

---

## Connecting the Pi to Mintlify Office WiFi

The only setup step required at the office is getting the Pi onto WiFi. After that, it runs on its own without needing peripherals.

### What You’ll Need for the First Setup

- A monitor with HDMI input  

  _(Many displays only support HDMI output, so this matters.)_

- A keyboard

- A mouse

  - Bluetooth peripherals are fine; plug the dongle into the Pi

### Steps

1. Plug the Raspberry Pi into power using cable **B**.

2. Connect the Pi to a monitor using one of the included **HD Out** cables.

3. Connect the keyboard and mouse.

4. Wait for the Raspberry Pi OS to boot.

5. Use the on-screen interface to connect to the Mintlify office WiFi.

6. Once WiFi is connected, you can disconnect the monitor, keyboard, and mouse.

   - The Pi will remember the WiFi network permanently.

### Login Credentials

- **Username:** mintlify

- **Password:** password

Feel free to change these during setup.

### After WiFi Setup

No peripherals are needed going forward.

The printer program and Bluetooth connection start automatically every time the Pi and printer are powered on.

---

## How to Use the Printer

1. Turn on the printer (labeled **A**).

2. Plug in the Raspberry Pi using cable **B**.

3. Wait about 10 seconds.

4. They will pair automatically.

5. Any messages submitted through the frontend will print out.

The system handles reconnections automatically.

---

## Items Included in the Package

### Main Hardware

- 1 NETUM Bluetooth receipt printer

- 1 Raspberry Pi 4B

- 1 32 GB SD card with OS and program installed

### Accessories and Components

- 5 rolls of phenol-free 57 mm x 30 mm thermal receipt paper

- 1 printer carrying case

- 1 printer charger labeled **A**

- 1 5V 3A power supply with on and off switch labeled **B**

- 2 HD Out cables

- 4 pure copper heat sinks

- 1 cooling fan

- 2 card readers

- 1 screwdriver

---

I hope you guys enjoy the printer! Feel free to reach out with any questions/comments.