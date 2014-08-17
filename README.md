AspectjDemoOne
==============

Aspectj Demo using Aspectj annotaion. It is a very basic sample, need to explore how to create complex pointcuts and advices..using annotaion as well as native aj syntext.

1) Install eclipse ajdt plugin
http://www.eclipse.org/ajdt/downloads/

2) Clone this project using GIT.

3) Import this project in eclipse

4) Note this project has three classes
   LoggingAspect.java - Aspectj advice class, used Aspectj annotaion. 
                       It containd pointcuts/advices and logging statement to be woven for the classes/merthods, grouped by
                       pointcuts.
   DemoOneAspectAnnotaion.java - A sample cass for which logging statements are woven
   DemoOneAspectAnnotaionTest.java- is a test class which calls all methods for DemoOneAspectAnnotaion object, to show how 
   log dsatements are woven.
   
5) To see the result run  DemoOneAspectAnnotaionTest  -> as java application from the eclipse.


You will see log messages on console which includes Message printed by Methods as well as woven log messages.
TODO: Need to include references/More explanation. Modifying project with maven/gradle for ease of building and exploring Aspectj project.



