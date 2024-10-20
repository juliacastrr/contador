Documentação do Componente Counter

Estrutura do Componente
O componente Counter é um contador simples que exibe um número e possui dois botões: um para incrementar e outro para decrementar o valor.

Testes para o Componente Counter
Os testes para o componente Counter são escritos utilizando a React Testing Library. O arquivo de teste se chama Counter.test.js.

1 - Testa a Renderização Inicial do Contador:
Propósito: Verificar se o componente Counter renderiza corretamente com o texto "Contador:".
O que verifica: Assegura que o título do contador está presente na tela.

2 - Testa a Função de Incremento:
Propósito: Verificar se o contador incrementa corretamente ao clicar no botão "Incrementar".
O que verifica: Confirma que, após um clique, o valor exibido do contador é incrementado para 1.

3 - Testa a Função de Decremento:
Propósito: Verificar se o contador decrementa corretamente ao clicar no botão "Decrementar".
O que verifica: Assegura que, após um clique, o valor exibido do contador é decrementado para -1.

4 - Testa Incrementos e Decrementos em Sequência:
Propósito: Verificar se o contador funciona corretamente em múltiplas interações de incremento e decremento.
O que verifica: Confirma que, após dois incrementos e um decremento, o valor do contador é atualizado corretamente.

Os testes acima garantem que o componente Counter está funcionando conforme o esperado, validando a renderização inicial, a funcionalidade de incrementar e decrementar, e a precisão nas interações do usuário. Essa abordagem ajuda a identificar problemas rapidamente e a manter a qualidade do código.
