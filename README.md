# pointers.cpp

Neither firstvalue nor secondvalue are directly set any value in the program, both end up with a value set indirectly through the use of mypointer.
First, mypointer is assigned the address of firstvalue using the address-of operator (&). Then, the value pointed to by mypointer is assigned a value of 10. Because, at this moment, mypointer is pointing to the memory location of firstvalue, this in fact modifies the value of firstvalue.
