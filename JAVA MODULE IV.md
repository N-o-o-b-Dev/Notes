
JAVA MODULE IV : 

 CLASSES & OBJECTS : -

	Classes and objects are fundamental concepts in object-oriented programming (OOP). Here's a clear explanation:
	
	Class Car
		|--> String Color;--->Variable
		     Void Sound();--->Method

	Person1 need RED & Sony
	Person2 need Blue & BOSE
	Person3 need Black & JBL


public class Car {

		String Color;
		
		Void Sound(String Sound){
		
		System.Out.println(Sound); }


public static void main(String[] args){

	Car Person1 = new Car();
	Person1.Color = "RED";
	Person1.Sound("Sony");

	Car Person2 = new Car();
	Person1.Color = "Blue";
	Person1.Sound("BOSE");

	Car Person1 = new Car();
	Person1.Color = "Black";
	Person1.Sound("JBL");

	System.Out.println(Person1.color);
	System.Out.println(Person2.color);
	System.Out.println(Person3.color);

}

-------------------------------------------+++++++++++++++++-------------------------------

CONSTRUCTORS : -

    A constructor in Java is a special method that is used to initialize objects. The       constructor is called when an object of a class is created. It can be used to set initial values for object attributes:

 1. Default Constructor
      Definition: A constructor that takes no parameters.

      Purpose: Initializes members with default values.

      Provided by compiler? Yes, if no constructors are defined manually


 2. Parameterized Constructor
            Definition: A constructor that takes arguments to initialize members with specific values.

              Purpose: Provides custom initialization when an object is created



 3. Copy Constructor
            Definition: A constructor that creates a new object as a copy of an existing                     object.

              Purpose: Ensures proper copying of object values (especially when pointers or                   dynamic memory are involved).


	
				
			
	
