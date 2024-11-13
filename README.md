# Softcore IP Configuration with NIOS II on FPGA

## Overview

This project demonstrates the configuration of a Softcore IP with NIOS II on an FPGA platform using the Altera DE10-Lite board and Quartus Prime software. The project involved setting up a NIOS II processor, creating a custom Board Support Package (BSP), hardware abstraction layer (HAL), and custom drivers to optimize the performance of the processor. The softcore was programmed to execute a counting routine and enable UART communication for interaction with external devices.

## Project Highlights

- Configured a Softcore IP with NIOS II processor on Altera DE10-Lite FPGA.
- Developed and optimized the Board Support Package (BSP), hardware abstraction layer (HAL), and custom drivers.
- Programmed the softcore to execute a simple counting routine and communicate via UART.
- Integrated the softcore with external devices for testing and communication.
- Utilized Eclipse IDE for development, debugging, and testing of the softcore IP.

## Tools and Technologies Used

- **FPGA:** Altera DE10-Lite Board
- **Development Tools:** Quartus Prime, Eclipse IDE
- **Programming Languages:** C, Hardware Description Language (HDL)
- **Protocols:** UART communication
- **Softcore Processor:** NIOS II

## Setup & Installation

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/your-username/nios-ii-softcore-fpga.git
   ```
2. Install Quartus Prime and configure the DE10-Lite board.
3. Import the Quartus Prime project and configure the NIOS II processor.
4. Set up the Board Support Package (BSP), Hardware Abstraction Layer (HAL), and drivers.
5. Compile the project and load it onto the FPGA board using Quartus.
6. Use Eclipse IDE for programming and testing the softcore. Ensure you have the necessary NIOS II tools and libraries installed.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
