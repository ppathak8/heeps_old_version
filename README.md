# HEEPS: High-contrast End-to-end ELT Performance Simulator

					    )               (      (     
					 ( /(               )\ )   )\ )  
					 )\())  (     (    (()/(  (()/(  
					((_)\   )\    )\    /(_))  /(_)) 
					 _((_) ((_)  ((_)  (_))   (_))   
					| || | | __| | __| | _ \  / __|  
					| __ | | _|  | _|  |  _/  \__ \  
					|_||_| |___| |___| |_|    |___/    



## Overview
HEEPS is coronagraphic PSF simulator mostly geared towards simulating the performace high-contrast imging mode of ELT instrument "METIS". 
[![N|Solid](https://i2.wp.com/metis.strw.leidenuniv.nl/wp-content/uploads/2017/11/logo_with_text.png?resize=300%2C238)](https://i2.wp.com/metis.strw.leidenuniv.nl/wp-content/uploads/2017/11/logo_with_text.png?resize=300%2C238)

Currently simulator includes three coronagraphs:
- Classical vortex
- Ring apodized vortex coronagraph (RAVC)
- Apodizing phase plate (APP)

For technical document about the simulator see: https://www.spiedigitallibrary.org/conference-proceedings-of-spie/9909/1/End-to-end-simulations-of-the-E-ELTMETIS-coronagraphs/10.1117/12.2233444.short

## Required libraries

1. 'PROPER' for simulating coronagraphic PFS's (link: https://sourceforge.net/projects/proper-library/?source=navbar).
2. 'VIP' for processing ADI processing and generating contrast curves (link to github page: https://github.com/vortex-exoplanet/VIP).

## Using HEEPS

1. Download all the HEEPS file as zip and extract it.
2. A default simulation parameters are described in a file called "simulation_config.py". These parameters can be overridden in the main program.
3. See files "example_coronagraph_psf.py" and "example_multi_cube_abberations.py" to get familiar with the module
4. See "manual.pdf" for more details about functions and architecture of the HEEPS module.



