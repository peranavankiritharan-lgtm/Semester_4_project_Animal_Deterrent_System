# Semester_4_project_Animal_Deterrent_System
Developing an Automated Wildlife Deterrent System 

During Semester 4, I had the opportunity to collaborate on a group project focused on resolving a critical agricultural challenge. Protecting cultivation land from wildlife intrusion. We designed and built a lab scale Animal Deterrent System to detect and humanely deter elephants, peafowls, and wild boars.

**Key Learning Outcomes:**
End to End Sensor Development: Built, calibrated, and implemented signal conditioning circuits from scratch.

Data Acquisition (DAQ): Gained hands on experience interfacing physical sensors and actuators with software.

Control Automation: Constructed complex logic circuits in LabVIEW to handle multi sensor data fusion.

**Hardware Software Integration & Custom Sensor Design:**
Our solution relied on a multi sensor array to capture real time data, which was fed into LabVIEW via a National Instruments DAQ card to control actuators.

Custom IR Beam Breakers: We designed and built this sensor from scratch, integrating an averaging circuit for signal conditioning. By stacking three emitters and receivers vertically, we classified animals based on height. Placing parallel beams allowed us to determine the count and direction of entry. To handle overlapping entries, the system used varying voltage drops across the IR receiver to accurately increment the count.

Pyroelectric (PIR) Sensors: Used for thermal classification. The system differentiated between large and small thermal bodies by analyzing the amplitude of the output voltage.

Piezoelectric Discs: Deployed along the inner boundary to protect crops. Triggering this zone activated high intensity deterrent mechanisms.


**Control Logic & Actuators:**
Using LabVIEW, we engineered a multi tiered response logic. Based on the animal type and count, the system dynamically adjusted the intensity of a Strobing Light and triggered randomized acoustic deterrents via speakers. If the inner boundary was breached, the system automatically overrode to deploy maximum strobing intensity and continuous audio alarms until the PIR sensor confirmed the area was clear.


**Team members:**
Sethum Perera, 
Thimeshi Nipunika,  
Peranavan Kiritharan
