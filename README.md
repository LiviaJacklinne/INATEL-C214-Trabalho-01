# Trabalho 01 - Testes Unitários

## Alunas: 
- Ana Luiza Martins
- Letícia Moreira Mendes
- Letícia Vitória Merss Moreira
- Livia Jacklinne Ramos Moreira

---

### Para excutar:
Código desenvolvido em REACT

Iniciar no servidor `npm start`

Rodar o teste `npm teste`

> OBS: Certifique-se de estar na pasta correta

---

## Introdução
O projeto desenvolvido trata-se de um gerenciador de tarefas, onde o mesmo é capaz de criar, editar, excluir e concluir uma tarefa.

## Funcionalidades
O código ficou duvidido em dois arquivos `ListaTarefa.js` e `Tarefa`. 

### O `ListaTarefa.js` contém as funcionalidades:
- adicionarTarefa;
- editarTarefa;
- concluirTarefa;
- desmarcarConcluida;
- excluirTarefa.

Ele tambem contempla o código HTML onde "coleta" os dados do front.
De modo geral ele é composto por todas as funções da lista de tarefa.

### A `Tarefa` contem as funcionalidade:
- salvarEdicao.

A Tarefa é responsável por lidar com apenas uma tarefa, ela foi criada para salvar edições. Ela "herda" todos os métodos de ListaTarefa, para salvar a edição.


