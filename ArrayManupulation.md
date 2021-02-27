### Manipulate Arrays With push()
**.push()** takes one or more parameters and "pushes" them onto the end of the array..
Example:

    var arr1 = [1,2,3];
    arr1.push(4);
    // arr1 is now [1,2,3,4]
    
    var arr2 = ["Stimpson", "J", "cat"];
    arr2.push(["happy", "joy"]);
    // arr2 now equals ["Stimpson", "J", "cat", ["happy", "joy"]]

Push `["dog", 3]` onto the end of the `myArray` variable..

    var myArray =  [["John",  23],  ["cat",  2]];
    myArray.push(["dog",  3]);
    console.log(myArray); //[ [ 'John', 23 ], [ 'cat', 2 ], [ 'dog', 3 ] ]

### Manipulate Arrays With pop()
`.pop()` is used to "pop" a value off of the end of an array. We can store this "popped off" value by assigning it to a variable. In other words, `.pop()` removes the last element from an array and returns that element.

Any type of entry can be "popped" off of an array - numbers, strings, even nested arrays.
Example:

    var threeArr = [1, 4, 6];
    var oneDown = threeArr.pop();
    console.log(oneDown); // Returns 6
    console.log(threeArr); // Returns [1, 4]

Use the `.pop()` function to remove the last item from `myArray`, assigning the "popped off" value to `removedFromMyArray`..

    var myArray =  [["John",  23],  ["cat",  2]];
    var removedFromMyArray;
    removedFromMyArray = myArray.pop();
    console.log(removedFromMyArray); //[ 'cat', 2 ]

### Manipulate Arrays With shift()
`pop()` always removes the last element of an array. What if you want to remove the first?

That's where `.shift()` comes in. It works just like `.pop()`, except it removes the first element instead of the last.
Example:

    var ourArray = ["Stimpson", "J", ["cat"]];
    var removedFromOurArray = ourArray.shift();
    // removedFromOurArray now equals "Stimpson" and ourArray now equals ["J", ["cat"]].

Use the `.shift()` function to remove the first item from `myArray`, assigning the "shifted off" value to `removedFromMyArray`.

    var myArray =  [["John",  23],  ["dog",  3]];
    var removedFromMyArray;
    removedFromMyArray = myArray.shift(); //[ 'John', 23 ]

### Manipulate Arrays With unshift()
Not only can you `shift` elements off of the beginning of an array, you can also `unshift` elements to the beginning of an array i.e. add elements in front of the array.

`.unshift()` works exactly like `.push()`, but instead of adding the element at the end of the array, `unshift()` adds the element at the beginning of the array.
Example:

    var ourArray = ["Stimpson", "J", "cat"];
    ourArray.shift(); // ourArray now equals ["J", "cat"]
    ourArray.unshift("Happy");
    // ourArray now equals ["Happy", "J", "cat"]

Add `["Paul",35]` to the beginning of the `myArray` variable using `unshift()`.

    var myArray =  [["John",  23],  ["dog",  3]];
    myArray.shift();
    myArray.unshift(["Paul",35]);
    console.log(myArray); //[ [ 'Paul', 35 ], [ 'dog', 3 ] ]
