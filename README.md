# notes

int16 will fit the value -777, why?

remember the difference between signed and unsigned integers. -777 is negative so the datatype should be signed. 
Now intN means numbers ranging from -2^(N-1) to 2^(N-1) - 1 that is
int8 range is -2^(8-1) to 2^(8-1) -1 = -2^7 to 2^7 - 1 = -128 to 127 Now think what would accommodate -777?
