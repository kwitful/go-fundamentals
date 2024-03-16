# VARIABLES

### Variables are declared as follows:

```go

// var keyword, variable name, variable type
var carBrand string

```


__This variable is not initialized (we did not assign a value to it with the = operator), its value is an empty string""__

```go
var carModel int

```  
 __This variable is also not initialized its value is 0__

 ```go
 
 carModel = 1970  // You can change it later on
```

__It is possible to declare and initialize variables at the same time. Note that variables are changeable after they are declared. This why they are called variables__
```go

var carCity string = "New York" // We have declared a variable carCity and initialized it with the value "New York"
carCity = "Boston"              // We can change it to something else later on with the = operator
```

__It is possible to declare multiple variables at once like this:__
```go

var carMotor, carMPG float32 = 200.45, 32.7
```

 __It is also possible to declare variables like this, it is especially useful when you have several variables to declare:__

 ```go

var (
	carNameOne    string = "Corolla"
	carNameTwo    string = "Grandland"
	carNameThree  string = "Golf"
	carModelOne   int    = 2008
	carModelTwo   int    = 2022
	carModelThree int    = 2018
	)
```
