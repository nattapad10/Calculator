Calculator
==========

Calculator.NET - Calculator that evaluates math expressions


The library supports math expressions, functions unit conversion and variables. Below are some examples of using the library directly.

    MathEvaluator eval = new MathEvaluator();
    //basic math
    double result = eval.Evaluate("(2 + 1) * (1 + 2)");
    //calling a function
    result = eval.Evaluate("sqrt(4)");
    //evaluate trigonometric 
    result = eval.Evaluate("cos(pi * 45 / 180.0)");
    //convert inches to feet
    result = eval.Evaluate("12 [in->ft]");
    //use variable
    result = eval.Evaluate("answer * 10");
    //add variable
    eval.Variables.Add("x", 10);            
    result = eval.Evaluate("x * 10");
    
Calculator that evaluates math expressions. 

![Calculator.NET](https://raw.githubusercontent.com/loresoft/Calculator/master/Documentation/Calculator.NET.png)

### Calculator.NET Features

* Evaluate math expressions including grouping
* Support trigonometry and other function
* Common unit conversion of the following types
    * Length
    * Mass
    * Speed
    * Temperature
    * Time
    * Volume
* Variable support including last answer
