# 2024-1-aula-01-intro

Instalar o Node.JS, disponível em <https://nodejs.org/en>

Instalar o VSCode, disponível em <https://code.visualstudio.com/>

Instalar a extensão (Quokka.js)[https://quokkajs.com/docs/#getting-started] no VsCode

## Revisão de Lógica

```javascript
// tipagem em JS é dinâmica
x = 2_000_000 // variável number
console.log(typeof(x)) // number
console.log("algo " + x) // saída
console.log(Math.floor(4.5))
console.log(typeof(Math.floor(4.5)))
var s = "TADS"
const q = "INFO" // constante
// q = ""
console.log(2 == "2")
console.log(2 === "2")
s = 'Tecnologia'
let r = "Analise"
v = true
console.log(typeof(v));
if (v == true) {
  console.log("v é verdadeiro")
}

o = "teste"
if (o) { // tipagem fraca, o é aceito como uma expressão boolean
  console.log('Eu tenho um "o" ' + o)
}

n = 5
m = "10" // tipagem fraca (conversão implícita)
console.log(n + m)
console.log(n - m)

componente = "poo"
switch (componente) {
  case "modular": // fallback
  case "poo":
  case "lógica": console.log("Programação");
  default: console.log("Não Programação")
}

if (componente == "lógica" || componente == "poo" || componente == "modular") {
  console.log("Programação")
} else {
  console.log("Não Programação")
}

// iterativos (laços, loops)
// for, while, do while // off-by-one
for (var i = 0, j = 3; i < 5; i++) { // 0, 1, 2, 3, 4
  console.log(i)
}

console.log(i)

for (; i < 10; i++) {
  console.log(i)
}

while (i < 15) {
  console.log(i)
  i++;
}
                    //   0    1    2    3    4    5
var nome = "mîrcio" // ["m", "a", "r", "c", "i", "o"]

console.log(nome.toUpperCase())
console.log(nome)

console.log(nome[0])
console.log(nome[1])

for (var i = 0; i < nome.length; i++) { // for para percorrer um array ou lista
  console.log(nome[i])
  console.log(nome[i].charCodeAt())
  console.log(String.fromCharCode(nome[i].charCodeAt() + 1))
}

console.log('a'.charCodeAt() - 'A'.charCodeAt())

var feliz = "😃"
console.log(feliz.length) // 2, emojis usam 2 bytes
console.log(feliz[0])
console.log(feliz[1])
console.log(feliz[2])
```
