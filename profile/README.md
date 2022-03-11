OSVVM is a VHDL verification methodology that defines a 
verification framework, VHDL utility library, 
VHDL Verification component library, and a scripting flow 
to simplify your FPGA or ASIC verification project from start to finish.
OSVVM is simple enough to use on small blocks and powerful enough to 
use on large, complex chips or systems.

One of the goals of OSVVM is to reduce the time spent on verification. 
OSVVM accomplishes this by: 
- Using the same framework approach for RTL, Core, and Chip level verification, 
we are able to reuse/pre-use verification components and test sequences between the different levels of verification.
- Using OSVVM's Model Independent transactions, we are able to share test sequences between different components.
- Using OSVVM's reporting, we are able to facilitate debug by making root cause of failures more readily available.

OSVVM is developed by the same VHDL experts who have helped develop VHDL standards.

## [OsvvmLibraries Repository] (https://github.com/osvvm/OsvvmLibraries) 
[OsvvmLibraries](https://github.com/osvvm/OsvvmLibraries) 
contains all of the OSVVM libraries as submodules.   

Download all of OSVVM using git clone with the "--recursive" flag:  
        `$ git clone --recursive https://github.com/osvvm/OsvvmLibraries`
        
If you would prefer a .zip file, see [osvvm.org Downloads](https://osvvm.org/downloads)

## [OSVVM Documentation Repository](https://github.com/OSVVM/Documentation)  
  - Documentation for all of OSVVM
  - To learn OSVVM you can either read [README.rst](https://github.com/OSVVM/Documentation#readme) or take the 
  class [Advanced VHDL Verification and Testbenches - OSVVM&trade; BootCamp](https://synthworks.com/vhdl_testbench_verification.htm)
## [OSVVM Utility Library Repository](https://github.com/osvvm/osvvm) 
Provides support for: 
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
