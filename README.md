# Huge-Real Number

Problem: Default datatypes don't support aproxx infinitly long length number.

Implement the HUGE-double class. And perform all huge-integer operations using floating point huge real numbers.

## huge-integer was


Write a program which takes as input 2-HUGE-INTEGER N1 and N2. User may enter any number of digits he
 wants to (You can’t take N in an array of huge size, be very careful about the size, do the growing array thing
 we did in the class). You have to perform the following tasks along with all the possible constructors you
 needed:
 ● Operator [ ] - Implement two operators. Why? __________________________

 o int operator[ ](int i) const
 /* i’th digit of the huge integer by copy. E.g. if the integer is 123
 the 0’th digit is 3, 1st digit is 2, 2nd digit is 3, 3rd digit is 0, 4th digit is 0, (assuming that there are
 as many zeroes as you want after the most significant digit. */

 o int & operator[ ](int i)
 /* i’th digit of the huge integer by reference. E.g. if the integer is
 123 the 0’th digit is 3, 1st digit is 2, 2nd digit is 3, 3rd digit is 0, 4th digit shouldn’t be called.*/

 ● MakeADDQuantityWise function
 HI ADDQuantityWise(const HI & H2) const
 o which ignores the sign and returns the addition of the two huge numbers.

 ● MakeSUBQuantityWise Function
 HI SUBQuantityWise(const HI & H2) const
 o which should Subtract second number from the first (assuming the first number is greater then
 the second). There is no need to check for the sign.

 ● MakeLessThanQuantityWise function
 bool LessThanQuantityWise(const HI & H2) const
 o Which should based on the quantity (without looking into the sign) should return true if
 *this<H2.

 ● MakeGreaterThanQuantityWise functionbool GreaterThanQuantityWise(const HI & H2) const
 o Which should based on the quantity (without looking into the sign) should return true if
 *this>H2.

 ● MakeEqualQuantityWise function
 bool EqualQuantityWise(const HI & H2) const
 o Which should based on the quantity (without looking into the sign) should return true if
 *this==H2.


 ● Operator++ operator--
 ● Operator+ and +=
 ● Operator-  and -=
 ● operator<
 o operator<=
 ● operator>
 o operator>=
 ● operator==
 ● operator=

 ● Operator<<
 // (in class and outside class) for outputting
 on Screen and also on the file.

 ● Operator 
 // Unary Minus e.g. N1 = -N2

 ● Operator>>

 // (in class and
 outside class) for taking input from the
 console and the file



## With base 2-32
Huge-Integers in a base at maximum 36 (where
 the numbers are 0,1,2,...,9,A,B,C,....Z)
 25%
 You have to extend the HugeInteger and floating to HEXADECIMAL
 integers. Or in general any base conversion (we can assume that
 at max the base could 36)
###  Bonus- Converting Huge Real class to hexa-decimal and generalised base conversion too
