# sqrt_cordic
Open source HLS implementation of sqrt cordic
reference:https://github.com/Xilinx/HLx_Examples

- **sqrt_cordic** - Linear Algebra Library: Sqrt() Example.
Implementing the math function sqrt from the Linear Algebra Library.

## DESIGN FILE HIERARCHY

	|   README.md
	|   
	\---code
			cordic_defines.h
			cordic_isqrt.cpp
			cordic_sqrt.cpp
			float_sqrt.cpp
			top_magnitude.cpp
	\---code_opt
			cordic_defines.h
			cordic_isqrt.cpp
			cordic_sqrt.cpp
			float_sqrt.cpp
			top_magnitude.cpp
	\---script
			run_sqrt_cordic_hls_script.tcl
	\---impl
			csynth.xml
			top_process_magnitude_sim.log
	\---testdata
			test_main.cpp


## OTHER INFORMATION

For more information check here: 

[Vivado HLS User Guide][]

## SUPPORT

For questions and to get help on this project or your own projects, visit the [Vivado HLS Forums][]. 

## License
The source for this project is licensed under the [3-Clause BSD License][]

## Contributing code
Please refer to and read the [Contributing][] document for guidelines on how to contribute code to this open source project. The code in the `/master` branch is considered to be stable, and all pull-requests should be made against the `/develop` branch.

[Contributing]: CONTRIBUTING.md 
[3-Clause BSD License]: LICENSE.md
[Vivado HLS Forums]: https://forums.xilinx.com/t5/High-Level-Synthesis-HLS/bd-p/hls 
[Vivado HLS User Guide]: http://www.xilinx.com/support/documentation/sw_manuals/xilinx2015_4/ug902-vivado-high-level-synthesis.pdf
