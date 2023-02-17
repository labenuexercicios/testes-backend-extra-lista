```javascript
// 1. identificar as chaves do objeto recebido
// 1.1 pesquisa no google "generate object keys js"
// 1.2 encontramos o método Object.keys()

const geraChavesObjeto = (input) => {
    return Object.keys(input)
}

console.log(geraChavesObjeto({ id: 1, name: "astrodev" }))
```
