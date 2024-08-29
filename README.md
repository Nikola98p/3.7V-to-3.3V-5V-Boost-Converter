**Boost Converter with TPS63020DSJR**

This project is a simple boost converter designed to take a lithium battery input of 3.7V and provide an output of either 3.3V or 5V. The output voltage can be selected by adjusting the resistor in the circuit.
Schematic

**Components**

    U1: TPS63020DSJR
    R1: 180kΩ
    R2: 1MΩ (Select for 3.3V Output)
    R3: 1.6MΩ (Select for 5V Output)
    C1, C2: 10µF Capacitors
    C3, C4: 22µF Capacitors
    C7: 100nF Capacitor
    L1: 1.5µH Inductor

**How It Works**

This circuit uses the TPS63020DSJR buck-boost converter IC to step up the 3.7V input from a lithium battery to either 3.3V or 5V at the output. The resistors R2 and R3 are used to select the desired output voltage:

    3.3V Output: Use resistor R2 (1MΩ)
    5V Output: Use resistor R3 (1.6MΩ)

The circuit also includes capacitors for filtering and an inductor for energy storage and conversion efficiency.
Usage

    Connect the input (VIN) to a 3.7V lithium battery.
    Connect the output (VOUT) to your load.
    Select the desired output voltage by populating the corresponding resistor:
        3.3V: Use R2 (1MΩ)
        5V: Use R3 (1.6MΩ)
    Ensure that all components are correctly soldered and securely connected.
    Power up the circuit and measure the output voltage at TP3 (VOUT) to confirm the selected output.

**Testing Points**

    TP1: VIN (Input Voltage)
    TP2: Ground (GND)
    TP3: VOUT (Output Voltage)
    TP4: Additional Ground (GND)

**License**

This project is open-source and available under the MIT License. Feel free to modify and distribute it as per the license terms.
