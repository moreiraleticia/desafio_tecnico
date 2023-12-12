# desafio_tecnico
Função  para descobrir os valores inteiros divisíveis por 3 e 5 inferiores de determinado Numero.



function somaDivisiveisPor3e5(numero) {
    let soma = 0;
    for (let i = 0; i < numero; i++) {
        if (i % 3 === 0 || i % 5 === 0) {
            soma += i;
        }
    }
    return soma;
}

console.log(somaDivisiveisPor3e5(10)); // irá imprimir 23
console.log(somaDivisiveisPor3e5(11)); // irá imprimir 33

compilador online para teste:
https://onecompiler.com/javascript/3zw7gsstk
