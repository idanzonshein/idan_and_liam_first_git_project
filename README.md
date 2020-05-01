# My 4 Favorite Ruby Methods 

### `.pop`
Removes the last element in an array and returns it.
```
a = [ "a", "b", "c", "d" ]
a.pop     #=> "d"
a.pop(2)  #=> ["b", "c"]
```

### `.iclude?`
Checks if an item is in an array.
```
a = [ "a", "b", "c" ]
a.include?("b")   #=> true
a.include?("z")   #=> false
```

### `.unshift`
Adds elements to the beginning of an array. 
```
a = [ "b", "c", "d" ]
a.unshift("a")   #=> ["a", "b", "c", "d"]
a.unshift(1, 2)  #=> [ 1, 2, "a", "b", "c", "d"]
```

### `.length`
Returns the number of elements in an array. 
```
[ 1, 2, 3, 4, 5 ].length   #=> 5
[].length                  #=> 0
```