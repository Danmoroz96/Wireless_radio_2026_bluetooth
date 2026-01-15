# Wireless_radio_2026_bluetooth
The goal of this assignment is to explore and analyze cellular network parameters (LTE/NR) using a smartphone's Service Mode. This experiment focuses on understanding how physical environments and signal metrics like RSRP and SINR affect network performance and stability.
2. Methodology & Setup
Device: Samsung Smartphone (Dual SIM Model)

Carrier: Elisa (PLMN 244-05)

Tools: Samsung Service Mode (*#0011#)

Location: Indoor environment in Finland.

Test Date: January 14, 2026.


3. Collected Measurement Data
The following data was captured during a live LTE-Advanced (4G+) session. The results are shown in Excel file.

4. Technical Analysis
Signal Strength vs. Quality
While the RSRP (-88 dBm) indicates a "Good" signal strength, the SNR (Signal-to-Noise Ratio) of 3-6 dB is relatively low. This suggests that while the phone "hears" the tower clearly, there is significant background noise or interference from other cells.

Carrier Aggregation (CA)
The device is utilizing Carrier Aggregation by combining Band 3 and Band 1. This effectively doubles the available bandwidth, which is critical for maintaining high data throughput even when individual signal quality is sub-optimal.

Environmental Impact
Indoor Obstructions: The measurements were taken indoors. The transition from -88 dBm to -92 dBm likely reflects moving away from a window or behind a wall.

Modulation Shifts: In the screenshots, the Uplink modulation shifted between QPSK and 64QAM. This confirms that the network dynamically adjusts its complexity based on real-time signal stability.

5. Conclusions
The experiment demonstrates that high signal strength (bars) does not always equate to high signal quality (SNR). In this specific test, the network reliability is maintained through Carrier Aggregation, but the data speed is likely capped by the low SNR values. To improve performance, reducing physical obstructions between the device and the tower is necessary.

