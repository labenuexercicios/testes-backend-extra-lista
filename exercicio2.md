```javascript
const divideNums = (num1, num2) => {
    if (typeof num1 !== "number" || typeof num2 !== "number") {
        const error = {
            isError: true
        }

        return error
    }

    const result = {
        divisao: num1 / num2,
        resto: num1 % num2
    }

    return result
}

console.log(divideNums(6,2))
console.log(divideNums(5,3))
console.log(divideNums("a","b"))
```
