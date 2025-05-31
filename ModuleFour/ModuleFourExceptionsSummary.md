Exceptions in C++ are a good way to provide a reaction to special circumstances that give control to special functions called handlers. The 
way they work is pretty simple, a portion of the code is enclosed in a "try" block where if the condition for the "try" block is true, the 
exception gets transferred to the "catch" block, also referred to as the "exception handler". However, if the "try" block is false, all the 
code inside gets executed as normal.

The first exception handler is a custom one that ....

The second one is used to catch an exception that is derived from std::exception. ....

The third one is a try-catch block that throws an exception if the value in "den" is zero. This secure coding practice for this type of 
function is crucial to make sure the values are being calculated correctly and the compiler is not giving any errors. 

The fourth one simply throws an exception, ....

