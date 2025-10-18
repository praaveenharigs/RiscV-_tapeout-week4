# RiscV-_tapeout-week4


A comprehensive guide to understanding CMOS transistor behavior, circuit analysis, and practical SPICE simulation using Sky130 technology.

---

### Installation

#### Clone the workshop repository:
```bash
git clone https://github.com/kunalg123/sky130CircuitDesignWorkshop.git
cd sky130CircuitDesignWorkshop
cd design
```
<img width="859" height="159" alt="image" src="https://github.com/user-attachments/assets/0b69ccfc-8baa-41db-99f7-740d8b9288c7" />

**Install ngspice (open-source SPICE simulator):**
```bash
sudo apt-get update
sudo apt-get install ngspice
```

#### Running Your First Simulation
**Execute a SPICE Netlist:**
```bash
ngspice day1_nfet_idvds_L2_W5.spice
```
**Generate Plots and for Saving Waveform Data**
```bash
plot -vdd#branch
write output.raw
wrdata output.csv -vdd
quit
less output.csv

```
<img width="877" height="680" alt="image" src="https://github.com/user-attachments/assets/a0aad573-45a8-4563-a1f7-f1d62cc4bf58" />


at desgin directory

```bash
vim day1_nfet_idvds_L2_W5.spice
```
<img width="1120" height="821" alt="image" src="https://github.com/user-attachments/assets/4434ebee-d1ea-4b7e-b970-a52aa20d34fa" />
