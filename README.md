# delta-v
`delta-v` is a program to calculate [Delta-V](https://en.wikipedia.org/wiki/Delta-v) (*ΔV*). Made specifically for [Kerbal Space Program](https://en.wikipedia.org/wiki/Kerbal_Space_Program), but may be used for other purposes.

It is currently under heavy development and many things will change in the near future. Feel free to give some tips or ideas!

## Compiling
To run the program, do the following:

  1. `git clone https://github.com/ii-v/delta-v.git`
  2. `cd delta-v`
  3. `make`
  4. Run the program with `./delta-v [number of stages]`
  5. Optional: Install the program with `sudo make install` and uninstall with `sudo make uninstall`

If this for some reason doesn't work for you, compile manually with `gcc -o delta-v delta-v.c -lm` and run with `./delta-v`
The program has only been tested on Ubuntu 16.04, but should work on other systems.

## Usage
When compiled, the program is very simple to use.
Run the program with `./delta-v [number of stages]` and follow the prompts.

If you are unsure what any of the prompts mean, please consult Wikipedia or the KSP Wiki.

## License
`delta-v` is made available under the MIT License, the full license can be read in the `LICENSE` file in this directory.
