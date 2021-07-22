# traducao codigo morse
 Tradução de Código Morse com Árvore.
 Objetivo era:

    Você foi convidado para desenvolver um sistema que seja capaz de traduzir mensagens em Código
    Morse para texto.
    No Código Morse, cada símbolo do alfabeto (letras e dígitos) é codificado através de pontos “.” e
    traços “-” conforme a tabela apresentada abaixo. Espaços são utilizados como separadores de
    símbolos e a barra “/” é usada como separador de palavras. Por exemplo a mensagem:
    ISSO EH 1 EXEMPLO
    é codificada como: 
    .. … … --- / . .... / .---- / . -..- . -- .--. .-.. ---
    Faça um programa que converta mensagens em Código Morse para mensagens em texto. Para isso,
    utilize a estrutura de dados Árvore. A estrutura deve ficar organizada de tal forma que, à medida que
    os pontos e traços do Código Morse são lidos, você “desce” na árvore até encontrar o símbolo do
    alfabeto correspondente.
    Considere duas etapas fundamentais no desenvolvimento do sistema:
    1) Construção da árvore: Implemente um procedimento para construção da árvore com base na
    tabela do Código Morse (sugestão: leia um arquivo de texto com a tabela armazenada). Além das
    funções necessárias para manipulação da estrutura de dados, implemente também um procedimento
    que imprima a árvore (o código e o símbolo correspondente) usando o percurso em “pré-ordem”.
    Resultado na saída, por exemplo:
    . E 
    .. I 
    ... S 
    2) Conversão da mensagem: Após a construção da árvore, seu sistema deve ser capaz de traduzir
    as mensagens em Código Morse. Para isso, implemente uma função que leia a mensagem em
    Código Morse, a partir de um arquivo de entrada, imprima na tela a mensagem em Código Morse,
    seguido da impressão da mensagem resultado da tradução
