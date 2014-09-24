# MMA.jl

[![Build Status](https://travis-ci.org/davidlizeng/MMA.jl.svg?branch=master)](https://travis-ci.org/davidlizeng/MMA.jl)

MMA.jl packages a few of the functions commonly used in the [EE 103](http://ee103.stanford.edu) class. We'll briefly describe each of the functions provided.


- `std_dev(x)` computes the standard deviation of the entries of `x`
- `variance(x)` computes the variance of the entries of `x`
- `dist(x, y)` computes the distance between vectors `x` and `y`
- `rms(x)` computes the root mean square of the entries of `x`
- `angle(x, y)` computes the angle between vectors `x` and `y`


Julia already defines `std` and `var` functions, which are **not** the same as `std_dev` and `variance`. Make sure to **never** use `std` and `var` when coding in Julia for the course!

