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
* Press **F8** to move to the next iteration</br>

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
