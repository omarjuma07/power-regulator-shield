# 12V to 5V DC-DC Power Regulator Shield

A custom-engineered 2-layer Arduino shield designed to step down a 12V DC input to a regulated 5V rail capable of driving high-power 10W surface-mount LEDs. 

<img width="1810" height="670" alt="image" src="https://github.com/user-attachments/assets/9fab0700-4c00-42d9-8f20-b1645386c98b" />


## Engineering Specifications

* **Topology:** Synchronous Step-Down (Buck) Converter utilizing the **TPS562200** regulator[cite: 15].
* **Board Stackup:** 2-layer FR-4 (60-mil core, 62-mil total thickness, 1oz copper).
* **Power Output:** Regulated 5V rail powering dual 10W SMD LEDs (MKRAWT series)[cite: 15].
* **Design Rules:** 10-mil minimum trace/space constraints, customized direct-connect thermal reliefs on high-current power pads to minimize resistive losses.
* **Manufacturing Compliance:** Fabricated per **IPC-6012A Class 2**, incorporating custom 3-mil hole tolerances on high-current power input pads.

<img width="1372" height="924" alt="image" src="https://github.com/user-attachments/assets/575d6c08-ab16-49b5-a72c-47427ca0648e" />


## Project Structure & Deliverables

* **Source Files:** Altium Designer schematic capture (`.SchDoc`) and PCB layout (`.PcbDoc`)[cite: 11].
* **Production Package:** Automated OutJob exports including Gerber files, ODB++, NC Drill, and Pick-and-Place data[cite: 11].
* **Documentation:** Draftsman-generated 2D fabrication and assembly blueprints complete with custom notes and drill tables[cite: 11].
