# Motor-Optimization
FEMM and MATLAB based parameterized motor geometry simulation

Geometry parameterization works for inrunners, outrunners, concentrated windings, distributed/full pitch windings.

Features so far:
- Draws a section of the motor based on ~15 geometry parameters, with the rotor at a specified angle (init_geometry_2.m)
- Calculates torque (static) given specified d and q axis currents (assming 1 turn per slot) or current density (calc_torque.m)
- Calculates stator/rotor mass, rotor inertia, phase resistance, resistive losses (calc_phys_props.m)

Features to add:
- IPM rotor suport, maybe
- inductance calculations
- line voltage calculations
- losses at speed, maybe eventually
- optimization/parameter sweeping - getting close

![T-motor U8](https://github.com/bgkatz/Motor-Optimization/blob/master/walco_animation.gif)
![Walco Motor](https://github.com/bgkatz/Motor-Optimization/blob/master/u8_animation.gif)
