```javascript
// 1. criar uma variável para armazenar o resultado
// 2. iterar a string do fim ao início
// 2.1 adiciona o caractere na variável resultado
// 3. retornar a variável resultado

const inverteString = (str) => {
    let result = ""

    for (let i = str.length - 1; i >= 0; i--) {
        // result = result + str[i]
        result += str[i]
    }

    return result
}

console.log(inverteString("abcdefg"))

// const inverteStringNativo = (str) => str.split("").reverse().join("")
// console.log(inverteStringNativo("abcdefg"))
```
