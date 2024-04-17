# CONTROL FLOW STATEMENTS IN GO

There are various control flows in Go that allow you to take actions based on logical conditions or iterate over certain items. These are:

1) If-Else If-Else Statements
2) Switches
3) For Loops

### If-Else Statements
If else statements allow you to take actions based on conditions of your choice:

```Go
	// If - else if - else statements

	var carModel int = 1986

	if carModel > 1972 {
		fmt.Println("The car isn't old")
	} else if carModel > 2010 {
		fmt.Println("The car is quite new")
	} else {
		fmt.Println("The car is old")
	}
```

### Switch
Switches introduce a practical way to act on condition:

```Go
	// Switch
	var carCity string = "New York"

	switch carCity {
	case "New York":
		fmt.Println("The car is in USA")

	case "London":
		fmt.Println("The car is in UK")

	case "Istanbul":
		fmt.Println("The car is in Turkiye")

	}
```


