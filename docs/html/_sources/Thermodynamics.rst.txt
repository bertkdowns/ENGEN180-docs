Thermodynamics
==============

This continues on from the previous page on temperature. For most stuff in thermodynamics just do the math so that the units cancel correctly, and remember that W = J/s and kW = kJ/s.

Energy vs Power
---------------
Energy is represented by a capital :math:`Q` and measured in Joules or kJ. 

Power is represented by a lowercase :math:`q`. It is rate of energy usage, measured in joules/s or watts. 

Mass flow rates
---------------

Mass flow rates have the symbol :math:`\dot{m}`. They are measured in g/s or something similar. When you have an equation for energy, if you use a mass flow rate instead of a mass, it gives you power (W) instead of energy (J). You can easily see this with unit cancellation stuff.

Enthalpy
--------

Enthalpy is the amount of heat energy something has per gram of it. It is different to temperature - different types of material have different heat capacities, which means more enthalpy per degree of temperature.

Enthalply is represented as :math:`h`, in units kJ/g or kJ/kg.

.. math::
	
	Q = m h
	
	q = \dot{m} h 



Thermal Efficiency
------------------

Thermal efficiency is how much usable heat energy is generated. Calculated by:

.. math::
	
	\frac{Usable \ Energy}{Total\ Heat\ Energy}

Energy required & Gravity
-------------------------

.. math ::
	
	Q = m g \Delta z
	
Where:
	- Q is energy required
	- g is accelleration due to gravity - 9.81 m/s
	- :math:`\Delta` z is the change in height

Sensible & Latent heat
----------------------

Sensible heat is heat energy absorbed by something becoming hotter. remember :math:`Q = m c \Delta T` for sensible heat, where
	- c is the heat capacity of the thing - :math:`J/g.^{\circ}K`
	- :math:`\Delta` T is the change in temperature
	- m is mass

Latent heat is heat energy absorbed by something changing state - it takes energy to change from a liquid to a gas. When energy is being absorbed this way you don't see a change in temperature, you instead see a change in state. The amount of heat absorbed by the change in state is represented as :math:`\lambda` in units J/g
