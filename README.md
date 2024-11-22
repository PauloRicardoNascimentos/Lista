1. Estrutura HTML
A página foi estruturada com:

Um cabeçalho <head> contendo codificação UTF-8 e meta tag para responsividade.

No <body>, um contêiner centralizado com:

Título <h1> para nomear a aplicação.

Formulário <form> com um campo de texto <input> para adicionar tarefas e botão de envio.

Lista <ul> onde as tarefas criadas são exibidas.



2. Estilização com CSS

Reset básico: Remoção de margens e padding padrões para consistência.

Layout centralizado: Uso de flexbox para centralizar o conteúdo.

Estilização de itens: Itens da lista possuem fundo claro, bordas arredondadas e estilo riscado ao serem concluídos.

Botões de ação: Botões de editar e excluir com cores distintas para facilitar identificação.


3. Adição de Funcionalidade com JavaScript

Envio do formulário: Previne o recarregamento da página e adiciona tarefas dinamicamente com document.createElement().

Editar e excluir:

Editar: Permite editar a tarefa com um prompt.

Excluir: Remove a tarefa da lista.


Marcar como concluída: Alterna uma classe CSS para riscar o texto e mudar a cor ao clicar na tarefa.


4. Melhorias e Ajustes Finais

O campo de texto é limpo após adicionar uma tarefa.

Efeitos de hover nos botões tornam as ações mais intuitivas.


Considerações
O projeto é simples, com foco em funcionalidade básica. Pode ser expandido com armazenamento local ou integração com banco de dados.



