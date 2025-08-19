# Eric Wastl's original Synacor challenge, solved with Admiran

## Files

* `arch-spec`: the original specification of the processor architecture that needs to be emulated
* `arch.am`: the architecture implemented in Admiran
* `challenge.asm`: the disassembled binary
* `challenge.bin`: the original binary program that needs to be emulated
* `challenge.input`: all of the correct commands to feed to the program to run to completion (including modifying memory/register state to hack the teleporter
* `codes.am`: Admiran program to extract all of the progress codes from the output
* `disassemble.am`: disassembler for the challenge.bin file
* `notes`: notes taken while manually solving the puzzle
* `solveTeleport.am`: Admiran program to solve the code to supply to the teleport verification
* `vaultPath.am`: Admiran program to solve reaching the target room with a weight of 30
* `vm.am`: the virtual machine to execute challenge.bin

