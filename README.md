# Networking & Cybersecurity Portfolio

A centralized repository containing interactive web simulations, packet crafting scripts, and security tools designed to explore low-level networking mechanics, protocol behavior, and cybersecurity principles.

## 📂 Repository Structure

- **`01-osi-encapsulation-engine/`**: An interactive, web-based visual simulation engine illustrating step-by-step data encapsulation (L7 down to L1) and decapsulation (L1 up to L7) across the OSI model.
- **`02-packet-crafting/`**: Python scripts utilizing libraries like Scapy to manually build, manipulate, and inject raw network frames and custom packets.
- **`03-network-scanners/`**: Implementation of socket-based scanning utilities, including stealth TCP SYN port scanners to assess infrastructure states.
- **`04-cryptography-labs/`**: Practical implementations of cryptographic protocols (like AES-GCM or RSA) demonstrating secure data transit and Presentation Layer security.

## 🚀 Getting Started

### Interactive Simulations
To run the web-based engines (e.g., the OSI simulation):
1. Navigate to the specific directory.
2. Open the `index.html` file directly in any modern web browser.

### Script Execution
To execute the Python networking and security utilities:
1. Ensure you have Python 3.x installed.
2. Install required dependencies:
   ```bash
   pip install scapy
