## Single Responsibility Principle

"Any Module ( set of functions, class, package, source code) should have a reason to change 
by only one actor."

What is an actor?

There a class called Employee that has three different methods
- calculateSalary()
- calculateHours()
- saveEmpData

calculateSalary() can be used for Financial person of the company let's say CFO.
calculateHors() can be use by Human resource of the company HR.
savEmpData() can be required by technical or engineering department.

So, here CFO, HR, Technical person are the three different actors.

Let's imagine a scenario where calculateSalary() and calculateHours() are using some underline function
or a private function let it be private 
