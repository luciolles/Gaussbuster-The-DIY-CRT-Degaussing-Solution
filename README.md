![Gaussbusters: The DIY CRT Degaussing Solution](https://www.arcadeinthebox.com/images/Gaussbusters_The_DIY_CRT_Degaussing_Solution.png)

# 📺 Gaussbusters: The DIY CRT Degaussing Solution
**Gaussbuster** is an open-source add-on card designed for CRT chassis that lack an integrated degaussing circuit. Whether you are refurbishing a budget arcade monitor or a specialty display, Gaussbuster helps eliminate purity issues and color splotches by providing a clean, reliable degaussing pulse every time you power on.

![Gaussbusters: The DIY CRT Degaussing Solution](https://www.arcadeinthebox.com/images/Gaussbusters-The-DIY-Degaussing-Solution.png)

# ⚡ Key Features
-   **Universal Compatibility:** Designed to interface with standard degaussing coils found on 14" to 29" tubes + all voltages (110 to 220V compatibility).
    -   **Automatic Triggering:** Clears the screen on cold boots using a standard PTC (Positive Temperature Coefficient) thermistor setup.
-   **Compact Footprint:** Small enough to be tucked away inside most arcade cabinets or monitor housings.

## 🛠 Hardware Overview
|Component                            |Function                         |
|-------------------------------|-----------------------------|
|PTC Thermistor MZ73#L7R|`Controls the AC current decay to the coil. Rated Voltage (V) 110/220`            |
|Fused Input|`Protects your chassis from overcurrent in case of component failure.`            |
|Conectors|`2 circuits JST LV connector (optional)`|


## 🚀 Getting Started
1.  **Fabrication:** Download the Gerbers from the `/hardware` folder and send them to your preferred PCB fabricator.
2. **BOM:** Refer to the `BOM.md` file for the exact part numbers.
3. **Installation:** * Mount the Gaussbuster card securely.
        -   Connect the AC input (Parallel to the main power switch).
        -   Connect the degaussing coil from the tube to the Gaussbuster output.     
        -   Power on and enjoy the "Thump."

## Files

 - Complete KiCad project available. Special thanks to the budy https://github.com/Guimli for designing this PCB.
 - README.md powered by [stackedit.io](https://stackedit.io/app#)
 - 3D models powered by [snapeda.com](https://www.snapeda.com/) & [Grabcad](https://grabcad.com/)
