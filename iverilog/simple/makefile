
all: 
	iverilog -o simple.vvp simple_tb.v simple.v
	vvp simple.vvp
	iverilog simple_tb.v simple.v
	gtkwave simple.vcd

clean:
	rm -rf *.vvp *.vcd a.out