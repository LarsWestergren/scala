# Complex Numbers

A complex number is a number in the form `a + b * i` where `a` and `b` are real and `i` satisfies `i^2 = -1`.

`a` is called the real part and `b` is called the imaginary part of `z`.
The conjugate of the number `a + b * i` is the number `a - b * i`.
The absolute value of a complex number `z = a + b * i` is a real number `|z| = sqrt(a^2 + b^2)`. The square of the absolute value `|z|^2` is the result of multiplication of `z` by its complex conjugate.

The sum/difference of two complex numbers involves adding/subtracting their real and imaginary parts separately:
`(a + i * b) + (c + i * d) = (a + c) + (b + d) * i`,
`(a + i * b) - (c + i * d) = (a - c) + (b - d) * i`.

Multiplication result is by definition
`(a + i * b) * (c + i * d) = (a * c - b * d) + (b * c + a * d) * i`.

The reciprocal of a non-zero complex number is
`1 / (a + i * b) = a/(a^2 + b^2) - b/(a^2 + b^2) * i`.

Dividing a complex number `a + i * b` by another `c + i * d` gives:
`(a + i * b) / (c + i * d) = (a * c + b * d)/(c^2 + d^2) + (b * c - a * d)/(c^2 + d^2) * i`.

Exponent of a complex number can be expressed as
`exp(a + i * b) = exp(a) * exp(i * b)`,
and the last term is given by Euler's formula `exp(i * b) = cos(b) + i * sin(b)`.


Implement the following operations:
 - addition, subtraction, multiplication and division of two complex numbers,
 - conjugate, absolute value, exponent of a given complex number.


Assume the programming language you are using does not have an implementation of complex numbers.

The Scala exercises assume an SBT project scheme. The exercise solution source
should be placed within the exercise directory/src/main/scala. The exercise
unit tests can be found within the exercise directory/src/test/scala.

To run the tests simply run the command `sbt test` in the exercise directory.

For more detailed info about the Scala track see the [help
page](http://exercism.io/languages/scala).


## Source

Wikipedia [https://en.wikipedia.org/wiki/Complex_number](https://en.wikipedia.org/wiki/Complex_number)

## Submitting Incomplete Solutions
It's possible to submit an incomplete solution so you can see how others have completed the exercise.