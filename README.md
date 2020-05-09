# Lab-6- Answers 

Lab 6 Answers
Qn 2  A method is a block of code which only runs when it is called. The program causes the statements to be executed by calling the method and specifying any required tasks. Methods are also referred to as functions or procedures in other programming languages and makes the application development process much faster by using divide and conquer.  Methods are used to perform certain actions and are available in the .NET framework Class Library, and various class libraries.  
A)	Scope is an enclosing context or region that defines where a name can be used without qualification. It is statement block enclosed by braces. 

B)	Static – These are objects/ members of a class that cab be accessed directly from the class, whereas the Non- Static are objects/Members that can only be accessed from the instance it belongs to. 

C)	Return Type,  this is a data type of a value that the method returns. If a method is not returning a value, then its void. 

D)	Method Name, this is a unique identifier and it is case sensitive. It cannot be same as any other identifier declared in the class.


E)	Parameters,  these are enclosed between parentheses, and they are used to pass and receive data from a method. The parameter list refers to the type, order, and number of the parameters of a method. Parameters are optional; that is, a method may contain no parameters.

F)	Method body, this contains the set of instructions needed to complete the required activity.

Qn 3.	User-defined methods are written by the user and are hidden from other methods. Well as Methods provided by the framework can be reused from several locations in an app. 
	
User defined methods are methods created by the user that are not in the visual studio libraries. These specify the required method arguments. The user must construct everything to be used. Programmers are advised not to reinvent the wheel, but to use the existing libraries to avoid the coding issue. 

Qn 4.	Static methods belong to the class and a non-static method belongs to an object of a class. The static methods can be accessed directly from the class, while non-static methods must be accessed from an instance. Non-static methods are also referred to as instance methods. 


Qn 5.	namespace Lab6Qn5
{
    public class Dog
    {
       string Name = "Fido";

        static void Main(string[] args)
        {
            Dog myDog = new Dog();
            myDog.Name = "Fido";
                   
            Console.WriteLine("{0} is Barking...", myDog.Name);
        }
Qn 6.	
public class Dog
    {
      string Name;
      string Bark;
      string trickName;

        static void Main(string[] args)
        { 
            Dog myDog = new Dog();
            myDog.Name = "Fido";
            Console.WriteLine("{0} is Barking...", myDog.Name);

            Dog Bark = new Dog();
            Bark.Bark= "woo, wooo";
            Console.WriteLine( Bark.Bark);

      Dog doTrick = new Dog();
      doTrick.trickName = "Fetch";
      Console.WriteLine("{0} is so smart! {0} is doing a(n) {1}", myDog.Name, doTrick.trickName);
        }                 
