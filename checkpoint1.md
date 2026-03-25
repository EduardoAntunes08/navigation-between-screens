Commit: Passagem de parâmetros obrigatórios na tela de Perfil

Implementa a passagem de parâmetros obrigatórios na navegação.
Foi criada uma rota dinâmica perfil/{nome} no Navigation.
O botão da MenuScreen passou a navegar enviando um nome na URL.
A PerfilScreen foi modificada para receber esse parâmetro e exibi-lo na tela.

Commit: Passagem de parâmetros opcionais na tela de Pedidos

Implementa a passagem de parâmetro opcional na navegação para a tela de pedidos.
Foi criada a rota pedidos?cliente={cliente} utilizando navArgument, com valor padrão "Cliente Genérico".
A PedidosScreen foi modificada para receber o parâmetro cliente e exibi-lo na interface.

Commit: Inserindo valor ao parâmetro opcional na tela de Pedidos

Altera a navegação do botão na MenuScreen para enviar o parâmetro cliente para a tela de pedidos.
A navegação passa a utilizar a rota pedidos?cliente=Cliente XPTO, permitindo que a PedidosScreen receba e exiba o nome do cliente.

Commit: Passagem de múltiplos parâmetros

Adiciona um novo parâmetro (idade) na navegação para a tela de perfil.
A rota foi alterada para perfil/{nome}/{idade} e os argumentos passaram a ter tipos definidos com NavType.
A PerfilScreen foi modificada para receber o parâmetro idade e exibi-lo junto ao nome na tela.