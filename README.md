
I successfully implemented a UART transceiver on the DE2-115 FPGA board. The DE2-115, a Field-Programmable Gate Array (FPGA), offers flexibility in a wide range of applications, including digital signal processing, hardware acceleration, and prototyping digital systems. Using the UART (Universal Asynchronous Receiver-Transmitter) protocol, I facilitated serial communication between electronic devices, where data is transmitted asynchronously without a shared clock signal. Instead, start and stop bits were used to frame data packets, and the baud rate determined the speed of data transfer.

For this project, I designed a UART module using Verilog, which handled parallel-to-serial conversion for transmission and serial-to-parallel conversion for reception. I also developed a testbench to simulate the UART module’s behavior before programming the FPGA with the final design.

Physically, I connected the Tx (transmit) and Rx (receive) pins of the DE2-115 board to the corresponding pins of the device I was communicating with, ensuring that the baud rates between the transmitter and receiver matched to guarantee reliable data transfer

#### UART Block Diagram:
<img src="https://github.com/Erandee-Jayathilaka/UART_Implementation---Verilog/blob/main/UART/simulation_results/Transceiver_Schematic.png" alt="Transmitter simulation" width="1000" height="500">

#### Simulation Waveforms:
<img src="https://github.com/Erandee-Jayathilaka/UART_Implementation---Verilog/blob/main/UART/simulation_results/tx.png" alt="Transmitter simulation" width="1000" height="500">
<img src="https://github.com/Erandee-Jayathilaka/UART_Implementation---Verilog/blob/main/UART/simulation_results/Rx.png" alt="Transmitter simulation" width="1000" height="500">
