# Network Security Labs

A collection of interactive, web-based visual tools designed to break down complex networking architecture and cybersecurity protocols into intuitive, step-by-step visual experiences.

## 📂 Featured Labs

### 1. OSI Layer Encapsulation & Decapsulation Engine
An interactive, state-driven simulation engine that visualizes how data traverses the OSI model. 

- **Data Encapsulation (L7 → L1):** Watch plaintext application data transform into an encrypted payload, append transport ports, network IP headers, and Data Link MAC frames before serializing into a raw physical bitstream.
- **Data Decapsulation (L1 → L7):** Track the receiving host as it ingests the bitstream, runs Frame Check Sequence (FCS) parity checks, strips protocol headers layer-by-layer, and delivers the reassembled message.

## 🚀 How to Run

Because these labs are built purely using standard frontend web technologies (HTML5, CSS3, vanilla JavaScript), they run entirely inside the browser sandbox. No compilation, terminal commands, or administrative privileges are required.

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/VK-learner/network-security-labs.git](https://github.com/VK-learner/network-security-labs.git)
