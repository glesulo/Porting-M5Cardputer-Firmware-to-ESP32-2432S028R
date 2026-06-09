# Rotary Valve Train Design Specification

## 1. Overview
This design specifies a high-performance rotary valve train for internal combustion engines, utilizing advanced sealing technologies and timing gear arrangements inspired by VAZTEC (ECORev), OHRV, and Coates Spherical Rotary Valve (CSRV) patents. The design specifically addresses the issue of combustion marks on the valve surface by implementing a pressure-actuated floating seal mechanism.

## 2. Core Components

### 2.1 Rotary Valve Shaft
*   **Geometry**: A rotating shaft featuring spherical or cylindrical valve sections positioned over each cylinder.
*   **Ports**: Integrated intake and exhaust passageways that rotate into registration with cylinder ports.
*   **Material**: High-strength alloy steel or ceramic-coated metal to withstand thermal stress.
*   **Operation**: Rotates at half the crankshaft speed (for 4-stroke cycles).

### 2.2 Pressure-Actuated Floating Seal Assembly
To prevent combustion gases from escaping into the clearance gap and causing "combustion marks," a floating seal assembly is utilized.

*   **Two-Piece Construction**:
    *   **Lower Receiving Ring**: Fixed within the cylinder head seat, featuring an annular groove.
    *   **Upper Contact Ring**: A ceramic/carbon composite ring that makes direct contact with the valve surface.
*   **Initial Loading**: Beveled springs (providing 1-4 ounces of force) maintain light contact between the contact ring and the valve surface during start-up and low-pressure phases.
*   **Sealing Mechanism (Blast Rings)**: One or more "blast rings" (similar to piston rings) are fitted around the outer periphery of the contact ring to seal against the wall of the receiving ring.
*   **Pressure Actuation**: Throughbores or communicating passageways allow high-pressure gases from the combustion chamber to enter the cavity behind the contact ring. During compression and power strokes, this pressure forces the contact ring firmly against the rotary valve, creating a gas-tight seal that scales with engine load.

### 2.3 Valve Timing Gear
*   **Ratio**: 2:1 gear reduction from the crankshaft to the rotary valve shaft.
*   **Drive Type**: Precision-cut timing gears (helical or spur) or a high-torque timing belt/chain system.
*   **Synchronization**: The gears ensure that the valve ports open and close in exact synchronization with the piston's position (Intake, Compression, Power, Exhaust).

## 3. Advanced Features

### 3.1 Oil-Free Operation
By utilizing ceramic composite contact rings and carbon-based lubricating inserts, the valve train can operate without traditional oil lubrication in the upper head assembly. This reduces oil consumption and eliminates carbon buildup associated with burnt oil.

### 3.2 Thermal Management
The split-head design (upper and lower halves) allows for integrated cooling jackets around the drum-accommodating cavities. The use of ceramic materials helps insulate the head and maintain structural integrity at high temperatures.

## 4. Design Diagram (Conceptual)

```text
       [ Rotary Valve Shaft ]
             /        \
      ______/ Port Port \______
     |                         |
     |   [ Upper Contact Ring ]<--- Ceramic/Carbon Interface
     |   [   Blast Rings      ]|
     |   [  Bevel Springs     ]|<--- Pressure-Actuated Cavity
     |___[ Lower Receiving R. ]|
     |_________Port____________|
               |
       ( Combustion Chamber )
```

## 5. Technical References
*   **VAZTEC ECORev**: Oil-free, rotating valvetrain eliminating reciprocating parts.
*   **Coates CSRV**: Spherical rotary valve with pressure-equalizing seals (US6789516B2).
*   **OHRV**: Overhead rotary valve arrangements for high-speed gas exchange.
