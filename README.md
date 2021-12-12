# CANBusPCB

Simple CAN Bus PCB designed for 8x CAN nodes, 2A power delivery and spring type connectors

![2D view](https://github.com/tkucic/CANBusPCB/blob/main/canbuspcb2d.png?raw=true)
![3D view](https://github.com/tkucic/CANBusPCB/blob/main/canbuspcb3d.png?raw=true)
![Circuit diagram](https://github.com/tkucic/CANBusPCB/blob/main/canbuspcbcircuit.png?raw=true)

This project started on a sunday when I got fed up daisy chaining my PLCs and devices over their CAN Bus ports. In case a device needs to be added or removed there is always a lot of work in rewiring the bus, moving the termination resistors etc. In this way, the PCB gives a lot of flexibility in doing so.

The PCB is also expandable from each end if more than 8 nodes are needed. You can also use the bus extention connectors as a node 0 and node 9.

The board also features 2A DC Power delivery bus if power over CAN is needed in the project.
