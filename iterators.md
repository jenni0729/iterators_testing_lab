##Descriptions of Iterators

###Instructions
Below you will find a list of methods. In the space provided below each, please provide a brief description of what this method does based upon your review of the Docs. 

###Array methods:
May be helpful to look in [Enumerable](http://ruby-doc.org/core-2.2.0/Enumerable.html) as well...

####select: Code in a block is applied to an array, and any value in the array which is proven true according to the condition specified in the block is added to the array which results. If a block is not given, an enumerator is returned. Similar to filter method in Javascript. 

####reject: Deletes items from array that are equal to the parameter. Returns the last value deleted, or nil if the parameter didn't match any object in the array.

####map: Same as collect. A condition is applied once to every member of an enum. Subsequent values populate the array that's returned. If no condition given, an enumerator is returned. 

####detect: Returns first value in an enumerator to prove true when passed to block. If no object matches, returns nil. If no block is given, an enumerator is returned instead.

####inject: Same as reduce method. Apply a specified operation to reduce the array to one value. The final cumulative value is the return value for the method - can be through concatenation, etc. 


####partition: Provides two sub-arrays in a main array as the output. The first sub-array contains the values which prove to be true based on the condition within a block. The second sub-array contains the remaining values. 

####sort: The specified method or condition for sorting is applied to the enum. The result is an array with the propertly-sorted values.

####one: A condition is applied to an enum. If the enum values return exactly one true situation, then true will be returned. Otherwise, false will be returned. 

####none: A condition is applied to an enum. If none of the enum values return true, then true will be returned. Otherwise, false will be returned.

####all: The opposite affect of the none method. If a condition is applied to an enum, and the value false or nil is never returned, then true will be returned. Otherwise, false will be. Like every method in JS. 

####empty?: If no elements are inside the array, true is returned. Otherwise, false is. 

####eql?: Returns true if two objects are pointing at the same value. Otherwise, false. 

####include?: If a specified parameter exists in a given array, true is returned. Otherwise, false. 

####nil?: Checks to see if receiving array is nil. Otherwise, false. 

###Hash methods: Creates a Fixnum hash value for a parameter, which is utilized with eql? to determine whether or not two parameters point to the same hash key. 

####key?: If the parameter/key exists in the presented hash, true is returned. Otherwise, false. 

####keys: The keys from the presented hash are returned to populate a new array.

####delete: Applied to hashes. Deletes the key/parameter; Returns the value paired with a particuar key/parameter. If key/parameter doesn't exist in hash, returns the default value. 

Question: el is inherent short way of saying element? 
Question: default value? 

####delete_if: Condition is applied to a hash. Every key-value pair which evaluates to true is removed, and remaining key:value pairs will populate returned hash. If no block is given, an enumerator is returned. Use if trying to delete based on a value. For every occurance of a key:value pair where the value returned is true, it will immediately delete it. 
