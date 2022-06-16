# awesome-fpga-programming
A curated list of awesome languages and tools to program FPGAs.
This list builds upon this survey:

E. Del Sozzo, D. Conficconi, A. Zeni, M. Salaris, D. Sciuto, and M. D. Santambrogio. *Pushing the Level of Abstraction of Digital System Design: a Survey on How to Program FPGAs*. ACM Computing Surveys (April 2022). https://doi.org/10.1145/3532989

and follows the same taxonomy to cluster state-of-the-art **Hardware Description Languages (HDLs)**, **High-Level Synthesis (HLS) tools**, and **Domain-Specific Languages (DSLs)**.

Please feel free to contribute and help maintain this list updated.

## Hardware Description Languages (HDLs)

The HDL taxonomy is based on the characteristics of the programming model employed in the embedded languages exploited as input. Here, we report high-level HDLs that, eventually, translates into standard HDLs, namely, VHDL/(System)Verilog.

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


<br /> 


## High-Level Synthesis (HLS) Tools

The HLS taxonomy is based on the target application and synthesis flow.

### High-Level Synthesis (HLS)

These tools generate RTL for generic IPs described using high-level languages (e.g., C and C++). Here we report only “pure” HLS tools, i.e., tools that do perform the HLS process without delegating it to third-party software. 

- ***Bambu***
 
    *Year*: 2012
 
    *Paper*: C. Pilato and F. Ferrandi. 2013. Bambu: A modular framework for the high level synthesis of memory-intensive applications. In Field Programmable Logic and Applications (FPL), 23rd International Conference on. IEEE. https://doi.org/10.1109/FPL.2013.6645550

    *Repository*: https://github.com/ferrandi/PandA-bambu
 
    *Website*: https://panda.dei.polimi.it/?page_id=31


- ***Catapult-HLS***
 
    *Year*: 2004
 
    *Paper*: T. Bollaert. 2008. Catapult synthesis: a practical introduction to interactive C synthesis. In High-Level Synthesis. Springer, 29–52. https://doi.org/10.1007/978-1-4020-8588-8_3

    *Website*: https://www.mentor.com/hls-lp/catapult-high-level-synthesis/


- ***CyberWorkBench***
 
    *Year*: 2011
 
    *Website*: https://www.nec.com/en/global/prod/cwb/index.html
 

 - ***Dynamatic***
 
    *Year*: 2017
 
    *Paper*: L. Josipović, R. Ghosal, and P. Ienne. 2018. Dynamically Scheduled High-level Synthesis. In Proceedings of the 2018 ACM/SIGDA International Symposium on Field-Programmable Gate Arrays (FPGA '18). Association for Computing Machinery, New York, NY, USA, 127–136. https://doi.org/10.1145/3174243.3174264

    *Paper*: L. Josipović, A. Guerrieri, and P. Ienne. 2020. Invited Tutorial: Dynamatic: From C/C++ to Dynamically Scheduled Circuits. In The 2020 ACM/SIGDA International Symposium on Field-Programmable Gate Arrays. 1–10. https://doi.org/10.1145/3373087.3375391

    *Paper*: L. Josipović, S. Sheikhha, A. Guerrieri, P. Ienne, and J. Cortadella. 2021. Buffer Placement and Sizing for High-Performance Dataflow Circuits. ACM Trans. Reconfigurable Technol. Syst. 15, 1, Article 4 (March 2022), 32 pages. https://doi.org/10.1145/3477053

    *Repository*: https://github.com/lana555/dynamatic
 
    *Website*: https://dynamatic.epfl.ch


- ***GAUT***
 
    *Year*: 2009
 
    *Paper*: P. Coussy, C. Chavet, P. Bomel, D. Heller, E. Senn, and E. Martin. 2008. GAUT: A high-level synthesis tool for DSP applications. In High-Level Synthesis. Springer, 147–169. https://doi.org/10.1007/978-1-4020-8588-8_9
 
    *Website*: http://hls-labsticc.univ-ubs.fr/
 

- ***Hastlayer***
 
    *Year*: 2015
 
    *Repository*: https://github.com/Lombiq/Hastlayer-SDK
 
    *Website*: https://hastlayer.com
 

- ***HDL Coder***
 
    *Year*: 2003
 
    *Documentation*: https://www.mathworks.com/help/pdf_doc/hdlcoder/hdlcoder_ug.pdf
 
    *Website*: https://www.mathworks.com/products/hdl-coder.html


- ***Intel HLS Compiler***
 
    *Year*: 2017
 
    *Documentation*: https://www.intel.com/content/www/us/en/docs/programmable/683349/22-1/pro-edition-reference-manual.html

    *Website*: https://www.intel.it/content/www/it/it/software/programmable/quartus-prime/hls-compiler.html


- ***LegUp***
 
    *Year*: 2009
 
    *Paper*: A. Canis, J. Choi, M. Aldham, V. Zhang, A. Kammoona, J. H. Anderson, S. Brown, and T. Czajkowski. 2011. LegUp: high-level synthesis for FPGA-based processor/accelerator systems. In Proceedings of the 19th ACM/SIGDA international symposium on Field programmable gate arrays. ACM, Association for Computing Machinery, New York, NY, USA, 33–36. https://doi.org/10.1145/1950413.1950423

    *Paper*: A. Canis, J. Choi, M. Aldham, V. Zhang, A. Kammoona, T. Czajkowski, S. D. Brown, and J. H. Anderson. 2013. LegUp: An open-source high-level synthesis tool for FPGA-based processor/accelerator systems. ACM Trans. Embed. Comput. Syst. 13, 2, Article 24 (September 2013), 27 pages. https://doi.org/10.1145/2514740

    *Repository*: https://github.com/wincle626/HLS_Legup
 
    *Website*: https://www.legupcomputing.com/


- ***ROCCC***
 
    *Year*: 2009
 
    *Paper*: J. Villarreal, A. Park, W. Najjar, and R. Halstead. 2010. Designing modular hardware accelerators in C with ROCCC 2.0. In Field-Programmable Custom Computing Machines (FCCM), 2010 18th IEEE Annual International Symposium on. IEEE, 127–134. https://doi.org/10.1109/FCCM.2010.28

    *Repository*: https://github.com/nxt4hll/roccc-2.0
 
    *Website*: http://roccc.cs.ucr.edu/


- ***Stratus HLS***
 
    *Year*: 2015
 
    *Paper*: D. Pursleyand, T. Yeh. 2017. High-level low-power system design optimization. In VLSI Design, Automation and Test (VLSI-DAT), 2017 International Symposium on. IEEE, 1–4. https://doi.org/10.1109/VLSI-DAT.2017.7939656
 
    *Website*: https://www.cadence.com/ko_KR/home/tools/digital-design-and-signoff/synthesis/stratus-high-level-synthesis.html
 

- ***Vitis HLS***
 
    *Year*: 2020
 
    *Documentation*: https://docs.xilinx.com/r/en-US/ug1399-vitis-hls/Getting-Started-with-Vitis-HLS


- ***Vivado HLS***
 
    *Year*: 2013
 
    *Documentation*: https://www.xilinx.com/support/documentation-navigation/design-hubs/dh0012-vivado-high-level-synthesis-hub.html


- ***XLS***
 
    *Year*: 2020
 
    *Repository*: https://github.com/google/xls/
 
    *Website*: https://google.github.io/xls/


### Accelerator-Centric Synthesis (ACS)

These tools focus on hardware acceleration of algorithms and automatize the whole design flow, from the HLS process to the bitstream generation.

- ***Altera OpenCL SDK (AOCL)***
 
    *Year*: 2012
 
    *Paper*: T. S. Czajkowski, U. Aydonat, D. Denisenko, J. Freeman, M. Kinsner, D. Neto, J. Wong, P. Yiannacouras, and D. P. Singh. 2012. From OpenCL to high-performance hardware on FPGAs. In 22nd international conference on field programmable logic and applications (FPL). IEEE, 531–534. https://doi.org/10.1109/FPL.2012.6339272

    *Documentation*: https://www.intel.com/content/dam/support/jp/ja/programmable/support-resources/bulk-container/pdfs/literature/hb/opencl-sdk/aocl-getting-started.pdf


- ***Intel oneAPI***
 
    *Year*: 2019
 
    *Documentation*: https://www.intel.com/content/www/us/en/developer/tools/oneapi/fpga-documentation.html?s=Newest
 
    *Website*: https://www.intel.com/content/www/us/en/developer/tools/oneapi/fpga.html


- ***Intel OpenCL SDK***
 
    *Year*: 2015
 
    *Documentation*: https://www.intel.com/content/www/us/en/support/programmable/support-resources/design-software/opencl-support.html?s=Newest
 
    *Website*: https://www.intel.com/content/www/us/en/software/programmable/sdk-for-opencl/overview.html


- ***SDAccel***
 
    *Year*: 2014
 
    *Documentation*: https://www.xilinx.com/support/documentation-navigation/design-hubs/dh0058-sdaccel-hub.html
 
    *Website*: https://www.xilinx.com/products/design-tools/software-zone/sdaccel.html


- ***SDSoC***
 
    *Year*: 2015
 
    *Documentation*: https://www.xilinx.com/support/documents/sw_manuals/xilinx2019_1/ug1027-sdsoc-user-guide.pdf
 
    *Website*: https://www.xilinx.com/products/design-tools/software-zone/sdsoc.html


- ***TAPAS***
 
    *Year*: 2018
 
    *Paper*: S. Margerm, A. Sharifian, A. Guha, A. Shriraman, and G. Pokam. 2018. TAPAS: Generating parallel accelerators from parallel programs. In 2018 51st Annual IEEE/ACM International Symposium on Microarchitecture (MICRO). IEEE, 245–257. https://doi.org/10.1109/MICRO.2018.00028

    *Repository*: https://github.com/sfu-arch/tapas
 

- ***Xilinx Vitis***
 
    *Year*: 2019
 
    *Documentation*: https://docs.xilinx.com/v/u/en-US/ug1416-vitis-documentation

    *Website*: https://www.xilinx.com/products/design-tools/vitis.html


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
