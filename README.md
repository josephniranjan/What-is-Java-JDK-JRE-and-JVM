**Execution of a Java Program**

1.  Simple.java file  compiler (javac) compiles the sourcecode to Simple.class file (bytecode).
2. This class file (bytecode) can be executed in any platform/OS by JVM (Java virtual machine).
3. JVM translates bytecode into native machine code which machines can executed.
4. uses two inbuilt interpreter and JIT compiler to convert the bytecode to machine code.

![Java-Execution-Flow](https://user-images.githubusercontent.com/46956514/76709425-9ab10f00-6724-11ea-8743-0107b1cc04a7.png)

**JVM Architecture**

![JVM-Architecture](https://user-images.githubusercontent.com/46956514/76709531-8f121800-6725-11ea-87c4-ce7f9dcf0f4e.png)

The _**class loader**_ loads the class files
_**Method Area**_ stores class structures like metadata, the constant runtime pool, and the code for methods.
**_Heap_** stores all objects that are created during application execution.
**_Stacks_** store local variables, and intermediate results. All such variables are local to the thread by which they are created. Each thread has its own JVM stack, created simultaneously as the thread is created. So all such local variable are called thread-local variables.
_**PC register**_ store the physical memory address of the statements which is currently executing.

**JVM Execution Engine**

All code assigned to JVM is executed by an execution engine. The execution engine reads the byte code and executes one by one. It uses two inbuilt **_interpreter_** and _**JIT**_ compiler to convert the bytecode to machine code and execute it.

**What is JRE?**
The Java Runtime Environment (JRE) is a software package which bundles the libraries (jars) and the Java Virtual Machine.

**What is JDK?**
JDK is a superset of JRE. JDK contains everything that JRE has along with development tools for developing, debugging, and monitoring Java applications. You need JDK when you need to develop Java applications. 
you don't need jdk to run java program.

Few important components in JDKs are:
**appletviewer** – this tool can be used to run and debug Java applets without a web browser.
**jar** – the archiver, which packages related class libraries into a single JAR file. This tool also helps 
               manage JAR files
**javap** – the class file disassembler
**javaws** – the Java Web Start launcher for JNLP applications


 **Differences between JDK, JRE and JVM**

JDK  = JRE + DEV tools
JRE = JVM + library classes

![JDK-JRE-JVM](https://user-images.githubusercontent.com/46956514/76709940-05fce000-6729-11ea-9c32-4c30c8a0c16d.png)










