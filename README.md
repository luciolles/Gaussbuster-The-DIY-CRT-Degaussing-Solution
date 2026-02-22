![Gaussbusters: The DIY CRT Degaussing Solution](https://www.arcadeinthebox.com/images/Gaussbusters_The_DIY_CRT_Degaussing_Solution.png)

# 📺 Gaussbusters: The DIY CRT Degaussing Solution
**Gaussbuster** is an open-source add-on card designed for CRT chassis that lack an integrated degaussing circuit. Whether you are refurbishing a budget arcade monitor or a specialty display, Gaussbuster helps eliminate purity issues and color splotches by providing a clean, reliable degaussing pulse every time you power on.

![Gaussbusters: The DIY CRT Degaussing Solution](https://www.arcadeinthebox.com/images/Gaussbusters-The-DIY-Degaussing-Solution.png)

# ⚡ Key Features
-   **Universal Compatibility:** Designed to interface with standard degaussing coils found on 14" to 29" tubes + all voltages (110 to 220V compatibility).
- **Automatic Triggering:** Clears the screen on cold boots using a standard PTC (Positive Temperature Coefficient) thermistor setup.
-   **Compact Footprint:** Small enough to be tucked away inside most arcade cabinets or monitor housings.

## 🛠 Hardware Overview
|Component                            |Function                         |
|-------------------------------|-----------------------------|
|PTC Thermistor MZ73#L7R|`Controls the AC current decay to the coil. Rated Voltage (V) 110/220`            |
|Fused Input|`Protects your chassis from overcurrent in case of component failure.`            |
|Conectors|`2 pins JST LV connector (optional)`|


## 🚀 Getting Started
 -  **Fabrication:** Download the Gerbers from the `/hardware` folder and send them to your preferred PCB fabricator.
 - **BOM:** Refer to the `BOM.md` file for the exact part numbers.
 - **Installation:** Mount the Gaussbuster card securely.
	 - Connect the AC input (Parallel to the main power switch).
	 - Connect the degaussing coil from the tube to the Gaussbuster output. 
	 - Power on and enjoy the "Thump."

## Detailed Bill of Materials  
  
| Item | Ref| Description | Qty | Unit Cost |  Supplier | Link |  
|---------:|------------------|---------:|------:|-----------:|----------|------|
| 1 | MZ73 7RM 7 Ω | 3 pins Demagnetization Resistor | 1 | €0.46 | Aliexpress | [Link](https://fr.aliexpress.com/item/1005011533510806.html?spm=a2g0o.order_list.order_list_main.177.3efd1802FvJe6m&gatewayAdapt=glo2fra#nav-description) | 
| 2 | 5x20mm | Fuse holder socket with transparent lid | 1 | €0.17 | Aliexpress | [Link](https://fr.aliexpress.com/item/1005001709479420.html?spm=a2g0o.order_list.order_list_main.171.3efd1802FvJe6m&gatewayAdapt=glo2fra) | 
| 3 | 250V 3A 5x20mm | Quick Blow Fuse | 1 | €0.05 | Aliexpress | - | 
| 4 | L Type | PCB Mounting Feet | 4 | €0.11 | Aliexpress | [Link](https://fr.aliexpress.com/item/1005006371432037.html?spm=a2g0o.cart.0.0.638c38dae05zSj&mp=1&pdp_npi=6%40dis%21EUR%21EUR%2021.58%21EUR%2010.79%21%21EUR%2010.79%21%21%21%402150af0417717215927244807e0d33%2112000053356723357%21ct%21FR%21169456376%21%211%210%21&gatewayAdapt=glo2fra) |  
---

## Files

 - Complete KiCad project available. Special thanks to the budy https://github.com/Guimli for designing this PCB.
 - README.md powered by [stackedit.io](https://stackedit.io/app#)
 - 3D models powered by [snapeda.com](https://www.snapeda.com/) & [Grabcad](https://grabcad.com/)
