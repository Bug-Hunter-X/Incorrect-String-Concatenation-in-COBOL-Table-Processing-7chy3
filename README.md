# COBOL String Concatenation Bug

This repository demonstrates a common, yet subtle, error in COBOL programs when dealing with string manipulation, specifically string concatenation within loops to populate tables.  The example showcases incorrect usage of the ampersand (&) operator for concatenation and provides a corrected version.

## Bug Description
The provided COBOL code attempts to populate a table with strings that include a counter. However, the use of the ampersand for string concatenation leads to unexpected results or a compilation error, depending on the COBOL compiler.  Correct string concatenation in COBOL often involves functions or other compiler-specific methods.

## Solution
The solution shows how to correctly concatenate strings using an appropriate method (e.g., using the INSPECT or STRING statements or compiler-specific functions).