# Exercício 2

Crie um campo label e um campo input na página HTML, e preencha o campo com o nome de mais uma fruta.
Depois disso, escreva **No DevTools** o código necessário para que seja possível imprimir o valor do input escrito no console.
Cole o comando aqui:
```jsx
    function imprimeFruta() {
    let guardaFruta = document.getElementById("nome")
    console.log(guardaFruta.value)
}
```