![Gaussbusters: The DIY CRT Degaussing Solution](https://www.arcadeinthebox.com/images/Gaussbusters-The-DIY-Degaussing-Solution-PCB.png)

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
|PTC Thermistor MZ73#L7R|`Controls the AC current decay to the coil. Rated Voltage (V) 110/220.`            |
|Fused Input|`Protects your chassis from overcurrent in case of component failure.`            |
|Conectors|`2 pins TJC1 connector or B2P-JST VH`|


## 🚀 Getting Started
 -  **Fabrication:** Download the Gerber.zip from the folder and send them to your preferred PCB fabricator.
 - **BOM:** Refer to the `Detailed Bill of Material.md` file for the exact part numbers.
 - **Installation:** Mount the Gaussbuster card securely.
	 - Connect the AC input (Parallel to the main power switch). Use the socket needed. You can still solder your cables directly to the PCB.
	 - Connect the degaussing coil from the tube to the Gaussbuster output. 
	 - Power on and enjoy the "Thump."

## Detailed Bill of Materials  
  
| Item | Ref| Description | Qty | Unit Cost |  Supplier | Link |  
|---------:|------------------|---------:|------:|-----------:|----------|------|
| 1 | MZ73 7RM 7 Ω | 3 pins Demagnetization Resistor | 1 | €0.46 | Aliexpress | [Link](https://fr.aliexpress.com/item/1005011533510806.html?spm=a2g0o.order_list.order_list_main.177.3efd1802FvJe6m&gatewayAdapt=glo2fra#nav-description) | 
| 2 | 5x20mm | Fuse holder socket with transparent lid | 1 | €0.17 | Aliexpress | [Link](https://fr.aliexpress.com/item/1005001709479420.html?spm=a2g0o.order_list.order_list_main.171.3efd1802FvJe6m&gatewayAdapt=glo2fra) | 
| 3 | 250V 3A 5x20mm | Quick Blow Fuse | 1 | €0.05 | Aliexpress | - | 
| 4 | L Type | PCB Mounting Feet | 4 | €0.11 | Aliexpress | [Link](https://fr.aliexpress.com/item/1005006371432037.html?spm=a2g0o.cart.0.0.638c38dae05zSj&mp=1&pdp_npi=6%40dis%21EUR%21EUR%2021.58%21EUR%2010.79%21%21EUR%2010.79%21%21%21%402150af0417717215927244807e0d33%2112000053356723357%21ct%21FR%21169456376%21%211%210%21&gatewayAdapt=glo2fra) |
| 5 | TJC1 connector | Wire to Board Connectors | 2 | €0.35 | Aliexpress | [Link](https://fr.aliexpress.com/item/1005010480821488.html?spm=a2g0o.order_list.order_list_main.5.681f1802twsb9V&gatewayAdapt=glo2fra) |
| 6 | B2P-VH JST | 2 Pins JST Connector | 1 | €0.20 | Aliexpress | [Link](https://fr.aliexpress.com/item/1005008970632259.html?spm=a2g0o.productlist.main.15.bf89h41qh41qY3&algo_pvid=556589c5-18ae-49df-aa38-40b8b18111ef&algo_exp_id=556589c5-18ae-49df-aa38-40b8b18111ef-14&pdp_ext_f=%7B%22order%22%3A%22-1%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%212.00%212.00%21%21%2115.86%2115.86%21%402103849717718563994824194e4295%2112000047412221126%21sea%21FR%21169456376%21X%211%210%21n_tag%3A-29919%3Bd%3A496a9db1%3Bm03_new_user%3A-29895&curPageLogUid=4jFblET3wUsL&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008970632259%7C_p_origin_prod%3A) |  
| 7 | B3P-VH JST | 3 Pins JST Connector | 1 | €0.15 | Aliexpress | [Link](https://fr.aliexpress.com/item/1005008970632259.html?spm=a2g0o.productlist.main.15.bf89h41qh41qY3&algo_pvid=556589c5-18ae-49df-aa38-40b8b18111ef&algo_exp_id=556589c5-18ae-49df-aa38-40b8b18111ef-14&pdp_ext_f=%7B%22order%22%3A%22-1%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%212.00%212.00%21%21%2115.86%2115.86%21%402103849717718563994824194e4295%2112000047412221126%21sea%21FR%21169456376%21X%211%210%21n_tag%3A-29919%3Bd%3A496a9db1%3Bm03_new_user%3A-29895&curPageLogUid=4jFblET3wUsL&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008970632259%7C_p_origin_prod%3A) | 

## Files

 - Complete KiCad project available. Special thanks to the budy https://github.com/Guimli for designing this PCB.
 - README.md powered by [stackedit.io](https://stackedit.io/app#)
 - 3D models powered by [snapeda.com](https://www.snapeda.com/) & [Grabcad](https://grabcad.com/)
