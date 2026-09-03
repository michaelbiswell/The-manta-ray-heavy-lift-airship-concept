The Manta Ray Heavy-Lift Airship Concept

A Structural-Photovoltaic, Multi-Tube, Hybrid-Electric LTA Architecture
Author: Michael Biswell. Zenodo 10.5281/zenodo.21104807 01/07/2026

Date: 2026 Preprint:

1.	Introduction
Lighter-than-air vehicles have historically suffered from structural fragility, crosswind vulnerability, and limited power availability. Modern materials, electric propulsion, and distributed sensing now enable a fundamentally different class of airship. This work proposes a manta ray-inspired heavy-lift platform optimized for stability, safety, and energy autonomy. The concept integrates aerodynamic shaping, multi-cell buoyancy, structural energy storage, and hybrid electric propulsion into a unified architecture.

2.	Aerodynamic Rationale
2.1	Manta Ray Hull Geometry
The airship employs a broad, flattened planform with no vertical tail surfaces. This geometry reduces side area, improving crosswind stability and minimizing ground-handling risk. The hull acts as a lifting body at forward velocity, contributing aerodynamic lift and reducing required buoyant lift.

2.2	Venturi Tunnel Stabilization
Twin cargo pods mounted beneath the hull form a central airflow channel. This creates a venturi effect that naturally damps yaw and roll disturbances. The configuration reduces reliance on mechanical control surfaces.

3.	Structural Architecture
3.1	Multi-Tube Buoyancy System
The hull interior contains multiple long, inflatable tubes arranged longitudinally. Each tube is divided into forward and aft chambers. This architecture provides:

•	puncture isolation
•	shape stability
•	trim control
 
•	structural reinforcement

3.2	Pneumatic Structural Reinforcement
Pressurized tubes act as pneumatic beams, reducing the need for heavy composite framing. Materials include BoPET/polyurethane laminates with Vectran or Kevlar reinforcement.

3.3	Chamber Segmentation
Each tube contains:

•	a helium chamber
•	an internal air ballonet
•	fore and aft segmentation

This enables static trim control without thrust expenditure.

4.	Buoyancy, Trim, and Gas Management
4.1	Closed-Loop Pneumatic Manifold
A central carbon-fibre manifold connects all chambers via electronically actuated selector valves. The system supports:

•	helium transfer
•	ballonet air compression
•	zone isolation
•	emergency sealing

4.2	Normally-Closed Isolation Valves
Each chamber includes a normally-closed valve that mechanically seals during power loss or rupture detection, preventing cross-bleed.

4.3	Trim Control Logic
Pitch control is achieved by shifting helium or air between fore and aft chambers. This adjusts the centre of buoyancy without aerodynamic surfaces.

5.	Power and Propulsion
5.1	Structural Photovoltaic Skin
The upper hull surface is a load-bearing photovoltaic composite. It provides primary energy input and eliminates the mass of traditional solar panel mounting structures.
 
5.2	Rim-Driven Electric Impellers
Propulsion is provided by enclosed, magnetically driven impellers with vectoring exhausts. Benefits include:

•	no gearboxes
•	reduced mechanical complexity
•	high manoeuvrability
•	zero-speed control

5.3	Hybrid DC Electrical Topology
The system operates on an 800–1200 V high-voltage DC bus. Inputs include:

•	photovoltaic skin
•	standby hydrogen fuel cell or microturbine
•	structural supercapacitors
•	main battery buffer

5.4	Supercapacitor Integration
Graphene-based structural supercapacitors buffer transient loads, enabling:

•	gust response
•	thrust-vector spikes
•	generator ramp-up smoothing

6.	Electrical Architecture
6.1	High-Voltage DC Bus
All major subsystems connect to a central HVDC bus via MPPT controllers, rectifiers, and buck-boost converters.

6.2	Capacitor-Battery Hybrid Buffer
Supercapacitors supply instantaneous power; batteries or fuel cells supply long-duration energy.

6.3	Emergency Power Routing
A dedicated 24 V avionics bus remains isolated from propulsion loads, ensuring cockpit and sensor continuity.

7.	Avionics and Control
 
7.1	Sensor Matrix
The airship uses distributed sensing including:

•	fibre-optic Bragg grating strain sensors
•	ultrasonic helium purity sensors
•	differential pressure transducers
•	dual IMUs at nose, tail, and pods

7.2	Fly-By-Wire Architecture
A triple-modular-redundant (TMR) flight computer integrates:

1.	Fault Detection, Isolation, and Recovery (FDIR)
2.	Dynamic Trim Engine
3.	Thrust Vectoring Controller

7.3	Unified Control Logic
The system blends slow pneumatic trim adjustments with rapid thrust-vector corrections to maintain stability under varying loads and wind conditions.

8.	Safety and Failure Modes
8.1	Rupture Isolation
If a chamber loses pressure rapidly, the FDIR system:

•	isolates the chamber
•	seals valves
•	redistributes gas
•	alerts the cockpit

8.2	Overpressure Protection
Mechanical relief valves vent expanding gas into emergency bladders during rapid ascent.

8.3	Vacuum Prevention
Ballonet compressors inflate chambers during rapid descent to maintain hull rigidity.

9.	Operational Use Cases
The airship is intended for:
 
•	heavy-lift logistics (50–100 tonnes)
•	remote infrastructure support
•	disaster relief
•	low-emission cargo transport

Two propulsion configurations are proposed:

•	two-drive for 50-tonne class
•	four-drive for 100-tonne class























10.	Conclusion
This paper presents a unified heavy-lift airship architecture that integrates aerodynamic shaping, multi-cell buoyancy, hybrid electric propulsion, and advanced control systems. The manta ray configuration addresses historical LTA limitations and leverages modern materials and energy systems to create a resilient, efficient, and safe cargo platform. This preprint establishes a foundation for further development, simulation, and prototyping.

Appendix A — Component Weight Budget (Preliminary Framework)
(You can paste this into a spreadsheet)
 
Component	Estimated Mass (kg)	Notes
Structural PV Skin	TBD	Depends on area & laminate thickness
Multi-Tube Helium Cells	TBD	Per-tube mass × number of tubes
Ballonet System	TBD	Compressors, bladders
Rim-Driven Impellers	TBD	2- or 4-drive configuration
Supercapacitor Structure	TBD	Integrated into frame
HVDC Bus & Power Electronics	TBD	MPPT, converters
Fuel Cell / Microturbine	TBD	Redundancy system
Avionics & Sensors	TBD	TMR computers, IMUs, FBG sensors
Cargo Pods	TBD	Structural composite pods
Cockpit Module	TBD	Crew systems
Appendix B — Standard Takeoff Checklist (Pilot + Automation)
Pre-Flight
•	Verify chamber pressures (fore & aft)
•	Confirm helium purity sensors nominal
•	Check ballonet compressor readiness
•	Verify HVDC bus voltage
•	Confirm supercapacitor charge state
•	Run FDIR self-test
•	Confirm thrust-vector actuators free

Trim & Lift Preparation
•	Set neutral trim (fore/aft equalization)
•	Inflate ballonets to ground-pressure baseline
•	Engage low-power hover thrust

Takeoff Sequence
•	Automation stabilizes pitch via trim engine
•	Pilot increases thrust to lift threshold
•	EM jets vector downward for vertical assist
•	Airship ascends to 50–100 m AGL
•	Transition to forward thrust
•	Trim engine shifts buoyancy for cruise attitude
 
References
1.	NASA Structural Supercapacitor Research
2.	Hybrid Electric Propulsion Studies (various)
3.	LTA Safety and Buoyancy Management Literature
4.	Photovoltaic Composite Materials Research
