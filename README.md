# Eclipse IDE
![Eclipse-Luna-Logo](https://github.com/danielurra/eclipse/assets/51704179/9f79c836-ae79-4770-a5fe-96c34984efba)</br>
Eclipse is an integrated development environment (IDE) that combines a code editor, compiler, debugger, text editor and a graphical user interface (GUI) builder.
## How to debug
A very useful technique to figure out logic problems is known as debugging. You remove the bugs in the code using debugging.</br>
Eclipse allow us to insert **Code breakpoints** that allow us to quickly focus on the code that concerns you.</br>
You set a breakpoint and run the program until it reaches that point.</br>
Stopping at each iteration of the loop allow us to inspect the value of variables at that given time.</br>
To use the debugger in Eclipse, navigate to the **_Run/Debug As_** menu, or simply press **F11**:</br>
* Press **F11** and Eclipse will run your program in debug mode.</br>
* Press **F8** to move to the next iteration.</br>

See below animation:
![howtodebug](https://github.com/danielurra/eclipse/assets/51704179/4acbd09c-0fb1-4a39-9a6a-af3ba4cfb896)</br>
## Grab the code
```java
package package_forloop_danny;

public class ClassForLoopDanny {

	public static void main(String[] args) {
		for (int D = 0; D < 5; D++) {
			System.out.println("The value of variable D is: " + D);
		}
	}
}
```
## Print current date
The **Date** class is packed into a particular package.</br>
It is required to import that package to be able to use the **Date** class.</br>
```java
import java.util.Date
```
Here **util** is the package, and **Date** is the class.</br>
We have to use the methods present in that particular class.</br>
To use the methods present in that class, we need to create an object of that particular class.</br>
See code below:
```java
Date d= new Date();
```
**d** is the object that contains the date and time, we need to convert it into readable text for printing purposes.</br>
```java
System.out.println(d.toString());
```
![to-string](https://github.com/danielurra/eclipse/assets/51704179/34036efb-884f-468e-8a06-ec79e84ea9a3)

## Grab the code
```java
package pkg_date_danny;

import java.util.Date;

public class ClassDateDanny {

	public static void main(String[] args) {
		Date d = new Date();
		System.out.println(d.toString());

	}

}
```
![eclipse-print-date](https://github.com/danielurra/eclipse/assets/51704179/bb7c649e-bd29-46be-b85f-efb559b024d9)</br>
## Constructor
**Step 1 of 2** - Create a class for all the rabbits</br>
![1 conejo-class](https://github.com/danielurra/eclipse/assets/51704179/2f48f184-6a77-4683-ab04-b95f1f8dcb02)</br>
```java
package pkg_conejo;

public class Conejo_class {
	String saludo;
//constructor - special method that allow us to initialize values when creating the object
//constructor - same name as the class
//constructor - doesn't return anything, not even void

	public Conejo_class(String Passedsaludo) {
		this.saludo = Passedsaludo;
	}

	public void sayHello() {
		System.out.println(this.saludo);
	}
}
```
**Step 2 of 2** - Create one particular bunny whose greeting is a well known one</br>
![2 create-new-object-and-call-method](https://github.com/danielurra/eclipse/assets/51704179/7d8920d6-3145-4038-b26f-0005dca20577)</br>
```java
package pkg_conejo;

public class Executable_class_has_main_mthd_run_calls {

	public static void main(String[] args) {
//      create a new object of class conejo, type new and Ctrl Space bar
//		type name = new type();
		Conejo_class BugsBunny = new Conejo_class("Que hay de nuevo viejo!!!");
//		 call the method para saludar, usar period, dot, punto
		BugsBunny.sayHello();
	}

}
```




