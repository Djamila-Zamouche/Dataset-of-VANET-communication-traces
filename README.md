# Dataset-of-VANET-communication-traces

The dataset contains traces of vehicular communications under disturbances in VANET. The dataset is generated from simulation of a real traffic scenario using a compound of two software, the vehicular mobility generator SUMO (Simulation of Urban Mobility) and NS-3 (Network Simulator v. 3.29). We have generated the mobility scenario using SUMO combined with OpenStreetMap by simulating a traffic area of 25km in the Bologna city (Italy). The resulting mobility traces file is then considered as input file to the NS-3. The communications between the vehicles is designed on the NS-3. The VANET environment consists of 300 vehicles, which including 15 malicious ones conducting malware activities. The generation process for these abnormal behaviors is increases and decreases the number and the rate of packets, and the communication duration between source and destination. The data transmission rate is 6Mbps, and packet size is set as 254 bytes. The simulation duration is of 20000 s.

The dataset has the following fields:

•	Start transmission: Time when the BSMs exchange will start.
•	End transmission: Time when the BSMs exchange will end.
•	Period: Time duration of BSM exchange.
•	Packets number: estimated number of packets to send during the requested session.
•	Debit: estimated rate of packet transmission per second.
•	Sender Stopping Distance: braking distance of sender.
•	Receiver Stopping Distance: braking distance of receiver.
•	Actual Distance: distance in meters between sender and receiver.



