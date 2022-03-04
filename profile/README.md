# The OSVVM VHDL Verification Libraries
Open Source VHDL Verification Methodology (OSVVM) provides 
utility and verification component libraries that simplify 
your FPGA and ASIC verification tasks.
Using these libraries you can create a simple, readable, and 
powerful testbench that is suitable for either a simple FPGA block
or a complex ASIC.

## OsvvmLibraries
The repository [OsvvmLibraries](https://github.com/osvvm/OsvvmLibraries) 
contains all of the OSVVM libraries as submodules.   

Download the entire OSVVM model library using git clone with the "--recursive" flag:  
        `$ git clone --recursive https://github.com/osvvm/OsvvmLibraries`

## Submodules
- [OSVVM Documentation](https://github.com/OSVVM/Documentation) contains 
  - Documentation for all of OSVVM
  - To learn OSVVM start by reading the README.rst (displayed at the bottom of the page).
- [OSVVM utility library](https://github.com/osvvm/osvvm) provides support for: 
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
- [OSVVM Verification Script Library](https://github.com/osvvm/OSVVM-Scripts) 
  - OSVVM's simulator independent scripting approach.  
  - Supports Aldec's Riviera-PRO/Active-HDL, Siemen's QuestaSim/ModelSim, GHDL, Synopsys' VCS, and Cadence's Xcelium
- [AXI4](https://github.com/osvvm/AXI4) contains: 
  - Axi4 Full Manager, Memory, Subordinate Verification Components
  - Axi4 Lite Manager and Subordinate Verification Components
  - AxiStream Transmitter and Receiver Verification Components
- [UART](https://github.com/osvvm/UART) contains 
  - UART Transmitter and Receiver
- [DpRam](https://github.com/osvvm/DpRam) contains 
  - DpRam behavioral model 
  - DpRam Manager VC to read and write to the DpRam interface
- [OSVVM Common Library](https://github.com/osvvm/OSVVM-Common) 
  - Defines OSVVMs Model Independent Transactions (Address Bus and Stream)
  - Required for all OSVVM Verification Components
