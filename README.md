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
  
    *Paper*: Y. Li and M. Leeser. 2000. HML, a Novel Hardware Description Language and Its Translation to VHDL. IEEE Transactions on Very Large Scale Integration (VLSI) Systems 8, 1 (2000), 1–8. https://doi.org/10.1109/92.820756
 
 - ***SpinalHDL***
 
    *Year*: 2014
 
    *Paper*: C. Papon. 2017. SpinalHDL: An alternative hardware description language. FOSDEM (2017). https://doi.org/10.5446/43800
 
    *Repository*: https://github.com/SpinalHDL/SpinalHDL
 
    *Website*: https://spinalhdl.github.io/SpinalDoc-RTD/master/index.html
 
 - ***VeriScala***
 
    *Year*: 2019
 
    *Paper*: Y. Liu, Y. Li, Z. Qi, and H. Guan. 2019. A scala based framework for developing acceleration systems with FPGAs. Journal of Systems Architecture 98 (2019), 231–242. https://doi.org/10.1016/j.sysarc.2019.08.001 
  
    *Repository*: https://github.com/VeriScala/VeriScala
 

### Imperative-based HDLs

HDLs embedding the characteristics of the imperative languages from which they derive (e.g., Java, Python, and C++).

- ***ArchHDL***
 
  *Year*: 2013
  
  *Paper*: S. Sato and K. Kise. 2013. ArchHDL: a new hardware description language for high-speed architectural evaluation. In 2013 IEEE 7th International Symposium on Embedded Multicore Socs. IEEE, 107–112. https://doi.org/10.1109/MCSoC.2013.38


- ***Just Another HDL (JHDL)***
 
  *Year*: 1998
  
  *Paper*: P. Bellows and B. Hutchings. 1998. JHDL - An HDL for Reconfigurable Systems. In IEEE Symposium on FPGAs for Custom Computing Machines. IEEE. https://doi.org/10.1109/FPGA.1998.707895

  *Website*: https://web.archive.org/web/20061205060548/http://jhdl.org/
  

- ***MaxJ***
 
  *Year*: 2009
  
  *Paper*: O. Lindtjorn, R. G. Clapp, O. Pell, O. Mencer, and M. J. Flynn. 2010. Surviving the end of scaling of traditional microprocessors in HPC. IEEE Hot Chips 22 (2010), 22–24.
  
  *Website*: https://www.maxeler.com/products/software/maxcompiler/


- ***MyHDL***
 
  *Year*: 2004
  
  *Paper*: J. Decaluwe. 2004. MyHDL: a Python-Based Hardware Description Language. Linux journal 127 (2004), 84–87. https://www.linuxjournal.com/article/7542
  
  *Code*: https://sourceforge.net/projects/myhdl/
  

- ***Python HDL (PHDL)***
 
  *Year*: 2007
  
  *Paper*: A. Mashtizadeh. 2007. PHDL: A Python Hardware Design Framework. https://dspace.mit.edu/handle/1721.1/41543.
  
  *Repository*: https://github.com/wnew/phdl


- ***PyMTL***
 
  *Year*: 2014
  
  *Paper*: D. Lockhart, G. Zibrat, and C. Batten. 2014. PyMTL: A Unified Framework for Vertically Integrated Computer Architecture Research. In 47th Annual IEEE/ACM International Symposium on Microarchitecture. IEEE. https://doi.org/10.1109/MICRO.2014.50

  *Paper*: S. Jiang, C. Torng. and C. Batten. 2018. An Open-Source Python-Based Hardware Generation, Simulation, and Verification Framework. In Workshop on Open-Source EDA Technology (WOSET’18). 1–5. https://www.csl.cornell.edu/~cbatten/pdfs/jiang-pymtl-woset2018.pdf

  *Repository*: https://github.com/pymtl/pymtl3
  
  *Website*: https://pymtl.github.io


- ***PyRTL***
 
  *Year*: 2017
  
  *Paper*: J. Clow, G. Tzimpragos, D. Dangwal, S. Guo, J. McMahan, and T. Sherwood. 2017. A pythonic approach for rapid hardware prototyping and instrumentation. In 2017 27th International Conference on Field Programmable Logic and Applications (FPL). IEEE, 1–7. https://doi.org/10.23919/FPL.2017.8056860
  
  *Repository*: https://github.com/UCSBarchlab/PyRTL
  
  *Website*: https://ucsbarchlab.github.io/PyRTL/


- ***PyVerilog***
 
  *Year*: 2015
  
  *Paper*: S. Takamaeda-Yamazaki. 2015. PyVerilog: A Python-Based hardware design processing toolkit for Verilog HDL. In Applied Reconfigurable Computing. Springer, 451–460. https://doi.org/10.1007/978-3-319-16214-0_42

  *Repository*: https://github.com/PyHDI/Pyverilog
  

### SystemVerilog Extension HDLs

HDLs extending SystemVerilog.

- ***BlueSpec SystemVerilog (BSV)***
 
    *Year*: 2004
 
    *Paper*: R. Nikhil. 2004. Bluespec System Verilog: efficient, correct RTL from high level specifications. In Proceedings. Second ACM and IEEE International Conference on Formal Methods and Models for Co-Design, 2004. MEMOCODE’04. https://doi.org/10.1109/MEMCOD.2004.1459818

    *Paper*: T. Bourgeat, C. Pit-Claudel, A. Chlipala, and Arvind. 2020. The essence of Bluespec: a core language for rule-based hardware design. In Proceedings of the 41st ACM SIGPLAN Conference on Programming Language Design and Implementation. 243–257. https://doi.org/10.1145/3385412.3385965

    *Repository*: https://github.com/B-Lang-org/bsc
 
    *Website*: http://wiki.bluespec.com


- ***Genesis2***
 
    *Year*: 2012
 
    *Paper*: O. Shacham, S. Galal, S. Sankaranarayanan, M. Wachs, J. Brunhaver, A. Vassiliev, M. Horowitz, A. Danowitz, W. Qadeer, and S. Richardson. 2012. Avoiding Game Over: Bringing Design to the Next Level. In DAC Design Automation Conference. IEEE, 623–629. https://doi.org/10.1145/2228360.2228472
 

- ***Transaction-Level Verilog (TL-Verilog)***
 
    *Year*: 2017
 
    *Paper*: S. F. Hoover. 2017. Timing-abstract circuit design in transaction-level Verilog. In 2017 IEEE International Conference on Computer Design (ICCD). IEEE, 525–532. https://doi.org/10.1109/ICCD.2017.91
 
    *Repository*: https://github.com/TL-X-org
 
    *Website*: https://www.redwoodeda.com/tl-verilog

## High-Level Synthesis (HLS) Tools

### High-Level Synthesis (HLS)

### Accelerator-Centric Synthesis (ACS)


## Domain-Specific Languages (DSLs)

We cluster DSLs based on their domain of interest: single application domain, architectural models, intermediate languages and infrastructure for DSLs. 

### Application Domain

DSLs concentrating on a given application domain (e.g., image processing and packet processing).

 - ***Spiral***
 
    *Year*: 2012
 
    *Paper*: P. Milder, F. Franchetti, J. C. Hoe, and M. Püschel. 2012. Computer generation of hardware for linear digital signal processing transforms. ACM Transactions on Design Automation of Electronic Systems 17, 2 (2012), 1–33. https://doi.org/10.1145/2159542.2159547

    *Paper*: F. Franchetti, T. M. Low, D. T. Popovici, R. M. Veras, D. G. Spampinato, J. R. Johnson, M. Püschel, J. C. Hoe, and J. M. Moura. 2018. SPIRAL: Extreme performance portability. Proc. IEEE 106, 11 (2018), 1935–1968. https://doi.org/10.1109/JPROC.2018.2873289

### Architectural Domain

### Intermediate Infrastructure
