# Wireless Mesh Network Graph Analysis

Description

This repository contains the code and data for creating a synthetic graph representation of a  wireless mesh network. The graph generated simulates realistic scenarios based on various node and edge features. The aim of this project is to analyze and predict links within such a network using machine learning, specifically graph neural networks.

Node Features:

Max Bandwidth: Maximum data transmission rate the node can handle.
Current Usage: Current bandwidth usage of the node.
CPU Utilization: The proportion of CPU being utilized.
Memory: Percentage of memory utilization.
Battery: Remaining battery life as a percentage.
Buffer Size: Storage buffer size.
Terrain: Types of terrains like urban, forest, field, or mountain.
Operational Mode: Status of the node - idle, transmitting, or receiving.
Transmission Power: The power with which the node transmits signals.
Temperature: Current temperature of the node.

Edge Features:

Bandwidth: Data transmission rate of the link.
Latency: Time taken for data to be transmitted from source to destination.
SNR (Signal-to-Noise Ratio): Measure of signal strength relative to background noise.
BER (Bit Error Rate): The rate at which errors occur during data transmission.
Weather: Current weather condition affecting the link - rain, fog, clear, or snow.
Interference: External interferences affecting the link.
Traffic Load: Amount of data being transmitted over the link.

Objective:
To predict potential links within this network based on the aforementioned features using graph neural networks. This can aid in optimizing network configurations, predicting potential network failures, or scaling the network efficiently.
