# SLICES IN GO

### What is a slice?

A slice is a data structure in Go. It is used to work with sequences of data. It is similar to an array with certain, profound advantages and disadvantages:
#### The Advantages:
1) Slices are dynamically sized and, therefore, offer more flexibility when compared to arrays
2) There are various, practical built-in functions in Go that make working with slices efficient
3) They are more suitable to be used as function arguments when compared to arrays

#### The Disadvantages:
1) Slices having a dynamic size can be problem for situations in which you specifically need a data structure with a fixed size
2) They directly modify the array on which they are based. This can be a problem if you aren't careful


### Declaring Slices


   
