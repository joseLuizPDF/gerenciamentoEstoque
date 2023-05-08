# gerenciamentoEstoque
Este código implementa um sistema simples de gerenciamento de estoque utilizando Python e a biblioteca Pandas para exportar os dados para um arquivo Excel.

A função adicionarProduto() solicita ao usuário o nome e a quantidade do produto a ser adicionado ao estoque, e armazena esses dados em um dicionário chamado estoque, onde a chave é o nome do produto e o valor é a quantidade.
A função removerProduto() solicita o nome do produto a ser removido e verifica se ele está presente no dicionário, removendo-o caso esteja. A função exibirEstoque() percorre o dicionário e exibe o nome e a quantidade de cada produto.

O código principal utiliza um loop while True para apresentar um menu de opções ao usuário e executar a função correspondente à opção escolhida. A opção 4 exporta o estoque atual para um arquivo Excel utilizando a função to_excel() da biblioteca Pandas.

Note que este código não possui nenhum tipo de validação de entrada, o que pode levar a erros caso o usuário digite valores inválidos.
Além disso, não há persistência dos dados do estoque entre as execuções do programa, ou seja, o estoque é perdido ao encerrar o programa.
