<!--
author:   FilliDeFilla

email:    info@fillidefilla.com

version:  0.0.1

language: en

narrator: US English Female

comment:  Structure and Interpretation of Computer Programs

import: https://raw.githubusercontent.com/LiaTemplates/BiwaScheme/master/README.md

-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/learn_more.svg)](https://LiaScript.github.io/course/?https://github.com/fillidefilla/Structure-and-Interpretation-of-Computer-Programs)

# Structure and Interpretation of Computer Programs

## Example BiwaSchema

```scheme
(define (fizzbuzz x y)
  (print
    (cond (( = (mod x 15) 0 ) "FizzBuzz")
          (( = (mod x 3) 0 ) "Fizz")
          (( = (mod x 5) 0 ) "Buzz")
          (else x)))

    (if (< x y) (fizzbuzz (+ x 1) y)))

(fizzbuzz 1 10)
```
@BiwaScheme.eval
