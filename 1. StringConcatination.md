### Concatenating Strings with Plus Operator
In JavaScript, when the  `+`  operator is used with a  `String`  value, it is called the  concatenation  operator. You can build a new string out of other strings by  concatenating  them together.
**Example**

    'My name is Alan,' + ' I concatenate.'
>**Note**
Watch out for spaces. Concatenation does not add spaces between concatenated strings, so you'll need to add them yourself.

**Example**

    var ourStr = "I come first. " + "I come second.";
    // ourStr is "I come first. I come second."
Build `myStr` from the strings `"This is the start. "` and `"This is the end."` using the `+` operator.

    var myStr; 
    myStr =  "This is the start. "  +  "This is the end.";
    console.log(myStr); //This is the start. This is the end.
### Concatenating Strings with the Plus Equals Operator
We can also use the  `+=`  operator to  concatenate  a string onto the end of an existing string variable. This can be very helpful to break a long string over several lines.

>**Note**
Watch out for spaces. Concatenation does not add spaces between concatenated strings, so you'll need to add them yourself.

**Example**

    var ourStr = "I come first. ";
    ourStr += "I come second.";
    // ourStr is now "I come first. I come second."

Build `myStr` over several lines by concatenating these two strings: `"This is the first sentence. "` and `"This is the second sentence."` using the `+=` operator. Use the `+=` operator similar to how it is shown in the editor. Start by assigning the first string to `myStr`, then add on the second string.

    var myStr;
    myStr =  "This is the first sentence. ";
    myStr +=  "This is the second sentence.";
    console.log(myStr); //This is the first sentence. This is the second sentence.
### Constructing Strings with Variables
Sometimes you will need to build a string, [Mad Libs](https://en.wikipedia.org/wiki/Mad_Libs) style. By using the concatenation operator (`+`), you can insert one or more variables into a string you're building.
**Example**

    var ourName = "freeCodeCamp";
    var ourStr = "Hello, our name is " + ourName + ", how are you?";
    // ourStr is now "Hello, our name is freeCodeCamp, how are you?"

Set  `myName`  to a string equal to your name and build  `myStr`  with  `myName`  between the strings  `"My name is "`  and  `" and I am well!"`
var myName;
var myStr;
myName =  'Aman';
myStr =  "My name is "  + myName +  " and I am well!";
console.log(myStr); //My name is Aman and I am well!
### Appending Variables to Strings
Just as we can build a string over multiple lines out of string literals, we can also append variables to a string using the plus equals (`+=`) operator.
**Example**

    var anAdjective = "awesome!";
    var ourStr = "freeCodeCamp is ";
    ourStr += anAdjective;
    // ourStr is now "freeCodeCamp is awesome!"

Set `someAdjective` to a string of at least 3 characters and append it to `myStr` using the `+=` operator.

    var someAdjective;
    var myStr =  "Learning to code is ";
    someAdjective =  "Awesome"
    myStr += someAdjective;
    console.log(myStr); //Learning to code is Awesome
