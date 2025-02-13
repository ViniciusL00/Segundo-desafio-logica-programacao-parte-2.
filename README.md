# segundo-desafio-logica-programacao-parte-2.
 Segundo desafio de logica de programação com JavaScript parte 2.

1- Criar uma função que exibe "Olá, mundo!" no console.

    function exibirOlaMundo(){
    console.log('Olá, Mundo!'); // Função criada para exibir a mensagem Olá, Mundo!
}

Quando você chamar a função exibirOlaMundo(), ela exibirá "Olá, mundo!" no console.

    exibirOlaMundo(); // Função executada exibindo a mensagem no console.

Essa função não recebe parâmetros e apenas executa o comando console.log() para mostrar a mensagem no console.

2- Criar uma função que recebe um nome como parâmetro e exibe "Olá, [nome]!" no console.

    function saudacao(nome){
    console.log(`Olá, ${nome}`);
}

    saudacao('Pumpkinn');

**Explicação:**

A função saudacao recebe um parâmetro nome.
Dentro da função, usamos a sintaxe de template string (${nome}) para inserir o valor do parâmetro nome na mensagem.
Quando chamamos a função, passamos 'Pumpkinn' como argumento, e a função exibe "Olá, Pumpkinn!" no console.

3- Criar uma função que recebe um número como parâmetro e retorna o dobro desse número.

    function dobro(numero){
    return numero * 2; 
}

**Explicação:**

A função dobro recebe um parâmetro chamado numero.
Dentro da função, multiplicamos o valor de numero por 2 e retornamos esse valor.


    let resultado = dobro(10); // o retorno do numero sera 20.
        console.log(resultado); // exibe 20.

Quando você chama a função com o valor 10, o resultado retornado será 20, que é o dobro do número passado.

4- Criar uma função que recebe três números como parâmetros e retorna a média deles.

    function calcularMedia(num1, num2, num3){
    let soma = num1 + num2 + num3;
    return soma / 3;
    }

**Explicação:**

A função calcularMedia recebe três parâmetros: num1, num2 e num3.
Dentro da função, somamos os três números e depois dividimos o resultado por 3 para calcular a média.
O resultado da média é retornado pela função.   

    let media = calcularMedia(5, 7 , 9); // o retorno será: 7
        console.log(media); // Exibe: 7

Quando você chama a função com os números 5, 7 e 9, a média será 7, que é o resultado da soma (5 + 7 + 9 = 21) dividida por 3.

5- Criar uma função que recebe dois números como parâmetros e retorna o maior deles.

        function maiorNumero(num1, num2){
        if(num1 > num2){
            return num1;
        } else {
            return num2;
        }
    }

**Explicação:** A função maiorNumero recebe dois parâmetros: num1 e num2.
A função verifica se num1 é maior do que num2. Se for, ela retorna num1.
Caso contrário, ela retorna num2.

    let resultado = maiorNumero(8, 5); // O retorno será: 8.
    console.log(resultado); // Exibe: 8.

Nesse exemplo, o número 8 será retornado porque é o maior entre 8 e 5.

6- Criar uma função que recebe um número como parâmetro e retorna o resultado da multiplicação desse número por ele mesmo.

    function multiplicado(numero){
        return numero * numero;
    }

**Explicação:** A função multiplicado recebe um parâmetro chamado numero.
Dentro da função, multiplicamos o numero por ele mesmo e retornamos o resultado.

    let resultado = multiplicado(8); // O retorno será: 64.
    console.log(resultado); // Exibe: 64

Quando você chama a função com o número 8, o resultado será 64, que é o multiplicado de 8(8 * 8).
