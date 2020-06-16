Temperature
===========

R value
-------

The R value, ( :math:`R` ) represents the "thermal resistance" per unit area. It's additive, so if you have  2 layers of insulation, you can add their R values to get the overall R value. Units are :math:`\frac{m^2{\cdot}K^{\circ}}{}`

Heat Transfer Coefficient
-------------------------

The inverse of the R value (:math:`1/R`).  Represented as a lowercase :math:`h`. Units are :math:`\frac{W}{m^2{\cdot}K^{\circ}}`

Thermal Conductivity
--------------------

A measure of a material's ability to conduct heat. Represented as the letter :math:`k`. Units are :math:`\frac{W}{m{\cdot}K^{\circ}}`

It is related to thermal resistance by the equation :math:`R=L/k`, where L is the length (thickness) of the material.

Heat Transfer
-------------

The rate of heat transfer can be measured in Watts (Joules per second).

The rate of heat transfer from one place to another by convection through a material is:

:math:`q=hA(T_S - T_F)` where:

	- h is the heat transfer coefficient
	- A is the area between the two places where heat transfer is taking place
	- :math:`T_S` and :math:`T_F` are the temperatures (in celcius or kelvin) of the two places.

Or:

:math:`q=\frac{kA(T_1 - T_2)}{L}` where:

	- k is the thermal conductivity
	- L is the length (thickness) of the thing seperating the two areas.

Heat Transfer through Radiation
-------------------------------

:math:`q=\epsilon \sigma A T_s^4` where:

	- :math:`\epsilon` is the surface emissitivity (0 < :math:`\epsilon` < 1, 1 being black, shinier as approaching 0)
	- :math:`\sigma` is the Stefan-Botzmann constant (:math:`5.67 \times 10^{-8} W/m^2K^4`)
	- :math:`A` is the cross sectional area
	- :math:`T_s` is the surface temprature of the solid

Ideal Gas Law
-------------

:math:`PV = nR_uT` where:
	- P is pressure (Pa)
	- V is volume (cubic metres)
	- T is Temperature (Kelvin)
	- n is the amount of "ideal" gas (mols)
	- :math:`R_u` is the ideal gas constant (8.314 J/mol K)



