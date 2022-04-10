OSVVM is a verification framework, VHDL utility library, 
VHDL Verification component library, and a scripting flow
that simplifies your FPGA or ASIC verification project 
from start to finish.
Using these libraries you can create a simple, readable, 
and powerful testbench that is suitable for either a 
simple FPGA block or a complex ASIC.

OSVVM is developed by the same VHDL experts who
have helped develop VHDL standards.
We have used our expert VHDL skills to create
advanced verification capabilities that:

- Are simple to use and feel like built-in language features.
- Maximize reuse and reduce project schedule.
- Facilitate readabilty and reviewability by the whole team including software and system engineers.
- Facilitate debug with HTML based Test Suite and Test Case reporting
- Provide buzz word features including Constrained Random, Functional Coverage, Scoreboards, FIFOs, Memory Models.

## Learning OSVVM
You can find an overview of OSVVM at [osvvm.github.io](https://osvvm.github.io).
Alternately you can find our pdf documentation at 
[OSVVM Documentation Repository](https://github.com/OSVVM/Documentation#readme).

You can also learn OSVVM by taking the class, [Advanced VHDL Verification and Testbenches - OSVVM&trade; BootCamp](https://synthworks.com/vhdl_testbench_verification.htm)

## Download OSVVM 
OSVVM is available as either a git repository 
[OsvvmLibraries](https://github.com/osvvm/OsvvmLibraries) 
or zip file from [osvvm.org Downloads Page](https://osvvm.org/downloads).

On GitHub, all OSVVM libraries are a submodule of the repository OsvvmLibraries. Download all OSVVM libraries using git clone with the “–recursive” flag:
        `$ git clone --recursive https://github.com/osvvm/OsvvmLibraries`
        
## Run The Demos
A great way to get oriented with OSVVM is to run the demos.
For directions on running the demos, see [OSVVM Scripts](https://github.com/osvvm/OSVVM-Scripts#readme).


## [OSVVM Utility Library Repository](https://github.com/osvvm/osvvm) 
The OSVVM Utility library implements verification capabilities such as:
  - Transaction-Level Modeling (TbUtilPkg, ResolutionPkg)
  - Constrained Random test generation (RandomPkg)
  - Functional Coverage with hooks for UCIS coverage database integration (CoveragePkg)
  - Intelligent Coverage Random test generation  (CoveragePkg)
  - Utilities for testbench process synchronization generation (TbUtilPkg)
  - Utilities for clock and reset generation (TbUtilPkg)
  - Transcript files (TranscriptPkg)
  - Error logging and reporting - Alerts and Affirmations (AlertLogPkg)
  - Message filtering - Logs (AlertLogPkg)
  - Scoreboards and FIFOs (data structures for verification) (ScoreboardGenericPkg)
  - Memory models (MemoryPkg)
  
For details see the [OSVVM Utility Library README](https://github.com/osvvm/osvvm#readme).
  
## [OSVVM Verification Script Library Repository](https://github.com/osvvm/OSVVM-Scripts)
  - OSVVM's simulator independent scripting approach.  
  - Supports Aldec's Riviera-PRO/Active-HDL, Siemen's QuestaSim/ModelSim, GHDL, Synopsys' VCS, and Cadence's Xcelium
## OSVVM Verification Components
OSVVM Verification components are all independent git repositories. 
### [OSVVM Common Library Repository](https://github.com/osvvm/OSVVM-Common)
  - Defines OSVVMs Model Independent Transactions (Address Bus and Stream)
  - Required for all OSVVM Verification Components
### [AXI4 Repository](https://github.com/osvvm/AXI4) 
  - Axi4 Full Manager, Memory, Subordinate Verification Components
  - Axi4 Lite Manager and Subordinate Verification Components
  - AxiStream Transmitter and Receiver Verification Components
### [UART Repository](https://github.com/osvvm/UART) 
  - UART Transmitter and Receiver
### [DpRam Repository](https://github.com/osvvm/DpRam) 
  - DpRam behavioral model 
  - DpRam Manager VC to read and write to the DpRam interface
