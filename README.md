# Jogo do Número Secreto

## Introdução
Este projeto implementa um jogo simples de adivinhação em JavaScript, onde o jogador precisa acertar um número secreto gerado aleatoriamente pelo computador. O jogo utiliza diversas funcionalidades do JavaScript para criar uma experiência interativa e desafiadora.

## Funcionalidades Principais
- Geração de Número Aleatório: A função gerarNumeroAleatorio() utiliza Math.random() para gerar um número aleatório dentro de um limite definido. Além disso, ela garante que o número gerado não se repita em uma mesma rodada, evitando que o jogo se torne previsível.
- Verificação de Chute: A função verificarChute() compara o número digitado pelo jogador com o número secreto. Se o chute estiver correto, o jogador é parabenizado e o jogo é reiniciado. Caso contrário, o jogador recebe dicas sobre se o número secreto é maior ou menor.
- Interface do Usuário: O JavaScript interage com o HTML para exibir mensagens, receber a entrada do usuário e atualizar a tela. As funções exibirTextoNaTela(), limparCampo() e reiniciarJogo() são responsáveis por essas interações.
- Feedback de Voz: A biblioteca responsiveVoice é utilizada para transformar o texto em fala, proporcionando um feedback auditivo ao jogador.
- Reinício do Jogo: A função reiniciarJogo() reinicia todas as variáveis e prepara o jogo para uma nova rodada.

## Conceitos de JavaScript Utilizados
- Arrays: A variável listaDeNumerosSorteados armazena os números já sorteados, garantindo que não haja repetições.
- Funções: O código é organizado em funções para modularizar o código e facilitar a reutilização.
- return: A palavra-chave return é utilizada para retornar um valor de uma função.
- responsiveVoice.speak(): Essa função da biblioteca responsiveVoice permite converter texto em fala.
- document.querySelector(): Seleciona o primeiro elemento que corresponda a um seletor CSS.
- document.getElementById(): Seleciona um elemento HTML pelo seu ID.
- .innerHTML: Define ou retorna o conteúdo HTML de um elemento.
- Funções com Parâmetros: As funções exibirTextoNaTela() e outras recebem parâmetros para personalizar seu comportamento.
- .removeAttribute(): Remove um atributo de um elemento.
- setAttribute(): Adiciona ou modifica um atributo de um elemento.
- .includes(): Verifica se um array contém um determinado elemento.
- .push(): Adiciona um elemento ao final de um array.
