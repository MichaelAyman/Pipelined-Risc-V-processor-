Ousswa Chouchane ID: 900225937
Michael Henein ID: 900212900

The implementation of the jump instruction could not be fixed in time, which is
why you will notice that it is missing from both the diagram and the implementation; however, we are planning to implement them closely in the branching.
5
We will have a control coming out from the control unit and anded with the
branching getting out of the branching unit, it should give us the right destination of PC.
We have also met some issues with implementing AUIPC, mainly adding
hardware and accommodation to other previously constructed functions. This
function implementation is also not included in both the diagram and the source
files.
Edge cases have not been tested. Further enhancement to the project will
be done before MS3.


/////////////////////////MS3///////////////////////
- all of the functionalities of the alu for the uncompressed instructions are working 
- the tested functionalities of the compressed instructions are working
- loading, branching and jumping work fine except for the instruction following the correctly ecexuted one, this problem was not encountered in the pipelined implementation of two memories however we started facing it when we implemented the single memory 
- the forwarding is detected and applied correctly 
- storing sometimes have glitches we couldnt fix 
- the rest of the tested functionalities are working fine


////////////////instructions///////////////////
view design.v for the top module
open the schematics usig=ng draw.io 
5 is the latest version