# teste-estagio-Target
Repositório que visa demonstrar o código desenvolvido durante o teste técnico para estágio em desenvolvimento de software na Target

# Respostas

1) Resposta: 91

2) 
```js
  function GenerateFibonacci(number){
    var fibonacci = [0, 1];
    for (var i = 2; i < number; i++) {
      fibonacci[i] = fibonacci[i - 2] + fibonacci[i - 1];
    }
    return fibonacci;
  }
```

3) Os próximos elementos das sequências são a) 9, b) 128, c) 49, d) 100, e) 13, f) 200.

4) utilizando uma regra de três temos que o carro percorre todo o trajeto em 54 minutos, enquanto que o Caminhão precisará de 75 minutos mais 10 de pedágio. Dessa forma, o carro atinge metade do trageto em 27min e o Caminhão demorara  aproximadamente 37min (10 a mais que o carro). Nesse sentido é garantido que os dois veículos se encontrarão somente após o carro estar pelo menos 50km de distância do ponto de partida Ribeirão preto, assim podemos afirmar que o carro estará mais distante do que o Caminhão dessa cidade.

5) 
``` js
function invertString(str) {
    var invertedString = ""
    for(var i = str.length - 1; i >= 0 ; i--) {
      invertedString+= str[i]
    }
    return invertedString
}
  console.log(invertString("Target")) //tegraT
```
