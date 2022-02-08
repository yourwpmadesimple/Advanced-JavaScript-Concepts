# Advanced JavaScript Concepts
![alt text][javascript]

[javascript]: https://github.com/yourwpmadesimple/javascript-navigation-animation/blob/master/javascript_banner.jpg "Javascript Banner"

## Functions
```javascript
// Function Expression (Can not be Hoisted)
var america = function(){
  console.log('cold')
}

// Function Declaration (Can be Hoisted)
function india(){
  console.log('warm')
}

// Function Invocation/Call/Execution
india()
america()

// Using the 'arguments' reserved variable
function marry(person1, person2){
	console.log(arguments)
	// Will print '{ '0': 'Olga', '1': 'Tafuku' }'
    console.log(Array.from(arguments))
	const statement = `${person1} and ${person2} are finally tying the knot`;
	console.log(statement) 
	// Will print 'Olga and Tafuku are finally tying the knot'
}
marry('Olga', 'Tafuku');