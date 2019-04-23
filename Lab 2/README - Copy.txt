Name: Sean Malloy
SID: 998853013
Partner: jason Dinh
SID: 912054827

Difficulties: We had problems incrementing the PC. For some reason the addresses of the instructions in our ROM were being loaded into it 1 address away every time (PC + 1), instead of the conventional way of having it load 4 adresses away at a time (PC + 4). In order to test our circuit with the given instruction set, we had to increment the PC by 1, instead of 4. We also had a few troubles implementing jumps and branches, since we had to remove our shifters because they were bringing us to the wrong jump locations.

Doesn't Work: We believe that the whole circuit should work with what is given for now!