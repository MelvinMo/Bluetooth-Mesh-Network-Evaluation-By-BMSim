# Bluetooth-Mesh-Network-Evaluation-By-BMSim
This repository contains the results report and analysis of experiments conducted using the BMSim tool, An Event-Driven Simulator for Performance Evaluation of Bluetooth Mesh Networks, which was originally available on [this GitHub page](https://github.com/BMSimulator/BMSim).

The goal was to simulate various Bluetooth Low Energy network scenarios and analyze the performance metrics recorded by BMSim codes.

I specified a random network topology with 49 nodes, with all nodes acting as both transmitters and receivers. Key configuration settings included a 30 ms scan window, a 30 ms scan interval, 0 retransmits for relays, 0 retransmits for endpoint packets, a packet reception ratio target of 100%, and a communication range of 11.6m. The experiments were carried out at BMSim.

Three different network scenarios were modeled for both grid and random topologies. For each scenario, the logs recorded by BMSim were processed to extract critical performance metrics like packet delivery ratio (PDR), average latency, and average energy consumption per node. Detailed node-level logs were also analyzed to study packet relay behavior.

The results are documented in the report file contained in this repository. Key results and insights include the impact of topology on overall PDR and latency, higher latency and energy consumption for nodes farther from the source, and identification of maximum burden nodes through packet tracing.
