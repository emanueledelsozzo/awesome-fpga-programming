[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
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
 
 
 - ***DWARV***
 
    *Year*: 2012
 
    *Paper*: R. Nane, V. Sima, B. Olivier, R. Meeuws, Y. Yankova, and K. Bertels. 2012. DWARV 2.0: A CoSy-based C-to-VHDL hardware compiler. In Field Programmable Logic and Applications (FPL), 2012 22nd International Conference on. IEEE, 619–622. https://doi.org/10.1109/FPL.2012.6339221


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


- ***Kiwi***
 
    *Year*: 2008
 
    *Paper*: S. Singh and D. J. Greaves. 2008. Kiwi: Synthesis of FPGA circuits from parallel programs. In 2008 16th International Symposium on Field-Programmable Custom Computing Machines. IEEE, 3–12. https://doi.org/10.1109/FCCM.2008.46

    *Website*: https://www.cl.cam.ac.uk/~djg11/kiwi/


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


<br />


## Domain-Specific Languages (DSLs)

We cluster DSLs based on their domain of interest: single application domain, architectural models, intermediate languages and infrastructure for DSLs. 

### Application Domain

DSLs concentrating on a given application domain (e.g., image processing and packet processing).

- ***Darkroom***
 
    *Year*: 2014
 
    *Paper*: J. Hegarty, J. Brunhaver, Z. De Vito, J. Ragan-Kelley, N. Cohen, S. Bell, A. Vasilyev, M. Horowitz, and P. Hanrahan. 2014. Darkroom: compiling high-level image processing code into hardware pipelines. ACM Trans. Graph. 33, 4 (2014), 144–1. https://doi.org/10.1145/2601097.2601174

    *Repository*: https://github.com/jameshegarty/darkroom

    *Website*: http://darkroom-lang.org


- ***ExaSlang 4***
 
    *Year*: 2014
 
    *Paper*: C. Schmitt, M. Schmid, F. Hannig, J. Teich, S. Kuckuk, and H. Köstler. 2015. Generation of multigrid-based numerical solvers for FPGA accelerators. In Proceedings of the 2nd International Workshop on High-Performance Stencil Computations (HiStencils). 9–15. http://dx.doi.org/10.13140/2.1.1680.9760

    *Repository*: https://github.com/lssfau/ExaStencils

    *Website*: https://www.exastencils.fau.de


- ***Halide-HLS***
 
    *Year*: 2017
 
    *Paper*: J. Pu, S. Bell, X. Yang, J. Setter, S. Richardson, J. Ragan-Kelley, and M. Horowitz. 2017. Programming Heterogeneous Systems from an Image Processing DSL. ACM Trans. Archit. Code Optim. 14, 3, Article 26 (Aug. 2017), 25 pages. https://doi.org/10.1145/3107953

    *Repository*: https://github.com/jingpu/Halide-HLS


- ***HeteroHalide***
 
    *Year*: 2020
 
    *Paper*: J. Li, Y. Chi, and J. Cong. 2020. HeteroHalide: From image processing DSL to efficient FPGA acceleration. In Proceedings of the 2020 ACM/SIGDA International Symposium on Field-Programmable Gate Arrays. 51–57. https://doi.org/10.1145/3373087.3375320

    *Repository*: https://github.com/UCLA-VAST/heterohalide


- ***Hipacc***
 
    *Year*: 2014
 
    *Paper*: O. Reiche, M. Schmid, F. Hannig, R. Membarth, and J. Teich. 2014. Code generation from a domain-specific language for C-based HLS of hardware accelerators. In 2014 international conference on hardware/software codesign and system synthesis (CODES+ ISSS). IEEE, 1–10. https://doi.org/10.1145/2656075.2656081

    *Paper*: R. Membarth, O. Reiche, F. Hannig, J. Teich, M. Körner, and W. Eckert. 2015. Hipacc: A domain-specific language and compiler for image processing. IEEE Transactions on Parallel and Distributed Systems 27, 1 (2015), 210–224. https://doi.org/10.1109/TPDS.2015.2394802

    *Paper*: O. Reiche, M. A. Özkan, R. Membarth, J. Teich, and F. Hannig. 2017. Generating FPGA-based image processing accelerators with Hipacc. In Proceedings of the 36th International Conference on Computer-Aided Design (ICCAD '17). IEEE Press, 1026–1033. https://doi.org/10.1109/ICCAD.2017.8203894

    *Repository*: https://github.com/hipacc/hipacc-fpga

    *Website*: https://hipacc-lang.org/install.html


- ***P4-to-VHDL***
 
    *Year*: 2014
 
    *Paper*: P. Benáček, V. Pu, and H. Kubátová. 2016. P4-to-VHDL: Automatic generation of 100 gbps packet parsers. In 2016 IEEE 24th Annual International Symposium on Field-Programmable Custom Computing Machines (FCCM). IEEE. https://doi.org/10.1109/FCCM.2016.46

    *Paper*: J. Cabal, P. Benáček, L. Kekely, M. Kekely, V. Puš, and J. Kořenek. 2018. Configurable FPGA packet parser for terabit networks with guaranteed wire-speed throughput. In Proceedings of the 2018 ACM/SIGDA International Symposium on Field-Programmable Gate Arrays. 249–258. https://doi.org/10.1145/3174243.3174250


- ***P4FPGA***
 
    *Year*: 2017
 
    *Paper*: H. Wang, R. Soulé, H. T. Dang, K. S. Lee, V. Shrivastav, N. Foster, and H. Weatherspoon. 2017. P4fpga: A rapid prototyping framework for p4. In Proceedings of the Symposium on SDN Research. 122–135. https://doi.org/10.1145/3050220.3050234

    *Repository*: https://github.com/p4fpga/p4fpga

    *Website*: http://p4fpga.github.io


- ***P4HLS***
 
    *Year*: 2018
 
    *Paper*: J. S. da Silva, F. Boyer, and J. M. P. Langlois. 2018. P4-compatible high-level synthesis of low latency 100 Gb/s streaming packet parsers in FPGAs. In Proceedings of the 2018 ACM/SIGDA International Symposium on Field-Programmable Gate Arrays. 147–152. https://doi.org/10.1145/3174243.3174270

    *Repository*: https://github.com/engjefersonsantiago/P4HLS


- ***PolyMage***
 
    *Year*: 2016
 
    *Paper*: N. Chugh, V. Vasista, S. Purini, and U. Bondhugula. 2016. A DSL compiler for accelerating image processing pipelines on FPGAs. In Proceedings of the 2016 International Conference on Parallel Architectures and Compilation. 327–338. https://doi.org/10.1145/2967938.2967969

    *Repository*: https://bitbucket.org/udayb/polymage/src/master/

    *Website*: http://mcl.csa.iisc.ernet.in/polymage.html


- ***Rigel***
 
    *Year*: 2016
 
    *Paper*: J. Hegarty, R. Daly, Z. DeVito, J. Ragan-Kelley, M. Horowitz, and P. Hanrahan. 2016. Rigel: Flexible Multi-Rate Image Processing Hardware. ACM Trans. Graph. 35, 4, Article 85 (July 2016), 11 pages. https://doi.org/10.1145/2897824.2925892

    *Repository*: https://github.com/jameshegarty/rigel


- ***RIPL***
 
    *Year*: 2016
 
    *Paper*: R. Stewart, K. Duncan, G. Michaelson, P. Garcia, D. Bhowmik, and A. M. Wallace. 2018. RIPL: A Parallel Image Processing Language for FPGAs. ACM Transactions on Reconfigurable Technology and Systems 11, 1 (2018), 7:1–7:24. https://doi.org/10.1145/3180481

    *Repository*: https://github.com/robstewart57/ripl

    *Website*: https://robstewart57.github.io/ripl/


- ***Spiral***
 
    *Year*: 2012
 
    *Paper*: P. Milder, F. Franchetti, J. C. Hoe, and M. Püschel. 2012. Computer generation of hardware for linear digital signal processing transforms. ACM Transactions on Design Automation of Electronic Systems 17, 2 (2012), 1–33. https://doi.org/10.1145/2159542.2159547

    *Paper*: F. Franchetti, T. M. Low, D. T. Popovici, R. M. Veras, D. G. Spampinato, J. R. Johnson, M. Püschel, J. C. Hoe, and J. M. F. Moura. 2018. SPIRAL: Extreme performance portability. Proc. IEEE 106, 11 (2018), 1935–1968. https://doi.org/10.1109/JPROC.2018.2873289

    *Website*: http://spiral.net/index.html
    

### Architectural Domain

DSLs concentrating on a given architectural model (e.g., spatial architecture and systolic array).

- ***Spatial***
 
    *Year*: 2018
 
    *Paper*: D. Koeplinger, M. Feldman, R. Prabhakar, Y. Zhang, S. Hadjis, R. Fiszel, T. Zhao, L. Nardi, A. Pedram, C. Kozyrakis, , and K. Olukotun. 2018. Spatial: A language and compiler for application accelerators. In Proceedings of the 39th ACM SIGPLAN Conference on Programming Language Design and Implementation. 296–311. https://doi.org/10.1145/3192366.3192379

    *Repository*: https://github.com/stanford-ppl/spatial

    *Website*: https://spatial-lang.org


- ***SPGen***
 
    *Year*: 2020
 
    *Paper*: Y. Watanabe, J. Lee, K. Sano, T. Boku, and M. Sato. 2020. Design and preliminary evaluation of openacc compiler for fpga with opencl and stream processing dsl. In Proceedings of the International Conference on High Performance Computing in Asia-Pacific Region Workshops. 10–16. https://doi.org/10.1145/3373271.3373274


- ***SuSy***
 
    *Year*: 2020
 
    *Paper*: Y. Lai, H. Rong, S. Zheng, W. Zhang, X. Cui, Y. Jia, J. Wang, B. Sullivan, Z. Zhang, Y. Liang, Y. Zhang, J. Cong, N. George, J. Alvarez, C. Hughes, and P. Dubey 2020. SuSy: a programming model for productive construction of high-performance systolic arrays on FPGAs. In 2020 IEEE/ACM International Conference On Computer Aided Design (ICCAD). IEEE, 1–9. https://doi.org/10.1145/3400302.3415644

    *Repository*: https://github.com/IntelLabs/t2sp



### Intermediate Infrastructure

Solutions proposing an intermediate layer lying between the DSL and the RTL/HLS code.

- ***AnyHLS***
 
    *Year*: 2020
 
    *Paper*: M. A. Özkan, A. Pérard-Gayot, R. Membarth, P. Slusallek, R. Leißa, S. Hack, J. Teich, and F. Hannig. 2020. AnyHLS: High-Level Synthesis With Partial Evaluation. IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems 39, 11 (2020), 3202–3214. https://doi.org/10.1109/TCAD.2020.3012172

    *Repository*: https://github.com/AnyDSL/anyhls

    *Website*: https://anydsl.github.io


- ***Calyx***
 
    *Year*: 2021
 
    *Paper*: R. Nigam, S. Thomas, Z. Li, and A. Sampson. 2021. A compiler infrastructure for accelerator generators. In Proceedings of the 26th ACM International Conference on Architectural Support for Programming Languages and Operating Systems. 804–817. https://doi.org/10.1145/3445814.3446712

    *Repository*: https://github.com/cucapra/calyx

    *Website*: https://calyxir.org


- ***Delite Hardware Definition Language (DHDL)***
 
    *Year*: 2016
 
    *Paper*: D. Koeplinger, R. Prabhakar, Y. Zhang, C. Delimitrou, C. Kozyrakis, and K. Olukotun. 2016. Automatic Generation of Efficient Accelerators for Reconfigurable Hardware. In 2016 ACM/IEEE 43rd Annual International Symposium on Computer Architecture (ISCA). 115–127. https://doi.org/10.1109/ISCA.2016.20

    *Paper*: R. Prabhakar, D. Koeplinger, K. J. Brown, H. Lee, C. De Sa, C. Kozyrakis, and K. Olukotun. 2016. Generating configurable hardware from parallel patterns. Acm Sigplan Notices 51, 4 (2016). https://doi.org/10.1145/2872362.2872415

    *Repository*: https://bitbucket.org/raghup17/dhdl/src/master/


- ***FROST***
 
    *Year*: 2017
 
    *Paper*: E. Del Sozzo, R. Baghdadi, S. Amarasinghe, and M. D. Santambrogio. 2017. A Common Backend for Hardware Acceleration on FPGA. In Computer Design (ICCD), 2017 IEEE International Conference on. IEEE, 427–430. https://doi.org/10.1109/ICCD.2017.75

    *Paper*: E. Del Sozzo, R. Baghdadi, S. Amarasinghe, and M. D. Santambrogio. 2018. A unified backend for targeting fpgas from dsls. In 2018 IEEE 29th International Conference on Application-specific Systems, Architectures and Processors (ASAP). IEEE, 1–8. https://doi.org/10.1109/ASAP.2018.8445108


- ***HeteroCL***
 
    *Year*: 2019
 
    *Paper*: Y. Lai, Y. Chi, Y. Hu, J. Wang, C. H. Yu, Y. Zhou, J. Cong, and Z. Zhang. 2019. HeteroCL: A multi-paradigm programming infrastructure for software-defined reconfigurable computing. In Proceedings of the 2019 ACM/SIGDA International Symposium on Field-Programmable Gate Arrays. 242–251. https://doi.org/10.1145/3289602.3293910

    *Repository*: https://github.com/cornell-zhang/heterocl

    *Website*: https://heterocl.csl.cornell.edu


- ***Infrastructure for Delite-based DSLs***
 
    *Year*: 2014
 
    *Paper*: N. George, H. Lee, D. Novo, T. Rompf, K. J. Brown, A. K. Sujeeth, M. Odersky, K. Olukotun, and P. Ienne. 2014. Hardware system synthesis from domain-specific languages. In 2014 24th International Conference on Field Programmable Logic and Applications (FPL). IEEE, 1–8. https://doi.org/10.1109/FPL.2014.6927454


- ***LIFT***
 
    *Year*: 2019
 
    *Paper*: M. Kristien, B. Bodin, M. Steuwer, and C. Dubach. 2019. High-level synthesis of functional patterns with Lift. In Proceedings of the 6th ACM SIGPLAN International Workshop on Libraries, Languages and Compilers for Array Programming. 35–45. https://doi.org/10.1145/3315454.3329957

    *Repository*: https://github.com/lift-project/lift

    *Website*: http://www.lift-project.org


