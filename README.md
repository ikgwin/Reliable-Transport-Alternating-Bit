# Reliable-Transport-Alternating-Bit Protocol

*University Project*

This repository contains an implementation of the Alternating Bit Protocol (ABP) for simulating reliable data transfer over a network. The code is adapted from the network emulator and Go-Back-N implementation by J.F. Kurose, customized specifically to demonstrate the functionality of the Alternating Bit Protocol.

Features
Alternating Bit Protocol: Simulates a simple yet effective protocol for reliable data transfer.
Error Handling: Includes mechanisms to handle packet loss and corruption.
Network Emulation: Utilizes a basic network emulator to mimic real-world network conditions.
Usage
Compilation: Compile the code using a C compiler (e.g., gcc).

bash
Copy code
gcc -o abp ABP.c
Execution: Run the executable with desired parameters.

bash
Copy code
./abp <emulator_host_address> <emulator_port> <sender_port> <receiver_port>
Notes: Ensure the emulator is running before executing the sender and receiver.
