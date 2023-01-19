##[Strings](./topics/jsStrings.md/#Strings)

### String Methods

[Back to Table of Contents](../README.md/#Table-of-Contents)

#### length
The .length property returns the number of characters in a string.
```javascript
let str = "Hello, World!";
let strLength = str.length;
console.log(strLength); // Output: 13
```

#### concat
The .concat(string1, string2, ...) method concatenates one or more strings to the calling string and returns a new string.
```javascript
let str = "Hello";
let newStr = str.concat(", ", "World!");
console.log(newStr); // Output: "Hello, World!"
```
[Back to Table of Contents](../README.md/#Table-of-Contents)

#### substring
The substring() method returns a subset of a string between a start and end index
```javascript
let str = "Hello World!";
let sub = str.substring(2, 8);
console.log(sub); // "llo W
```

#### slice
The .slice(start, end) method returns a subset of a string between a start and end index
```javascript
let str = "Hello World!";
let slc = str.slice(2, 8);
console.log(slc); // "llo Wo"
```

[Back to Table of Contents](../README.md/#Table-of-Contents)

#### substr
The .substr(start, length) method returns a subset of a string starting from a specified index and with a specified length
```javascript
let str = "Hello World!";
let sub = str.substr(2, 6);
console.log(sub); // "llo Wo"
```

#### replace
The .replace(searchValue, newValue) method replaces a specified value with another value in a string
```javascript
let str = "Hello World!";
let newStr = str.replace("World", "Universe");
console.log(newStr); // "Hello Universe!"
```

[Back to Table of Contents](../README.md/#Table-of-Contents)

#### indexOf
The .indexOf(searchValue, start) method returns the first index at which a given element can be found in the array, or -1 if it is not present
```javascript
let str = "Hello World!";
let index = str.indexOf("o");
console.log(index); // 4
```

#### lastIndexOf
The .lastIndexOf(searchValue, start) method returns the last index at which a given element can be found in the array, or -1 if it is not present
```javascript
let str = "Hello World! Hello World!";
let index = str.lastIndexOf("o");
console.log(index); // 15
```

[Back to Table of Contents](../README.md/#Table-of-Contents)

#### toString
The .toString() method returns the value of a string object
```javascript
let str = new String("Hello World!");
console.log(str.toString
```

#### trim
The .trim() method removes whitespace from the beginning and end of a string.
```javascript
let str = "    Hello, World!    ";
let newStr = str.trim();
console.log(newStr); // Output: "Hello, World!"
```

[Back to Table of Contents](../README.md/#Table-of-Contents)

#### repeat
The .repeat(count) method returns a new string with the specified number of copies of the original string.
```javascript
let str = "Hello";
let newStr = str.repeat(3);
console.log(newStr); // Output: "HelloHelloHello"
```

#### startsWith
The .startsWith(searchString, position) method returns a boolean indicating whether a string starts with the specified string at the specified position.
```javascript
let str = "Hello, World!";
let result = str.startsWith("Hello");
console.log(result); // Output: true
```

[Back to Table of Contents](../README.md/#Table-of-Contents)

#### endsWith
The .endsWith(searchString, length) method returns a boolean indicating whether a string ends with the specified string at the specified position.
```javascript
let str = "Hello, World!";
let result = str.endsWith("World!");
console.log(result); // Output: true
```

#### includes
The .includes(searchString, position) method returns a boolean indicating whether a string contains the specified string at the specified position.
```javascript
let str = "Hello, World!";
let result = str.includes("World");
console.log(result); // Output: true
```

[Back to Table of Contents](../README.md/#Table-of-Contents)

#### search
The .search(searchValue) method searches a string for a specified value and returns the position of the match.
```javascript
let str = "Hello World!";
let index = str.search("World");
console.log(index); // 6
```
#### charAt
The .charAt(index) method returns the character at the specified index in a string.
```javascript
let str = "Hello, World!";
let char = str.charAt(0);
console.log(char); // Output: "H"
```

[Back to Table of Contents](../README.md/#Table-of-Contents)

#### charCodeAt
The .charCodeAt(index) method returns the Unicode of the character at the specified index in a string.
```javascript
let str = "Hello, World!";
let charCode = str.charCodeAt(0);
console.log(charCode); // Output: 72
```

#### toLowerCase
The .toLowerCase() method returns the calling string value converted to lowercase.
```javascript
let str = "Hello, World!";
let newStr = str.toLowerCase();
console.log(newStr); // Output: "hello, world!"
```

[Back to Table of Contents](../README.md/#Table-of-Contents)

#### toUpperCase
The .toUpperCase() method returns the calling string value converted to uppercase.
```javascript
let str = "Hello, World!";
let newStr = str.toUpperCase();
console.log(newStr); // Output: "HELLO, WORLD!"

```

#### localeCompare
The .localeCompare(compareString) method compares the calling string to a specified string in the current locale 
and returns a number indicating whether the calling string is less than, equal to, or greater than the specified string.
```javascript
let str1 = "Hello";
let str2 = "world";
let comparison = str1.localeCompare(str2);
console.log(comparison); // Output: -1 (str1 is less than str2 in lexicographic order)
```

[Back to Table of Contents](../README.md/#Table-of-Contents)

#### split
The .split(separator) method splits a string into an array of substrings, using the specified separator.
```javascript
let str = "Hello, World!";
let strArray = str.split(",");
console.log(strArray); // Output: ["Hello", " World!"]
```

#### match
The .match(searchValue) method searches a string for a match against a regular expression, and returns the matches as an Array object.
```javascript
let str = "Hello World! Hello World!";
let matches = str.match(/Hello/g);
console.log(matches); // ["Hello", "Hello"]
```