# Closure, Recursion and Callbacks

Closure, Recursion and Callbacks are three concepts that are quite important in advanced JavaScript. This exercise allows you to demonstrate that you understand the basics of these three concepts.

## 1. Closure

### 1.1. Closure Countdown

- Create a closure function which will count down a number from 5 to 1 by calling the following code:

```
console.log(subtract());
console.log(subtract());
console.log(subtract());
console.log(subtract());
console.log(subtract());
```

### 1.2 Closure Todo List

- Create a closure function which adds todo items to a private array variable (which can't be changed from outside the function).

```
console.log(addTodo('wash dishes'));
console.log(addTodo('go shopping'));
console.log(addTodo('go to bed'));
```

- The output should look like this:

```
Things to do = 1 and they are: wash dishes.
Things to do = 2 and they are: wash dishes, go shopping.
Things to do = 3 and they are: wash dishes, go shopping, go to bed.
```



## 2. Recursion

### 2.1. Recursive Number Adder

- Complete this recursive function which adds numbers:

```
const nums = [1, 2, 3, 4, 5, 6];
function add(nums) {
    ... // base case, return statement
    ... // recurcive case
}
console.log(add(nums));
```

### 2.2. Recursive Count Function

- Explain why this recursive function counts down as well as up:

```
function counter(value, limit) {
	if (value === limit) {
		console.log(value);
	} else {
		console.log('going up:', value); // on the way down / going deeper (increment)
		counter(value + 1, limit);
		console.log('going down:', value); // on the way up / coming up from the depths (decrement)
	}
}
counter(0, 3);
```

## 3. Callbacks

- nnn
