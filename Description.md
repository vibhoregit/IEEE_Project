# Automated FM Demodulator/Amplifier system
Most FM receivers cannot discriminate between meaningful data and noise. A typical FM demodulator thus outputs static noise in the absence of data. Human intervention becomes necessary to switch off the system to save power. The project aims at making a system that can discriminate between useful data and noise and accordingly let the data be passed on for further processing or block it. Design of such a circuit is preferred in Ananlog domain because of the following reasons:
1. The entire process of discriminating data from noise is relatively simple in analog domain.
2. Arbitrary precision (limited by the channel noise) can be achieved.
3. Integration of such a system with any class of amplifier is simpler (no need for DACs).

### Block diagram representation of the system.
![block_diagram](https://github.com/vibhoregit/IEEE_Project/blob/master/Block_Diagram.png?raw=true)

### Application
Such systems can be deployed in radio systems of all vehicles with the demodulator tuned to frequencies outside commercial radio. This frequencu can be used to transmit emergency messages in scenarios like creating urgent green corridors or fire fighting where in the ambulance/fire truck could transmit emergency messages in a range of 4-5 Kilometres transmitting the path that needs to be cleared off. The system will override any playback and force the amplifier to amplify the emergency signal. 