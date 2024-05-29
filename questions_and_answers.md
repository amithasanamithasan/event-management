<div align="center">
  <img height="60" src="https://edurev.gumlet.io/AllImages/original/ApplicationImages/CourseImages/944e5d47-8c55-4a89-91e5-22ab5f2798fc_CI.png">
  <h1>MCQ TEST</h1>
</div>

###### 1. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
let greeting;
greetign = {};
console.log(greetign);
```

- A: `{}`
- B: `ReferenceError: greetign is not defined`
- C: `undefined`

<details><summary><b>Answer</b></summary>
<p>

#### Answer: A 

<i> JavaScript, and it is correctly declared and assigned before being logged to the console.</i>

</p>
</details>

###### 2. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
function sum(a, b) {
  return a + b;
}

sum(1, "2");
```

- A: `NaN`
- B: `TypeError`
- C: `"12"`
- D: `3`

<details><summary><b> </b></summary>
<p>

#### Answer: 12

<i>জাভাস্ক্রিপ্টে একটি সংখ্যা এবং একটি স্ট্রিং সহ  অপারেটর ব্যবহার করা হয়, তখন সংখ্যাটি একটি স্ট্রিংয়ে রূপান্তরিত হয় এবং অন্য স্ট্রিংয়ের সাথে সংযুক্ত হয়।</i>

</p>
</details>

###### 3. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
const food = ["🍕", "🍫", "🥑", "🍔"];
const info = { favoriteFood: food[0] };

info.favoriteFood = "🍝";

console.log(food);
```

- A: `['🍕', '🍫', '🥑', '🍔']`
- B: `['🍝', '🍫', '🥑', '🍔']`
- C: `['🍝', '🍕', '🍫', '🥑', '🍔']`
- D: `ReferenceError`

<details><summary><b>Answer</b></summary>
<p>

#### Answer: A

<i>info.favoriteFoodকে "🍝"-এ পুনরায় বরাদ্দ করেন, তখন এটি তথ্য অবজেক্টে প্রিয় খাদ্য সম্পত্তির মান পরিবর্তন করে, কিন্তু এটি খাদ্য অ্যারেকে প্রভাবিত করে না। ফুড অ্যারে অপরিবর্তিত থাকে, তাই যখন console.log(food) কল করা হয়, তখন এটি মূল অ্যারেটিকে আউটপুট করে:</i>

</p>
</details>

###### 4. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
function sayHi(name) {
  return `Hi there, ${name}`;
}

console.log(sayHi());
```

- A: `Hi there,`
- B: `Hi there, undefined`
- C: `Hi there, null`
- D: `ReferenceError`

<details><summary><b>Answer</b></summary>
<p>

#### Answer: B

<i>যখন sayHi ফাংশনটি একটি যুক্তি ছাড়াই কল করা হয়, তখন নাম প্যারামিটারটি ডিফল্টরূপে অনির্ধারিত থাকে। </i>

</p>
</details>

###### 5. Write the `correct answer` from the following options and give an explanation (2-5 lines).

```javascript
let count = 0;
const nums = [0, 1, 2, 3];

nums.forEach((num) => {
  if (num) count += 1;
});

console.log(count);
```

- A: 1
- B: 2
- C: 3
- D: 4

<details><summary><b>Answer</b></summary>
<p>

#### Answer: 3

<i>Write your explanation here</i>

</p>
</details>
