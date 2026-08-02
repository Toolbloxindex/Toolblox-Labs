# Prototype 1 🚀

![Prototype 1 render](Prototype%20V1/Photos/3D%20Render.png)

Prototype 1 is a small model rocket project developed by ToolBlox Labs to explore aerodynamics, stability, and flight performance. The rocket was designed and simulated in OpenRocket, then manufactured using a Bambu Lab A1 Mini and assembled from multiple 3D-printed segments.

The goal wasn't to build the biggest or fastest rocket, but simply to understand how different design choices affect flight characteristics and to compare real-world launches with simulations.

The launch tests were successful and achieved values very close to those predicted by OpenRocket.



# Project goals

- Test the aerodynamic stability of a simple rocket design.
- Experiment with lightweight 3D-printed components.
- Learn how to use OpenRocket for flight simulations.
- Compare simulated and real-world performance.
- Design a modular rocket that can be printed in multiple pieces and assembled without glue.



# Specifications

| Parameter | Value |
|---|---:|
| Length | 44.4 cm |
| Diameter | 2.2 cm |
| Mass (without motor) | 85.8 g |
| Launch mass (with motor) | 102 g |
| Maximum altitude (apogee) | 82.9 m |
| Maximum velocity | 35.9 m/s |
| Mach number | 0.105 |
| Maximum acceleration | 66 m/s² |

## Recommended motor

Prototype 1 was designed around the **Klima B4-4** solid-fuel motor.

- Total impulse: **5.0 Ns**
- Average thrust: **4 N**

The motor thrust curves used in the simulations are included in this repository.

![Motor thrust curve](Prototype%20V1/Motor%20Thrust%20Graph/B4-4%20Graph.png)



# Payload

Prototype 1 was designed purely as an aerodynamic test platform and does not include a dedicated payload compartment.



# Software and tools

## Software

- OpenRocket (CAD)
- Bambu Studio (3D Printer Slicer Software)

## Hardware

- Bambu Lab A1 Mini
- ABS filament
- Klima B4-4 solid-fuel motor
- 9 V battery
- Electric igniters
- Jumper wires
- Two 10 m launch cables



# Repository structure

```text
Prototype V1/

├── Full Rocket/
│   └── Protoype V1.obj
│
├── Motor Thrust Graph/
│   ├── B4-4 Graph.png
│   └── B4-4 Graph.svg
│
├── Photos/
│   ├── 3D Render.png
│   ├── IMG_Launch1.jpg
│   ├── IMG_Launch2.jpg
│   ├── IMG_Launch2_Edited.png
│   └── IMG_Launch2_Unedited.PNG
│
├── Segmented Parts/
│   ├── Protoype 3 V1 Base (Fins).stl
│   ├── Protoype 3 V1 Cone.stl
│   ├── Protoype 3 V1 Outer Tube 1.stl
│   ├── Protoype 3 V1 Outer Tube 2.stl
│   └── Protoype 3 V1 Tube Coupler.stl
│
├── Simulations/
│   ├── Plotted Graph Simulation.png
│   └── Simulations Prototype V1.csv
│
├── LICENSE
└── README.md
```

---

# 3D render

![3D Render](Prototype%20V1/Photos/3D%20Render.png)



# Assembly instructions

The rocket was printed in multiple segments on a Bambu Lab A1 Mini using ABS filament.

All parts were assembled using friction-fit couplers; no glue was used.

## Printing

1. Print all rocket sections using the STL files in `Segmented Parts/`.
2. Print the couplers separately.
3. Remove any support material and clean the connections.

## Assembly

1. Insert the tube couplers into the corresponding sections.
2. Push the segments together until fully seated.
3. Ensure the body is straight and the joints are secure.
4. Insert the motor into the rear section.

The repository also contains the complete rocket model in OBJ format:

- `Full Rocket/Protoype V1.obj`



# Launch setup

Prototype 1 uses an electric ignition system.

## Components required

- Standard 9 V battery
- Electric igniter
- Nichrome resistance wire
- Jumper wires
- Two 10 m cables

## Launch procedure

1. Place the rocket vertically on the launch pad.
2. Install the motor and connect the igniter.
3. Connect the igniter to the jumper wires.
4. Walk at least 10 meters away from the rocket.
5. Connect the battery terminals to ignite the motor.
6. Observe the flight and recover the rocket after landing.



# Simulations

All simulations were performed in OpenRocket.

The repository includes:

- Flight simulation CSV data
- Flight graphs
- Motor thrust curves
- STL and OBJ models

## Predicted performance

- Apogee: **82.9 m**
- Maximum velocity: **35.9 m/s**
- Maximum acceleration: **66 m/s²**

## Flight simulation

![Flight simulation](Prototype%20V1/Simulations/Plotted%20Graph%20Simulation.png)

The raw simulation data can be found in:

- `Simulations/Simulations Prototype V1.csv`



# Launch photos

<table>
  <tr>
    <td align="center">
      <img src="Prototype%20V1/Photos/IMG_Launch1.jpg" width="250"><br>
      <sub>Launch 1</sub>
    </td>
    <td align="center">
      <img src="Prototype%20V1/Photos/IMG_Launch2.jpg" width="250"><br>
      <sub>Launch 2</sub>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="Prototype%20V1/Photos/IMG_Launch2_Edited.png" width="250"><br>
      <sub>Edited launch image</sub>
    </td>
    <td align="center">
      <img src="Prototype%20V1/Photos/IMG_Launch2_Unedited.jpg" width="250"><br>
      <sub>Original launch image</sub>
    </td>
  </tr>
</table>


# Test results

The test launches were successful and the measured values closely matched the OpenRocket simulations.

Prototype 1 proved to be stable throughout the flight and validated the aerodynamic assumptions used during the design process.



# Safety notes

This project was built for educational and experimental purposes only.

- Launch only in large, open areas.
- Keep spectators at a safe distance.
- Never launch in strong winds or dry conditions.
- Check the rocket structure before every flight.
- Never modify or disassemble rocket motors.
- Wait several minutes before approaching a rocket after a failed ignition.
- Wear eye protection while setting up the launch system.
- Keep a fire extinguisher nearby.
- Follow all local laws and regulations regarding model rocketry.

Solid-fuel motors contain combustible materials and should always be handled responsibly.



# Disclaimer

This repository documents Prototype 1 and its simulations. Anyone reproducing or modifying the project is responsible for complying with local laws and safety regulations.
