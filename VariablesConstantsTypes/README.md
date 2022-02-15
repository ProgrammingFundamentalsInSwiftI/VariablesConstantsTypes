# VariablesConstantsTypes
 
 Swift allows us to create variables and constants.
 
 Remember that these are like boxes that store values inside of them that we can retrieve later.
 
 As an example, I will declare a variable called test and assign it a value of 15
 
 
		 var x = 15
 
 
 Swift has type inference, so Swift already knwos that the type of variable x is an Int
    
 
 We can also specify the variable type, this is useful to let others know what variable type it will be
 
		var x : Int = 15
  
  
  Both variables are of the same value,
 
 
 
 Remember, Swift has four primitive types that we can reference:
 
    	Int
    	Double
    	String
    	Bool
 
 Here are some definitions of each of them
    
    	var a : Int = 20
    	var b : Double = 25.5
    	var c : String = "Hello World!"
    	var d : Bool = true
 
 
 Variables are very useful for storing, retrieving, and modifying data. What if we don't want data to be modified?
 
 Should your name be able to change easily in your app? Birthday, eye color, hair color?
 
 Sometimes we want to have variables that DO NOT change, and these are called CONSTANTS
 
 Constants are declared the same way as variables
 
 
 		let x = 15
 
 
 We can also apply the same logic of type inference the same way we do as variables
 
 		let x : Int = 15
 
 Here are some definitions of each of them
  
 		let a : Int = 20
		let b : Double = 25.5
		let c : String = "Hello World!"
		let d : Bool = true
 
 
 Remember constants cannot change, so if you attempt to modify the constant after it is originally declared you will experience an error!
 
 
