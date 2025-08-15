# Amigo Secreto em JavaScript

Este projeto é uma aplicação simples de Amigo Secreto, desenvolvida como parte do programa **Oracle ONE em parceria com a Alura e Alura Latam**. O objetivo foi construir uma ferramenta que permite aos usuários adicionar nomes a uma lista e, em seguida, sortear um amigo secreto de forma aleatória.

A aplicação demonstra conceitos fundamentais de JavaScript, HTML e CSS, como manipulação do DOM e lógica de programação.

---

### Funcionalidades da Aplicação

- **Adicionar Amigos**: O usuário pode inserir nomes em um campo de texto e adicioná-los a uma lista.
- **Capitalização Automática**: Todos os nomes são capitalizados (primeira letra maiúscula) ao serem adicionados, garantindo consistência na lista.
- **Sorteio Aleatório**: A aplicação sorteia um amigo secreto de forma aleatória a cada clique, removendo o nome sorteado da lista principal para evitar repetições.
- **Mensagem de Finalização**: Ao final do sorteio, uma mensagem é exibida para informar que todos os amigos foram sorteados.
- **Reiniciar Sorteio**: Um botão permite ao usuário limpar todas as listas e reiniciar a brincadeira.

---

### Tecnologias Utilizadas

- **HTML5**: Estrutura e marcação da aplicação.
- **CSS3**: Estilização e layout.
- **JavaScript**: Lógica de programação, manipulação do DOM, controle de eventos e validações.

---

### Como o Código Funciona (Destaques da Lógica)

- **Manipulação de Arrays**: O projeto utiliza um array (`amigos`) para armazenar os nomes, manipulando-o com métodos como `push()` para adicionar, `splice()` para remover, e `length` para validações.

- **`Math.random()` e `Math.floor()`**: A combinação dessas funções é utilizada para gerar um índice aleatório e seguro, garantindo que o sorteio selecione um nome que realmente existe na lista.

- **DOM e Eventos**: O JavaScript é usado para criar e manipular elementos HTML dinamicamente (`createElement`, `appendChild`) e para responder às interações do usuário, como cliques de botão e o pressionar da tecla "Enter".

- **Validações**: Funções de validação garantem que a aplicação não apresente erros, como tentar sortear com menos de dois amigos na lista.

---



### Instalação e Execução

Para rodar o projeto, basta abrir o arquivo `index.html` em qualquer navegador web. Nenhuma configuração adicional é necessária.
ou acesse: https://challenge-amigo-secreto-one-rose.vercel.app/
