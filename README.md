# Iterators Lab

### Description

In the iterators lab we will be continuing our exploration of
iterators. We have a series of challenges that require you to use the
iterators we discussed in class. We will try to use various testing
methods to verify that your code is working.

### Phase-1

Research the following term and summarize your findings on it two to
three sentences:

* `higher-order function` - A function that takes another function (or functions) as input and/or returns a function(s) as its output.


Update this README with a description of each of the following and an
example you've created:

* `forEach`: The forEach() method executes a provided function once per array element. E.g NumArr.forEach(function(n){ return n*2;})
[note](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)

* `map`: The map() method creates a new array with the results of calling a provided function on every element in this array. E.g var numSquare = numArr.map(function(n){return n*n;})
[note](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

* `filter`: The filter() method creates a new array with all elements that pass the test implemented by the provided function. E.g var greater_than_5 = numArr.filter(function(n){return n > 5;})
[note](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)

* `reduce`: The reduce() method applies a function against an accumulator and each value of the array (from left-to-right) has to reduce it to a single value. E.g mult_Number = numArr.reduce(function(a,b){return a * b;})
[note](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)

* `some`: The some() method tests whether some element in the array passes the test implemented by the provided function.
[note](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/some)

* `every`: [note](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every)

Use the notes provided to help guide you explanation.

### Phase-2

* Run `npm install` from the `iterators_lab` directory.
* Looks at the tests we've written in the `test` folder. Run the tests
  with `npm test` (also from the `iterators_lab` directory). They
  should all fail.
* Get all of the tests to pass by writing the necessary code in
  `src/iterators.js`.

### Phase-3

Refactor the following code using `map` to make only one call to the `map` function versus the two below.


```
var myNumbers = [ -1, 2, -3, 4, -5, 6];

var square = function(num) {
	return num * num;
};

var sqrRoot = function(num) {
	return Math.sqrt(num);
};


var sqrNumbers = myNumbers.forEach(square);
var absNumbers = sqrNumbers.map(sqrRoot);
```




