---
id: qjxxlwlwhrt99ovxlxn3n3a
title: Boolean Logic & Logical Operators
desc: ""
updated: 1673158868893
created: 1673158868893
tag: JS
---

---

##### Theory

1. Boolean logic is a branch of computer science, which uses true & false values to solve complex logical problems, and in order to do that it uses several logical operators to combine true & false values.
2. Much like we uses arithematic operator to combine numeric values.
3. But in this lecture we are going to talk only about `AND`, `OR` and `Not` operators.
4. Boolean logic is not specific to JS. This is true for all Programming.
5. Boolean Logic: AND, OR & NOT (picture)
   - ![[1.png|300]]
6. An Example (picture)
   - ![[456.png|300]]

---

##### Example Code (code)

```js

const hasDriverLicense = true; // A
const hasGoodVision = true; // B

console.log(hasDriverLicense && hasGoodVision);
console.log(hasDriverLicense || hasGoodVision);
console.log(!hasDriverLicense );

// if (hasDriverLicense && hasGoodVision) {
// 	console.log('Sarah is able to Drive');
// } else {
// 	console.log('Someone else should Drive...');
// }

const isTired = false: // C
console.log(hasDriverLicense && hasGoodVision && isTired);

if (hasDriverLicense && hasGoodVision && !isTired) {
	console.log('Sarah is able to Drive');
} else {
	console.log('Someone else should Drive...');
}

```

---
