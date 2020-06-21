# PolarizationMapping
App for Tracing Laser Beam Polarization Thru Simple Optical System

Author: Gary Herrit

Start Date: ~April 2020.

This app is designed to predict how a laser beam's polarization will change as it pass through a simplified optical system. The program assumes that the incoming light beam is monochromatic. It also assumes that all optics and the parameters listed for the optics are given at the wavelength of interest.

The app uses Mueller Matrices to represent optical elements that have the potential to modify the beams polarization. The laser beam is represented by a Stokes Vector at each stage in the optical system.

Laser beams can be analyzed using their Stokes Vector to produce polar plots and 3d electric field plots. The electric field plots require Python and Matplotlib 3d to be installed on the users computer.
