# trabalho2processamento
# 4-Bit Binary Adder with Arduino

This project demonstrates how to implement a 4-bit binary adder using an Arduino. It includes code for reading binary inputs, performing binary addition, and outputting the result and carry bit.

## Overview

The 4-bit binary adder adds two 4-bit binary numbers and outputs the result along with a carry bit. The implementation uses the Arduino platform to read binary inputs from specific pins, perform the addition, and output the result to other pins.

## Installation

1. **Hardware Setup**:
    - Arduino board (e.g., Arduino Uno)
    - Wires for connections
    - LEDs (optional) to observe output
    - Breadboard (optional)

2. **Software Setup**:
    - Arduino IDE: Download and install from [Arduino's official website](https://www.arduino.cc/en/software).

3. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/4-bit-binary-adder.git
    cd 4-bit-binary-adder
    ```

4. **Open the Sketch**:
    - Open the Arduino IDE.
    - Load the provided `4_bit_adder.ino` sketch from the cloned repository.

## Usage

### Basic Usage Example 1: Adding 1 + 1

1. **Wiring**:
    - Connect bit 0 of the first binary number (1) to pin 0.
    - Connect bit 0 of the second binary number (1) to pin 4.
    - Connect LEDs to pin 8 (sum bit 0) and pin 12 (carry bit).

2. **Run the Code**:
    - Upload the `4_bit_adder.ino` sketch to the Arduino board.
    - Set pin 0 to HIGH (1).
    - Set pin 4 to HIGH (1).
    - Observe pin 8 and pin 12: pin 8 should be LOW (0) and pin 12 should be HIGH (1).

### Basic Usage Example 2: Adding 1010 + 0101

1. **Wiring**:
    - Connect bit 3 of the first binary number (1) to pin 3.
    - Connect bit 1 of the first binary number (1) to pin 1.
    - Connect bit 2 of the second binary number (1) to pin 6.
    - Connect bit 0 of the second binary number (1) to pin 4.
    - Connect LEDs to pins 8 to 11 (sum bits) and pin 12 (carry bit).

2. **Run the Code**:
    - Upload the `4_bit_adder.ino` sketch to the Arduino board.
    - Set pin 3 to HIGH (1).
    - Set pin 1 to HIGH (1).
    - Set pin 6 to HIGH (1).
    - Set pin 4 to HIGH (1).
    - Observe pins 8 to 11 and pin 12: all sum bits should be HIGH (1), and the carry bit should be LOW (0).

## API

Refer to the [API Documentation](./docs/api/index.md) for detailed information about the functions and their usage.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING](./CONTRIBUTING.md) file for guidelines.
