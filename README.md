# MSoC - [pp4fpga] CORDIC



<br />
<p align="center">  
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Usage](#usage)
* [References](#References)
* [Contributing](#contributing)


<!-- ABOUT THE PROJECT -->
## About The Project
Using high level synthesis to accelerate CORDIC and implementation on Zedboard.  

**Directory structure**
* **README.md** - introduce the project, usage and reference 
* **hls/** - source files for HLS project 
  * cordic.h
  * cordic_fixed-top.cpp
  * cordic_fixed.cpp
  * directives.tcl
* **vivado/**  -  bitstream from vivado 
  * cordic.bit
  * cordic.hwh
* **python/**  -  Run on zedboard 
  * cordic.ipynb 


<!-- USAGE EXAMPLES -->
## Usage
1. HLS <br>
(1) create the hls project <br>
(2) add cordic_fixed.cpp and cordic.h to source <br>
(3) add cordic_fixed-top.cpp to Testbench <br>
(4) Set directives from directive.tcl <br>
(5) C-Sim, synthesis and Co-sim could work <br>

2. System on board <br>
(1) fpga board setup <br>
    We use **Xilinx ZedBoard Evaluation and Development Kit** to evaulate this project <br>
(2) put cordic.bit and cordic.hwh on Zedboard <br>
(3) python cordic.ipynb <br>

## References
1. https://github.com/KastnerRG/pp4fpgas/tree/master/examples

<!-- CONTRIBUTING -->
## Contributing
Build cordic.ipynb and run on Zedboard  
