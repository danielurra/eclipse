# Eclipse IDE
![Eclipse-Luna-Logo](https://github.com/danielurra/eclipse/assets/51704179/9f79c836-ae79-4770-a5fe-96c34984efba)</br>
Eclipse is an integrated development environment (IDE) that combines a code editor, compiler, debugger, text editor and a graphical user interface (GUI) builder.
## How to debug
A very useful technique to figure out logic problems is known as debugging. You remove the bugs in the code using debugging.</br>
To use the debugger in Eclipse, navigate to the Run | Debug As menu, or simply press F11:</br>
Press F11 and Eclipse will run your program in debug mode.</br>
Press F8 to move to the next iteration</br>
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
