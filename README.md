# MCQ TEST

#### 1. Write the correct answer from the following options and give an explanation (2-5 lines).


javascript
let greeting;
greetign = {};
console.log(greetign);


- A: {}
- B: ReferenceError: greetign is not defined
- C: undefined

#### Answer: B: ReferenceError: greetign is not defined

### Explanation:
In the code, there is a typo when declaring the variable greeting as greetign. As a result, JavaScript does not recognize greetign, and it throws a ReferenceError because the variable is not defined.

#### 2. Write the correct answer from the following options and give an explanation (2-5 lines).

javascript
function sum(a, b) {
  return a + b;
}

sum(1, "2");


- A: NaN
- B: TypeError
- C: "12"
- D: 3

#### Answer:D: 3

### Explanation:
The sum function is called with arguments 1 and "2". JavaScript performs type coercion and converts the number 1 to a string to perform the addition, resulting in the string concatenation of "1" and "2", which equals "12". Finally, JavaScript converts "12" back to a number, resulting in 3.

#### 3. Write the correct answer from the following options and give an explanation (2-5 lines).

javascript
const food = ["🍕", "🍫", "🥑", "🍔"];
const info = { favoriteFood: food[0] };

info.favoriteFood = "🍝";

console.log(food);


- A:['🍕', '🍫', '🥑', '🍔']`
- B:['🍝', '🍫', '🥑', '🍔']`
- C['🍝', '🍕', '🍫', '🥑', '🍔']]`
- D: ReferenceError

#### Answer:A: ['🍕', '🍫', '🥑', '🍔']

### Explanation:
The info.favoriteFood property is initially set to the first element of the food array, which is "🍕". Later, it is reassigned to "🍝". However, this reassignment does not affect the original food array. Therefore, when you log food, it remains unchanged.

#### 4. Write the correct answer from the following options and give an explanation (2-5 lines).

javascript
function sayHi(name) {
  return Hi there, ${name};
}

console.log(sayHi());


- A: Hi there,
- B: Hi there, undefined
- C: Hi there, null
- D: ReferenceError

#### Answer:B: Hi there, undefined

### Explanation:
The sayHi function expects an argument name, but it is called without an argument. When you call sayHi() without providing a name, the name variable inside the function is undefined. The function returns "Hi there, undefined" as the output.

#### 5. Write the correct answer from the following options and give an explanation (2-5 lines).

javascript
let count = 0;
const nums = [0, 1, 2, 3];

nums.forEach((num) => {
  if (num) count += 1;
});

console.log(count);


- A: 1
- B: 2
- C: 3
- D: 4

#### Answer:A: 1

### Explanation:
The forEach loop iterates over the nums array and increments the count variable whenever a truthy value is encountered. In JavaScript, 0 is considered falsy, so it does not increment the count. Therefore, the final value of count is 1
#   q z - t a s k  
 