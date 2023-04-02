[View code on GitHub](https://dune.com/docs/query/DuneSQL-reference/Functions-and-operators/bitwise.md)

The Bitwise section of the app technical guide covers the different functions available for performing bitwise operations in Dune Docs. The guide provides examples of how to use each function and the expected output. The functions covered in this guide include bit_count(), bitwise_and(), bitwise_not(), bitwise_or(), bitwise_xor(), bitwise_left_shift(), bitwise_right_shift(), and bitwise_right_shift_arithmetic().

The bit_count() function counts the number of bits set in a given value, treated as a bits-bit signed integer in 2's complement representation. The function takes two arguments, the value to count the bits in and the number of bits in the value. The function returns a bigint. The guide provides examples of how to use the function with different values and bit sizes.

The bitwise_and() function returns the bitwise AND of two values in 2's complement representation. The function takes two arguments, the two values to perform the operation on. The function returns a bigint. The guide provides an example of how to use the function with two values and the expected output.

The bitwise_not() function returns the bitwise NOT of a value in 2's complement representation. The function takes one argument, the value to perform the operation on. The function returns a bigint. The guide provides examples of how to use the function with different values and the expected output.

The bitwise_or() function returns the bitwise OR of two values in 2's complement representation. The function takes two arguments, the two values to perform the operation on. The function returns a bigint. The guide provides an example of how to use the function with two values and the expected output.

The bitwise_xor() function returns the bitwise XOR of two values in 2's complement representation. The function takes two arguments, the two values to perform the operation on. The function returns a bigint. The guide provides an example of how to use the function with two values and the expected output.

The bitwise_left_shift() function returns the left shifted value of a given value. The function takes two arguments, the value to shift and the number of bits to shift by. The function returns the same type as the input value. The guide provides examples of how to use the function with different values and the expected output.

The bitwise_right_shift() function returns the logical right shifted value of a given value. The function takes two arguments, the value to shift and the number of bits to shift by. The function returns the same type as the input value. The guide provides examples of how to use the function with different values and the expected output.

The bitwise_right_shift_arithmetic() function returns the arithmetic right shifted value of a given value. The function takes two arguments, the value to shift and the number of bits to shift by. The function returns the same type as the input value. The guide provides examples of how to use the function with different values and the expected output.

Overall, the Bitwise section of the app technical guide provides a comprehensive overview of the different functions available for performing bitwise operations in Dune Docs. The guide includes examples of how to use each function and the expected output, making it easy for developers to understand and implement these functions in their code.
## Questions: 
 1. What is the purpose of the dune docs app and how does it relate to blockchain technology?
- The app technical guide does not provide information on the purpose of the dune docs app or its relation to blockchain technology, so a blockchain SQL analyst may need to seek additional information elsewhere.

2. Can the bitwise functions be used with binary data stored in a SQL database?
- The app technical guide does not provide information on whether the bitwise functions can be used with binary data stored in a SQL database, so a blockchain SQL analyst may need to test this or seek additional information elsewhere.

3. Are there any limitations to the size of the values that can be used with the bitwise functions?
- The app technical guide provides information on the behavior of the bitwise functions when shifting values by 64 or more bits, but it does not provide information on any other limitations to the size of the values that can be used with the functions. A blockchain SQL analyst may need to test this or seek additional information elsewhere.