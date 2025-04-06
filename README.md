**Author :** Antoine Daniel

# Description

This repository is a model of a three-phase induction motor made during a student
project using MatLab and Simulink. The goal of this model is to perform
Park's transform and control motor's speed while learning the basics of Simulink. 

As said, this is a student project and errors may be present. Feel free to correct or enhance the project.

# Glossary

| Variable |             Name              |                         Unit                         |
|:--------:|:-----------------------------:|:----------------------------------------------------:|
| $B_{m}$  |     Viscosity coefficient     | $\mathrm{kg}\cdot\mathrm{m}^{^-1}\cdot\mathrm{s}^-1$ |
|   $f$    |        Grid frequency         |                    $\mathrm{Hz}$                     |
|   $J$    |    Rotor moment of inertia    |            $\mathrm{kg}\cdot\mathrm{m}^2$            |
| $L_{lr}$ |   Rotor leaking inductance    |                     $\mathrm{H}$                     |
| $L_{ls}$ |   Stator leaking inductance   |                     $\mathrm{H}$                     |
| $L_{mr}$ | Rotor magnetizing inductance  |                     $\mathrm{H}$                     |
| $L_{ms}$ | Stator Magnetizing inductance |                     $\mathrm{H}$                     |
| $L_{r}$  |       Rotor inductance        |                     $\mathrm{H}$                     |
| $L_{s}$  |       Stator inductance       |                     $\mathrm{H}$                     |
|   $P$    |        Number of poles        |                         $1$                          |
| $R_{r}$  |       Rotor resistance        |                  $\mathrm{\Omega}$                   |
| $R_{s}$  |       Stator resistance       |                  $\mathrm{\Omega}$                   |
| $V_{m}$  |    Peak voltage per phase     |                     $\mathrm{V}$                     |

# References

* [Mathwork – *abc to dq0, dq0 to abc*](https://fr.mathworks.com/help/sps/powersys/ref/abctodq0dq0toabc.html)
* [Wikipedia – *Direct-quadrature-zero transformation*](https://en.wikipedia.org/wiki/Direct-quadrature-zero_transformation)
* [MIT Libraries – *A Geometric Interpretation of Reference Frames and Transformations: dq0, Clarke, and Park*](https://dspace.mit.edu/bitstream/handle/1721.1/123557/Final_Submission__Open_Access.pdf?sequence=1&isAllowed=y)
* [Sandeep Kaler, Youtube – *abc-dq Transformation*](https://www.youtube.com/watch?v=VpXiSUVzVas)