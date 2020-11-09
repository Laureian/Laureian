# Javascript Resources

My private Javascript resources page with interesting courses, articles, libraries.

## Courses
- https://frontendmasters.com/courses/getting-started-javascript-v2/

## Excercises
- https://static.frontendmasters.com/resources/2019-05-08-getting-into-javascript/getting-into-javascript.zip

## Types&Corecion
`In Javascript variables don't have types, values do.`
- typeof null -> "object"
- typeof undeclaredVariable -> "undefined"
- typeof function() {} -> "function"
- typeof [1,2,3] -> "object"
- typeof {} -> "object"

`let name = "Maciej";`
`let something = name / 2;`

`something; // NaN`
`Number.isNaN(something); // true`

## new operator

| don't use   | use       |
|-------------|:---------:|
| Object()    | String()  |
| Array()     | Boolean() |
| Function()  | Number()  |
| Date()      |           |
| RegExp()    |           |
| Error()     |           |

## Falsy values
- "" - empty string
- 0, -0
- null
- NaN
- false
- unefined

Everything else is thruthy

## Closures
- https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/scope%20%26%20closures/ch1.md
- http://ryanmorr.com/understanding-scope-and-context-in-javascript/
- https://medium.com/dailyjs/i-never-understood-javascript-closures-9663703368e8
- http://www.algosmart.pl/zakresy-powtorka-reactjs-7/
- https://v8.dev/blog/ignition-interpreter
- https://www.freecodecamp.org/news/whats-a-javascript-closure-in-plain-english-please-6a1fc1d2ff1c/
- https://en.wikipedia.org/wiki/Closure_(computer_programming)
- https://www.freecodecamp.org/news/lets-learn-javascript-closures-66feb44f6a44/
