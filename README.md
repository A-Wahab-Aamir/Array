# WHAT IS ARRAY USING DIAGRAM

![image](https://github.com/A-Wahab-Aamir/Array/assets/83786802/3ced9b50-b986-4756-a574-78f687d82b51)


# What is Array in JavaScript?
JavaScript Array is a data structure that allows you to store and organize multiple values within a single variable. It is a versatile and dynamic object. It can hold various data types, including numbers, strings, objects, and even other arrays. Arrays in JavaScript are zero-indexed i.e. the first element is accessed with an index 0, the second element with an index of 1, and so forth.



# METHOD IN JS

//Example
var ary = ["A", "B", "C", "D", "E"];

//length
console.log(ary.length); //5

//push
console.log(ary.push("F")); //6

//pop
console.log(ary.pop()); //"F"

//unshift
console.log(ary.unshift("F")); //6

//shift
console.log(ary.shift()); //"F"

//splice(insert)
console.log(ary.splice(3, 0, "F")); //[]

//splice(remove)
console.log(ary.splice(3, 1)); //["F"]

//indexOf
console.log(ary.indexOf("D")); //3

//lastIndexOf
console.log(ary.lastIndexOf("D")); //3

//join
console.log(ary.join(":")); //"A:B:C:D:E"

//reverse
console.log(ary.reverse()); //["E", "D", "C", "B", "A"]

//sort
console.log(ary.sort()); //["A", "B", "C", "D", "E"]

//some
console.log(ary.some(function(item) {
	return item === "C";
})); //true

//every
console.log(ary.every(function(item) {
	return item.length === 1;
})); //true

//forEach
console.log(ary.forEach(function(item) {
	return item;
})); //undefined

//reduce
console.log(ary.reduce(function(prevItem, item) {
	return prevItem + item;
})); //"ABCDE"

//reduceRight
console.log(ary.reduceRight(function(prevItem, item) {
	return prevItem + item;
})); //"EDCBA"

//map
console.log(ary.map(function(item) {
	return item + item;
})); //["AA", "BB", "CC", "DD", "EE"]

//filter
console.log(ary.filter(function(item) {
	return item > "C";
})); //["D", "E"]

//slice
console.log(ary.slice(2, 4)); //["C", "D"]

//concat
console.log(ary.concat(["G", "H"])); //["A", "B", "C", "D", "E", "G", "H"]

# for help
### https://www.scaler.com/topics/javascript/javascript-array/

# YOUTUBE VIDEO
### https://www.youtube.com/watch?v=rq_5uPKjgsY
