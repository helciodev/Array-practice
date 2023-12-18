# Array practice

Identify the time complexity of each of these functions with a 1 sentence
justification for your answer. Assume `arr` is an array of length _n_.

## `arr.push()`

Time complexity: O(1)
Space complexity: O(1)
Justification: _The number of operations to add a new element to the end of `arr` will always be same assigning the `arr.length` as the new element `index` and increasing the `arr.length + number of elements to add` doesn't matter the size of the array, so it's time complexity is constant_.

[push on MDN][push]

## `arr.pop()`

Time complexity: O(1)
Space complexity: O(1)
Justification: _It will be same as push method, the number of operations will always be same and it will only remove the last element which will always be at the position `arr.length - 1` thus not affecting the other elements in the array, therefore we can say it will be constant time complexity_

[pop on MDN][pop]

## `arr.shift()`

Time complexity: O(n)
Space complexity: O(n)
Justification: _It will have a linear time complexity and space complexity as the number of operations is greater than the two methods above making it linear, besides adding an new element with index 0 it has the calculate every other element in the `arr` array according to the number of element added a the start of the array_

[shift on MDN][shift]

## `arr.unshift()`

Time complexity: O(n)
Space complexity: O(n)
Justification: _It will be very similar to the `shift` method therefore the time and space complexity will be linear as well_

[unshift on MDN][unshift]

## `arr.splice()`

Time complexity: O(1)
Space complexity: O(1)
Justification: _I think it will be constant time and space complexity as it will basically always perform the same number of operations without needing to iterate through every element in the `arr` array_

[splice on MDN][splice]

## `arr.slice()`

Time complexity: O(?)
Space complexity: O(?)
Justification: _Fill this in_

[slice on MDN][slice]

## `arr.indexOf()`

Time complexity: O(?)
Space complexity: O(?)
Justification: _Fill this in_

[indexOf on MDN][indexOf]

## `arr.map()`

Time complexity: O(?)
Space complexity: O(?)
Justification: _Fill this in_

[map on MDN][map]

## `arr.filter()`

Time complexity: O(?)
Space complexity: O(?)
Justification: _Fill this in_

[filter on MDN][filter]

## `arr.reduce()`

Time complexity: O(?)
Space complexity: O(?)
Justification: _Fill this in_

[reduce on MDN][reduce]

## `arr.reverse()`

Time complexity: O(?)
Space complexity: O(?)
Justification: _Fill this in_

[reverse on MDN][reverse]

## `[...arr]`

Time complexity: O(?)
Space complexity: O(?)
Justification: _Fill this in_

[spread on MDN][spread]

[push]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push
[pop]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop
[shift]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift
[unshift]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift
[splice]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice
[slice]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice
[indexOf]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf
[map]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
[filter]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter
[reduce]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce
[reverse]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reverse
[spread]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax
