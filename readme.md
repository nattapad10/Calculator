งานประจำภาคการศึกษาที่1 2561 
นาย ณัฐภัทร เหมือนคิด 60030029 เรื่องที่เลือก "Calculator" ของ "loresoft"
ที่เลือกเรื่องนี้คือ 
โปรแกรมนี้เป็นโปรเกรมที่มีคนโฟคมาก เป้นเครื่องคิดเลขที่สามารถคำนวนฟังค์ชั่นยากๆได้ๆพวกคณิตศาสตร์วิศวกรรม ฟังก์ชั่นต่างที่เครื่องคิดเลขในwindownไม่สามารถเช่น sin
มีความใกล้ตัวกับวิชาที่เรียน (วิชาเรียนคณิตศาสตร์วิศวกรรม) จึงเป็นที่มาในการเลือกโปรแกรมนี้ครับผม โดยรายละเอียดการเพิ่มพีเจอร์3 อย่างอาจารย์สามารถตรวจได้ตามเอกสารที่ผมแนบไปนะครับ 

Calculator.NET
==========

Calculator.NET - Calculator that evaluates math expressions

[![Build Status](https://ci.appveyor.com/api/projects/status/i4vqogfwurshk6ff?svg=true)](https://ci.appveyor.com/project/LoreSoft/calculator)

[![GitHub Release](https://img.shields.io/github/release/loresoft/Calculator.svg)](https://github.com/loresoft/Calculator/releases)

[![Github Releases](https://img.shields.io/github/downloads/loresoft/Calculator/latest/total.svg)](https://github.com/loresoft/Calculator/releases)

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
