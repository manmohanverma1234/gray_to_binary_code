# gray_to_binary_code

Gray to binary conversion :

The Most Significant Bit (MSB) of the binary code is always equal to the MSB of the given gray code.
Other bits of the output binary code can be obtained by checking the gray code bit at that index. If the current gray code bit is 0, then copy the previous binary code bit, else copy the invert of the previous binary code bit.
