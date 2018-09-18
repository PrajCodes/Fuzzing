# Fuzzing
This Fuzzer Service Provider Jar is implemented to test the JSoup Java Library against multiple modifications to input HTML file 

Fuzzing or Fuzz Testing in software engineering refers to testing to try and break a software by providing unexpected random data as input to the software. 

Here, In this example, I have implemented a simple fuzzer to check html parser library Jsoup. 
This project is an extensible application(https://docs.oracle.com/javase/tutorial/ext/basics/spi.html ) which can be used as a seperate module and added to an available application as an external jar. This is a new functionality introduced in JDK 8 release. 
The steps to run the fuzzer is shown in howtorun.png in Screenshots.zip. 
The source code contains FuzzerServiceDemo/FuzzerDemo.java which is the Driver Program, and multiple service providers to remove, replace and insert scripts that may lead to cross site scripting attack. 
Here, I have tried to test the clean function of Jsoup. But it can be extended and modifies easily to test any functionality using the service providers. 
