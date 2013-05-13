ConstantPropagationAnalysis
===========================

An Intra-Procedure Constant Propagation Analysis course project for the Course of Programming Analysis 

Authors: Patricia Chin, Qinglin Xia 

Some Program Design Decisions:
1. The TopLatticeElement is represented as "T", and the BottomLatticeElement is represented as "B".
2. Because we wrote two seperate classes for MustAnalysis and MayAnalysis, the output of them would be seperated into
   two section.  

How to run the file: 
There is only one way to run the program: 
1. Import CS253_Project2 into Eclipse and run ConstantPropagationAnalysis.java with your tester file as its command arguments 
via your run configurations. 
In our Program, the test file is Testers.Foo
(right click CS253_Project2 > Run As... > Run Configurations, Click on Arguments tab > add Testers.Foo
 under program arguments)
