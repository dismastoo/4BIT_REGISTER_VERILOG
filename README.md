# 4BIT_REGISTER_VERILOG
To build a 4 bit register we use a D flip flop as a building block and cascade 4 D flip flops to realize the 4 bit register.
for a D flip flop when the clock is 1(rising), whatever is the input shall be presented as the output.
When the clock is made 0(falling), the output retains its initial state.
for our case we simulate with A = 1101 at clock =1 and when we change the input to 1000 while the clock is 0(falling), the output remains the same(1101).
Thats how a 4 bit register is realized.
