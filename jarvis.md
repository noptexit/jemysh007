
1️⃣ Power Supply (Gigabyte 650W PSU) Connections

24-pin ATX → connects to motherboard main power.

8-pin EPS (CPU power) → connects near CPU socket for Intel i5‑14400F CPU.

6+2 PCIe connector(s) → connects to Gigabyte RTX 5060 GPU (OC version).

SATA power connectors → power HDDs, SSDs, and optionally the MSI RGB hub.

Molex (if any) → may be unused unless powering old devices.



---

2️⃣ Motherboard Headers (Gigabyte B760M G AX WiFi DDR5)

CPU & RAM

CPU_FAN header → connects AG400 CPU cooler fan.

DDR5 DIMM slots → 2 × 16 GB RAM sticks.


Case Fans

SYS_FAN1 → front 3 MSI fans or StackerFlow front 3.

SYS_FAN2 → top 2 MSI fans or StackerFlow top 2.

SYS_FAN3 → rear fan or StackerFlow rear 1.


ARGB / RGB

D_LED1 (5V ARGB) → all ARGB devices (front, top, rear fans, CPU cooler) via splitter.

12V RGB header → not used if only using ARGB fans.



---

3️⃣ Storage

M.2 NVMe SSD → plugs directly into M.2 slot, no cables needed.

4 × SATA HDDs → SATA data cables to motherboard, SATA power from PSU.



---

4️⃣ GPU (Gigabyte RTX 5060 8GB OC)

PCIe x16 slot → plugs into motherboard.

Power: 6+2 pin PCIe from PSU → GPU.



---

5️⃣ Case Fans & ARGB

If using stock MSI 6 fans with hub

Front 3 + Top 2 + Rear 1 fans → plug into MSI RGB hub.

MSI hub → powered via SATA power from PSU.

Lighting control → via hub + case button (fixed rainbow effects).

Fan speed control → mostly fixed or limited via hub (not motherboard-controlled).


If replacing all 6 fans with StackerFlow 3-in-1 ARGB fans

Front 3 fans: SYS_FAN1 + D_LED1 (first fan), rest wire-free daisy chain.

Top 2 fans: SYS_FAN2 + D_LED1 via splitter.

Rear 1 fan: SYS_FAN3 + D_LED1 via splitter.

CPU cooler: CPU_FAN + D_LED1 via splitter.

MSI hub → not used anymore.



---

6️⃣ PSU to Components Quick Map

24-pin ATX → motherboard

8-pin CPU EPS → CPU socket

PCIe 6+2 pin → GPU

SATA power → HDDs / SSD / MSI hub (if using stock fans)



---

7️⃣ Motherboard Fan & ARGB Quick Map

Component	Power Header	ARGB Header

CPU Cooler (AG400)	CPU_FAN	D_LED1 (via splitter)
Front 3 Fans	SYS_FAN1	D_LED1 (via splitter)
Top 2 Fans	SYS_FAN2	D_LED1 (via splitter)
Rear Fan	SYS_FAN3	D_LED1 (via splitter)


Only 1 ARGB header → all fans + CPU cooler share via splitter.



---

8️⃣ Notes on MSI RGB Hub

Needed only if stock fans are kept.

Controls all 6 stock fans’ lighting with case button.

Powered via SATA power from PSU.

If using StackerFlow fans → hub not needed at all.



---

✅ Summary

PSU provides power to motherboard, CPU, GPU, drives, and hub (if used).

Motherboard headers control fan speed (SYS_FAN) and ARGB lighting (D_LED1).

Splitters allow multiple ARGB devices on one header.

Replacing stock fans with StackerFlow makes wiring cleaner and motherboard fully controls speed + lighting.
