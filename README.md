# 📌 8-Bit Manchester Adder

## 🔬 Overview
This project presents the design and implementation of an **8-bit Manchester adder**, optimized for high-performance **accumulator applications**. The design employs a **hybrid logic approach** that balances **power, speed, and area efficiency**.

## 🛠 Features
✅ **CMOS logic** for basic gates (AND, OR, INVERTER)  
✅ **Pass Transistor Logic (PTL)** for XOR gates to reduce transistor count  
✅ **Transmission Gate Logic** for the carry circuit to optimize speed  
✅ **Post-layout simulations & power dissipation analysis**  
✅ **Compared against Brent-Kung, Kogge-Stone, Ladner-Fischer, and Han-Carlson adders**  

## 📖 Design Approach
### 🔹 Logic Style Selection
- **CMOS Logic**: Used for AND, OR, and INVERTER gates (robust & noise-immune)  
- **PTL XOR Gates**: Reduces transistor count while maintaining efficiency  
- **Transmission Gate Carry Chain**: Optimized for minimal delay & high-speed operation  

### 🔹 Performance Trade-offs
- **Logic depth**: 5 levels (comparable to Brent-Kung)  
- **Fanout**: 2 (optimal for performance)  
- **Area efficiency**: Comparable to Han-Carlson design  
- **Power Dissipation**: Analyzed pre-layout and post-layout  

⚙️ Tools & Technologies Used
📟 **Simulation & Verification**: Cadence Virtuoso  
💾 **Schematic & Layout**: Custom VLSI Design Flow  
📡 **Power & Performance Analysis**: Pre & Post Layout Simulations  

### 📖 Open the Report
Check out the **8_Bit_Manchester_Adder_Report.pdf** for a complete breakdown of the design and implementation.

📢 Contributions & Feedback
🚀 **Contributions are welcome!** If you have improvements or suggestions, feel free to fork the repository and submit a pull request.  

📩 For any queries or discussions, open an issue or reach out!  

