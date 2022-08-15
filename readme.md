```
// main code complete,
// testbench needed to be implemented

// in testbench:

initial begin
$dumpfile("output_filename.vcd");
$dumpvars(0,testbench_filename);
// ...................bunch of test code with test values

end

# cmd:
iverilog -o output_filename input_filename
vvp output_filename

# creates dump file with "output_filename.vcd" 



# gtk_wave:

gtkwave utput_filename.vcd
```