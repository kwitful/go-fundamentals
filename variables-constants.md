	package main
 	import "fmt"


# VARIABLES

### Variables are declared as follows:
	'''go
	 // var keyword, variable name, variable type
	var carBrand string'''
__This variable is not initialized (we did not assign a value to it with the = sign), its value is an empty string""__

	var carModel int  
 __This variable is also not initialized its value is 0__
 
 	carModel = 1970  // You can change it later on

__It is possible to declare and initialize variables at the same time__

	var carCity string = "New York" // We have declared a variable carCity and initialized it with the value "New York"
	carCity = "Boston"              // We can change it to something else later on with the = sign

__It is possible to declare multiple variables at once like this:__

	var carMotor, carMPG float32 = 200.45, 32.7

 __It is also possible to declare variables like this, it is especially useful when you have several variables to declare:__

	var (
		carNameOne    string = "Corolla"
		carNameTwo    string = "Grandland"
		carNameThree  string = "Golf"
		carModelOne   int    = 2008
		carModelTwo   int    = 2022
		carModelThree int    = 2018
	)
