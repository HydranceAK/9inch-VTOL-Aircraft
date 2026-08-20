**Autonomous VTOL Aircraft**

A custom-built, fully autonomous Vertical Take-Off and Landing (VTOL) aircraft designed for emergency medical supply transport, search and rescue operations, and early disaster identification. By blending multirotor hover capabilities with fixed-wing forward flight, this platform delivers critical supplies and real time monitoring to remote areas without needing runways or launch gear.

**Overview & Background**

In many rural or disaster-stricken regions, damaged roads and rough terrain completely cut people off from medical care. While some NGOs use mini planes or fixed-wing drones to bypass road blockades, those aircraft rely on catapult launchers, landing strips, or recovery nets. This project solves that hardware barrier by using a hybrid VTOL airframe. It lifts off vertically from small, unprepared spaces, transitions into efficient winged flight to cover distance quickly, and lands vertically right where it is needed. The goal is a straightforward, autonomous aerial transport system that gets running fast with basic setup instructions.

**Primary Applications**

_Emergency Medical Transport:_ Getting blood packs, vaccines, anti venom, and critical supplies to rural clinics or isolated patients where cars cannot reach.

_Search & Rescue Operations:_ Giving first responders and law enforcement a tool to spot missing people or scan dangerous sites from a safe distance.

_Disaster & Weather Monitoring:_ Running automated flight routes to flag early signs of wildfires or extreme weather before they hit populated areas.

**Engineering & Development Progress**

The last few months have been focused on component research and system testing: Propulsion Selection: Testing motor KV ratings, stator sizes, and prop pitch combinations to balance high thrust hover stability against low amp draw during forward cruise. Power Systems: Comparing battery capacity to weight ratios to stretch total flight time while carrying useful payloads. Frame Optimization: Designing 3D-printable airframe sections that stay rigid under load without adding dead weight. Autopilot Setup: Writing and testing transition logic so the flight controller handles the switch from hover to winged cruise smoothly and safely on pre set waypoints. Raspberry pi and AI Camera, along with TOF and optical flow sensors will be used for autonomous flight.

**Project Roadmap**

**Phase 1: Proof of Concept** — Built and flight-tested the initial 3D-printed quadcopter to test basic systems. (Done)

**Phase 2: Research & Component Selection** — Evaluated motor efficiencies, battery setups, frame designs, and flight controller options. (Done)

**Phase 3: Prototype Build & Transition Tuning** — Assemble the VTOL airframe, calibrate flight modes, and test autonomous transition routines. (In Progress)

**Phase 4: Field Testing **— Run mock delivery missions with payloads, test weather tracking, and run target identification trials.

**Phase 5: Deployment** — Offer the finished aircraft and build specs to NGOs, emergency response teams, and field organizations that need low-cost aerial logistics.

Specs:

2812 900kv Brushless Motor
21700 6s 2p 8000mah JP40 Custom battery pack
F722 Flight Controller (custom in work)
4in1 ESC
Buzzer
ELRS Receiver
DJI O4 Air Unit
DJI Goggle N3
Rasberry Pi 3 (upgrading to 5 soon)
Rasberry pi AI cam + Normal Cam
Rasiomaster pocket + ELRS module 500mw
4 TOF Sensors
25kg Tilt Servo 
9inch Triblade Propellers
SG90 Servos
25mm GPS 
Optical Flow Sensor

Note: Not all the CAD designs are my own. Some parts like motors, servos, and propellers were sources from GRABCAD as I didn't want to CAD these parts. 

<img width="1380" height="626" alt="image" src="https://github.com/user-attachments/assets/7266c5b6-4e37-4f6d-a766-289cd99e4b48" />
<img width="1066" height="541" alt="image" src="https://github.com/user-attachments/assets/c9554ccc-dff6-4074-aab1-a2d7ea7a1beb" />
<img width="1041" height="525" alt="image" src="https://github.com/user-attachments/assets/18695178-4598-47c4-83cd-518447d2e0f2" />
<img width="1598" height="426" alt="image" src="https://github.com/user-attachments/assets/aa8923fc-e268-4060-9d8d-02ee4186f9ed" />


