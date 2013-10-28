selenium-training
=================

selenium training, including css, xpath

Tasks
16.10.2013
Recollect: 

SELENIUM
* what is selenium?
>>>  It's a portable software testing framework for web applications. Selenium provides a record/playback tool for authoring tests without learning a test scripting language (Selenium IDE). It also provides a test domain-specific language (Selenese) to write tests in a number of popular programming languages, including Java, C#, Groovy, Perl, PHP, Python and Ruby. The tests can then be run against most modern web browsers. Selenium deploys on Windows, Linux, and Macintosh platforms.
* when do we use it?
>>> for web applications automation
* what are the ways selenium can identify web elements?
>>>  There are 8 locators strategies included in Selenium:
 - Identifier
 - Id
 - Name
 - Link
 - DOM
 - XPath
 - CSS
 - UI-element
 
JAVA and OOP
Q: what does word "extends" in java class mean? Please write an example, saying you need to write a class who has parent class, use any names, but remember java naming convention (camel case)
A: Java, supports class inheritance which allows one class to "inherit" the properties of another class. For example, all Java objects are inherited from the java.lang.Object class. This means that we can call the toString() method inherited from java.lang.Object, and get a string representation of any java object, such as an Integer, a Float, a Double, etc.

public class A extends java.lang.Object {
	public int number;

	public String toString() {
		return new String("Value : " + number);
	}
}
In this example, we implicitly state that we extend java.lang.Object, and override the functionality of the toString() method by providing our own function. 

In the following example, we inherit from class A, which means that B will also contain a field called "number", and a function called toString().

public class B extends A {
	public void increment() {
		number++;
	}
}

Q: what does word "private" for field in java class mean? Write a line of code
A: The "private" access modifier means that only code inside the class itself can access the field (Methods, Variables and Constructors).
public class Customer {
 private   String email;
}

Q: what is camel case in Java? Please  write how would name class that tests CSS selector
A: CamelCase (also known as Upper CamelCase) is where each new word begins with a capital letter (e.g., CamelCase, CustomerAccount, PlayingCard). Applied to classes, interfaces 
public class FindByCSS {
......
}

JUNIT
* when do we use setUp() method in Seleium/JUnit test?
>>> a test which needs to be executed before all the other test methods is named as “SetUp”
* when do we use tearDown() method in Seleium/JUnit test?
>>> method which will be executed just before stopping the test execution is termed as “TearDown”
* when do we use assertEquals(expected, actual) method. What each parameter means?
>>> To check that two values are equal. Result is Passed if expected = actual and Failed if expected <> actual. Messages are only displayed when an assert fails.

************************************************************
************************************************************
************************************************************
JAVA recap
Q: What each line of code in MailTest mean?
