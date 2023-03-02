# Array
Data structure 
An array is a collection of items of same data type stored at contiguous memory locations. 

Is the array always of a fixed size?
the array has a fixed size meaning once the size is given to it, it cannot be changed i.e. you can’t shrink it nor can you expand it. 
The reason was that for expanding if we change the size we can’t be sure ( it’s not possible every time) that we get the next memory location to us for free.
The shrinking will not work because the array, when declared, gets memory statically allocated, and thus compiler is the only one that can destroy it. 
