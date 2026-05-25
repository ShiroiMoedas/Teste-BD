# Teste-BD

TESTE_001:
RF01: Cadastrar Produto
Descrição: Cadastra corretamente.
Precondição: No campo 'nome', aceita apenas Strings, nos demais campos se tento inserir outros tipos de valores diferentes do definido, o proprio IDE não deixa.
Passos: Testei inserir outros tipos de dados, não funcionou;
Resultado Esperado: Funcionar apenas com os dados devidos.

TESTE_002:
RF02: Registrar Categoria de Produtos
Descrição: Categorizar produtos corretamente.
Precondição: No campo 'categoria', aceita apenas Strings, caso seja inserido dados diferentes do solicitado, a IDE não permite.
Passos: Testei inserir outros tipos de dados, não funcionou.
Resultado Esperado: Funcionar apenas com os dados devidos.

TESTE_003:
RF03: Registrar Validade de Produtos
Descrição: O sistema deve registrar a data de validade dos produtos.
Precondição: No campo 's', aceita apenas String. (podem ser inseridos dados que não sejam equivalentes a uma data) 
Passos: Testei inserir outros tipos de dados, não funcionou.
Resultado Esperado: Funcionar apenas com os dados devidos.

TESTE_004:
RF04: O sistema deve mostrar a quantidade de produtos em estoque.
Descrição: O sistema deve exibir quantidade de produtos em estoque
Precondição: No campo 'quantidadeAtual', aceita apenas Int, caso seja algum dado diferente o IDE não permite.
Passos: Tentei inserir dados diferentes e não fuynciona.
Resultado Esperado: Funcionar apenas com os dados devidos.

TESTE_005:
RF05: O sistema deve permitir que o estoque seja gerenciado.
Descrição: O sistema deve permitir que coloque ou tire produtos do estoque.
Precondição: Utilizar metodo para alterar quantidade de produtos.
Passos: Chamar metodo 'alterarQuantidadeEstoque' e cumprir os parametros corretamente.
Resultado Esperado: Quantidade de produtos alterada devidamente.

TESTE_006:
RF06: O sistema deve avisar quando o estoque estiver baixo.
Descrição: O sistema deve avisar quando o estoque de produtos for menos que o minimo.
Precondição: Utilizar metodo para verificar estoque.
Passos: Chamar metodo 'verificarEstoqueAbaixoDoMinimo' que verifica quais produtos estão abaixo do minimo.
Resultado Esperado: Caso tenha produtos que não cumpram com a quantidade minima, será exibida uma mensagem de aviso no console.

TESTE_007:
RF06: O sistema deve permitir filtrar produtos por categoria.
Descrição: O sistema deve permitir que busque produtos de uma categoriqa especifica.
Precondição: Utilizar metodo para listar por categoria.
Passos: Chamar metodo 'listarPorCategoria' que exibe a lista de uma categoria especifica.
Resultado Esperado: Exibir apenas itens da categoria desejada.


