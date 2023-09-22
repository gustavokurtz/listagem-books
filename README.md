
# Desenvolvi uma aplicação de gerenciamento de livros utilizando as tecnologias NestJS e Prisma. Este sistema permite que os usuários realizem operações CRUD em uma lista de livros, tornando a gestão de informações de livros eficiente e organizada.

Funcionalidades Principais:

Listagem de Livros:

Os usuários podem visualizar uma lista completa de todos os livros cadastrados no sistema.
Cada livro é exibido com informações como título, descrição e código de barras.
Cadastro de Livros:

É possível adicionar novos livros à lista, fornecendo informações como título, descrição e código de barras.
A aplicação verifica se um livro com o mesmo código de barras já existe para evitar duplicatas.
Atualização de Livros:

Os usuários têm a capacidade de atualizar informações de livros existentes, como título e descrição.
A atualização é feita com base no código de barras único de cada livro.
Exclusão de Livros:

Os livros podem ser removidos da lista, proporcionando uma opção de exclusão para cada registro.
A exclusão é segura e requer confirmação para evitar remoções acidentais.
Tecnologias Utilizadas:

NestJS: Este framework TypeScript é usado para criar a API RESTful que alimenta a aplicação de gerenciamento de livros. Ele fornece uma arquitetura modular, injeção de dependência e uma estrutura organizada para desenvolver o backend.

Prisma: O Prisma é uma ORM (Object-Relational Mapping) moderna que simplifica o acesso ao banco de dados. Ele é usado para definir os modelos de dados, criar migrações e realizar operações CRUD no banco de dados.

Benefícios:

O uso do NestJS facilita a criação de rotas RESTful e a organização de controladores para manipular operações CRUD.

O Prisma simplifica o acesso ao banco de dados, permitindo que os desenvolvedores interajam com o banco de dados usando código TypeScript, em vez de escrever SQL manualmente.

O CRUD em forma de listagem de livros melhora a eficiência na gestão de bibliotecas, permitindo que os usuários organizem e atualizem facilmente informações sobre os livros disponíveis.

Conclusão:

Com o NestJS e o Prisma, construí uma aplicação de gerenciamento de livros que oferece uma interface de usuário eficiente para listar, adicionar, atualizar e excluir livros. Essa solução simplifica a administração de uma biblioteca de livros, tornando-a mais organizada e fácil de gerenciar.
