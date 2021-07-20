---
title: Create An Analysis
description: Leveraging the custom function files for reproducible analysis.
---

## Introduction
A core feature of Iris DVA is the ability to create custom analysis functions
and tune input arguments from the Analysis interface and store output arguments
in a user-defined location. Furthermore, Iris DVA introduces a way to provide
mutable default values for specific function input arguments. To take
full advantage of the Analysis feature in Iris DVA, one must understand the
creation and access processes of function files in MATLAB. Below is a short list of
resources we assume the user comprehends.

* [Creating Function Files](https://www.mathworks.com/help/matlab/matlab_prog/create-functions-in-files.html)
* [Functions](https://www.mathworks.com/help/matlab/ref/function.html)
* [Types of
  Functions](https://www.mathworks.com/help/matlab/matlab_prog/types-of-functions.html)
* [Function Precedence
  Order](https://www.mathworks.com/help/matlab/matlab_prog/function-precedence-order.html)

Iris DVA leverages the capability of MATLAB's `function` syntax by parsing the
function output arguments as named variables, storing them in the specified output
mat-file. 

```matlab
function [output] = functionName(inputs)
  % ... perform analysis
end
```
