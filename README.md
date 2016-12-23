![](https://github.com/SanPen/GridCal/blob/master/GridCal_banner.png)


This software aims to be a complete platform for power systems research and simulation. [Watch the video](https://youtu.be/O6lv-d8z39k)

![](https://github.com/SanPen/GridCal/blob/master/GridCal.png)

# Installation

Open a console and type:

`pip install GridCal` (windows)

`pip3 install GridCal` (Linux)

Easy enough right?

*You must have Python3 installed

# first run

From a Python console:

`from GridCal.ExecuteGridCal import run`

`run()`

The GUI should pop up.

You can use the calculation engine directly or from other applications:

`from GridCal.grid.CircuitOO import *`

Then you can create the grid objects and access the simulation objects as demonstrated in the test scripts in the test folder.

`GridCal/UnderDevelopment/GridCal/tests/`

#Features overview
It is pure Python, It works for Windows, Linux and OSX.

It is based on PyPower (MatPower for python) and it is compatible with Matpower files, and many more to come.

Some of the features you'll find already are:

- Power flow:
  - Newton Raphson Iwamoto (robust Newton Raphson)
  - Holomorphic Embedding Power flow.
  - DC approximation.
  
- The ability to handle island grids in all the simulation modes.

- Time series with load and generation profiles. 
  - It includes a nice profile import window.
  - Continuation power flow from step `t-1` to step `t`

- Bifurcation point with predictor-corrector Newton-Raphson.

- Monte Carlo simulation based on the input profiles. (Stochastic power flow)

Visit the [Wiki](https://github.com/SanPen/GridCal/wiki) to learn more and get started.

Send feedback and requests to santiago.penate.vera@gmail.com.
