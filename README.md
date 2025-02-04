This repository contains a simple Dart program demonstrating a common off-by-one error in list iteration. The error occurs in the loop condition `i <= numbers.length`.  This causes an attempt to access an index outside the bounds of the list, resulting in an exception. The solution demonstrates the correct approach using `i < numbers.length`.