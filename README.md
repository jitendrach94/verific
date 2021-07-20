# verific
This tool is designed to verify the multiplier circuits.
The background of the tool is algebraic backward rewriting.
To run your design download the tool and give the command on terminal as:
./verific your_file.blif

sample:
./verific 4bit_1.blif
Old polynomial size: 84     // total number of polynomials generated without reduction 
New polynimial size: 64     // total number of polynimials generated after reduction
Time for backward rewriting: 0.00sec    // time take for algebraic backward rewriting
Overall run Time: 0.01sec    // overall time = time taken for circuit initialization + time taken for backward rewriting.


