
### Name of File containing `main`
* `Source.cpp`

### Details
* The code is implemented as modular as possible and command-line arguments are set as parameters to `Parameters` Class 
* `cuboid()` is the general function to compute cuboids according to the link number or iteration number
* Additional Functions are present for matrix multiplications and to print out the points to the console in `.iv` format

### Programming Language and OS
* The code is implemented in C++ on the tux (Linux) platform and would require the g++ compiler to compile

### Instructions
* cd into the directory of the folder containing `Source.cpp` and the `make` file.
* Type in `make` to compile. This produces an executable of the format `CG_hw5`
* Type in `./CG_hw5 -t [theta1] -u [theta2] -v [theta3] -l [L1_value] -m [L2_value] -n [L3_value]` to run the code
* Follow the run-time command by `> [filename].iv` to redirect the output to `[filename].iv` format

### Cleanup
* You can type `make rm` to remove the executable `CG_hw5` and run again
