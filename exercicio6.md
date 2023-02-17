```javascript
const geraNumsParesEntre = (min, max) => {
    const result = []

    for (let i = min + 1; i < max; i++) {
        if (i % 2 === 0) {
            result.push(i)
        }
    }

    return result
}

console.log(geraNumsParesEntre(4, 12))
```
