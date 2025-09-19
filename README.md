# DC/DC Feedback Resistor Calculator

**Online calculator for determining optimal feedback resistor values in DC/DC converter circuits**

## 🔧 What it does

This web-based calculator helps engineers and electronics enthusiasts calculate the optimal feedback resistor values (R1 and R2) for DC/DC converter voltage divider networks. The tool automatically determines the resistor values needed to achieve a specific output voltage based on the reference voltage of your switching regulator.

## ⚡ Features

- **Auto Selection Mode**: Automatically finds the best resistor combination within a specified range
- **Single Resistor Mode**: Calculate the unknown resistor when one value is already known
- **Manual Input Mode**: Verify existing resistor combinations and see actual output voltage
- **Standard Resistor Series**: Supports both E24 (5% tolerance) and E96 (1% tolerance) standard values
- **Smart Value Display**: Automatically formats results in the most appropriate units (Ω, kΩ, MΩ)
- **Mobile Responsive**: Works perfectly on all devices - desktop, tablet, and mobile
- **Circuit Diagram**: Includes visual reference showing resistor placement
- **Real-time Calculation**: Instant results with error percentage display

## 🎯 Use Cases

- **Buck Converters** - Step-down DC/DC converters
- **Boost Converters** - Step-up DC/DC converters  
- **Linear Regulators** - Adjustable voltage regulators
- **Switching Power Supplies** - SMPS feedback network design
- **PWM Controllers** - Feedback loop design
- **Power Electronics Projects** - Voltage setting and regulation

## 📐 Formula

The calculator uses the standard voltage divider formula:
```
Vout = Vref × (1 + R1/R2)
```

Where:
- **Vout** - Desired output voltage
- **Vref** - Reference voltage (feedback pin voltage)
- **R1** - Upper resistor (between output and feedback pin)
- **R2** - Lower resistor (between feedback pin and ground)

## 🚀 How to Use

1. **Enter Reference Voltage**: Input your DC/DC converter's reference voltage (typically 0.6V - 1.25V)
2. **Set Target Output**: Specify your desired output voltage
3. **Choose Resistor Tolerance**: Select 1% (E96) or 5% (E24) series
4. **Select Calculation Mode**:
   - **Auto Selection**: Enter min/max resistor range for automatic optimization
   - **One Resistor**: Specify one known resistor value  
   - **Manual Input**: Enter both resistor values to verify the design
5. **Get Results**: View optimal resistor values with error percentage

## 🌐 Live Demo

**[Try the Calculator →](https://serbinov.github.io/Feedback-resistor-calculator-for-DC-DC/)**

## 💻 Technical Details

- **Pure HTML/CSS/JavaScript** - No dependencies, works offline
- **Responsive Design** - Optimized for all screen sizes
- **Standard Resistor Values** - Uses industry-standard E24 and E96 series
- **Error Calculation** - Shows percentage deviation from target voltage
- **Circuit Validation** - Prevents invalid input combinations

## 🛠️ Applications

Perfect for designing:
- Switching regulators (Buck, Boost, Buck-Boost)
- Linear voltage regulators (LM317, LM1117, etc.)
- DC/DC converter modules
- Power management circuits
- Battery charging circuits
- LED driver circuits

## 📁 Files

- `index.html` - Main calculator application (GitHub Pages entry point)
- `Feedback resistor calculator for DCDC_V1.html` - Original calculator file (backup)
- `image.png` - Circuit diagram showing resistor configuration
- `README.md` - This documentation file

## 🔧 Installation

No installation required! Simply:
1. Download the HTML file
2. Open in any modern web browser
3. Start calculating resistor values

Or visit the live version at: https://serbinov.github.io/Feedback-resistor-calculator-for-DC-DC/

## 📱 Browser Support

- ✅ Chrome (Desktop & Mobile)
- ✅ Firefox (Desktop & Mobile)  
- ✅ Safari (Desktop & Mobile)
- ✅ Edge (Desktop & Mobile)
- ✅ Opera (Desktop & Mobile)

## 🎨 Screenshots

The calculator features a clean, intuitive interface with:
- Clear input fields for all parameters
- Tabbed interface for different calculation modes
- Visual circuit diagram for reference
- Responsive design that works on all screen sizes

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 👨‍💻 Author

**Oleg Serbinov**
- Website: [serbinov.github.io](https://serbinov.github.io/)
- GitHub: [github.com/serbinov](https://github.com/serbinov)

## 📄 License

This project is open source and available under the MIT License.

## 🏷️ Keywords

`feedback resistor calculator` `DC/DC converter` `voltage divider` `power supply design` `switching regulator` `buck converter` `boost converter` `electronics calculator` `power electronics` `resistor calculator` `voltage regulator` `SMPS design` `PWM controller` `feedback network`