# awesome-fpga-programming
A curated list of awesome languages and tools to program FPGAs.
This list builds upon this survey:

E. Del Sozzo, D. Conficconi, A. Zeni, M. Salaris, D. Sciuto, and M. D. Santambrogio. *Pushing the Level of Abstraction of Digital System Design: a Survey on How to Program FPGAs*. ACM Computing Surveys (April 2022). https://doi.org/10.1145/3532989

and follows the same taxonomy to cluster state-of-the-art **Hardware Description Languages (HDLs)**, **High-Level Synthesis (HLS) tools**, and **Domain-Specific Languages (DSLs)**.

Please feel free to contribute and help maintain this list updated.

## Hardware Description Languages (HDLs)

The HDL taxonomy is based on the characteristics of the programming model employed in the embedded languages exploited as input.

### Functional-based HDLs

HDLs embedding the characteristics of the functional languages from which they derive (e.g., SML, Haskell, and Scala). 

- ***Chisel***
 
  *Year*: 2012
  
  *Paper*: J. Bachrach, H. Vo, B. Richards, Y. Lee, A. Waterman, R. Avizienis, J. Wawrzynek, and K. Asanovic. 2012. Chisel: Constructing hardware in a Scala embedded language. In DAC Design Automation Conference 2012. 1212–1221. https://doi.org/10.1145/2228360.2228584
  
  *Repository*: https://github.com/chipsalliance/chisel3
  
  *Website*: https://www.chisel-lang.org

- ***Clash***
 
  *Year*: 2009
  
  *Paper*: C. Baaij, M. Kooijman, J. Kuper, A. Boeijink, and M. Gerards. 2010. C𝜆ash: Structural descriptions of synchronous hardware using haskell. In 2010 13th Euromicro Conference on Digital System Design: Architectures, Methods and Tools. IEEE, 714–721. https://doi.org/10.1109/DSD.2010.21
  
  *Repository*: https://github.com/clash-lang/clash-compiler
  
  *Website*: https://clash-lang.org

 - ***DFiant***
  
    *Year*: 2017
  
    *Paper*: O. Port and Y. Etsion. 2017. DFiant: A dataflow hardware description language. In 2017 27th International Conference on Field Programmable Logic and Applications (FPL). IEEE, 1–4. https://doi.org/10.23919/FPL.2017.8056858
  
    *Repository*: https://github.com/DFiantHDL/DFiant
  
    *Website*: https://dfianthdl.github.io


 - ***Hardware ML (HML)***
 
    *Year*: 2000
  
    *Paper*: Yanbing Li and Miriam Leeser. 2000. HML, a Novel Hardware Description Language and Its Translation to VHDL. IEEE Transactions on Very Large Scale Integration (VLSI) Systems 8, 1 (2000), 1–8. https://doi.org/10.1109/92.820756
 
 - ***SpinalHDL***
 
    *Year*: 2014
 
    *Paper*: C Papon. 2017. SpinalHDL: An alternative hardware description language. FOSDEM (2017).
 
    *Repository*: https://github.com/SpinalHDL/SpinalHDL
 
    *Website*: https://spinalhdl.github.io/SpinalDoc-RTD/master/index.html
 
 - ***VeriScala***
 
    *Year*: 2019
 
    *Paper*: Y. Liu, Y. Li, Z. Qi, and H. Guan. 2019. A scala based framework for developing acceleration systems with FPGAs. Journal of Systems Architecture 98 (2019), 231–242. https://doi.org/10.1016/j.sysarc.2019.08.001 
  
    *Repository*: https://github.com/VeriScala/VeriScala
 

#### Imperative-based HDLs

#### SystemVerilog Extension HDLs


## High-Level Synthesis Tools (HLS)

### High-Level Synthesis

### Accelerator-Centric Synthesis (ACS)


## Domain-Specific Languages (DSLs)

We cluster DSLs based on their domain of interest: single application domain, architectural models, intermediate languages and infrastructure for DSLs. 

### Application Domain

DSLs concentrating on a given application domain (e.g., image processing, packet processing, etc.).

 - ***Spiral***
 
    *Year*: 2012
 
    *Paper*: Peter Milder, Franz Franchetti, James C Hoe, and Markus Püschel. 2012. Computer generation of hardware for linear digital signal processing transforms. ACM Transactions on Design Automation of Electronic Systems 17, 2 (2012), 1–33.

    *Paper*: Jianxin Xiong, Jeremy Johnson, Robert Johnson, and David Padua. 2001. SPL: A language and compiler for DSP algorithms. ACM SIGPLAN Notices 36, 5 (2001), 298–308.

    *Paper*: Franz Franchetti, Tze Meng Low, Doru Thom Popovici, Richard M Veras, Daniele G Spampinato, Jeremy R Johnson, Markus Püschel, James C Hoe, and José MF Moura. 2018. SPIRAL: Extreme performance portability. Proc. IEEE 106, 11 (2018), 1935–1968.


### Architectural Domain

### Intermediate Infrastructure
