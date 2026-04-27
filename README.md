# QA-Teste-Sauce-Demo
Treinando casos de testes no site Sauce Demo


ID: TC001
Título: Adicionar produto ao carrinho com sucesso

Pré-condição:
Usuário acessando o site com produto disponível em estoque

Passos:

Acessar a página inicial
Selecionar um produto
Escolher tamanho/cor (se aplicável)
Clicar em "ADD TO CART"

Resultado Esperado:
O produto deve ser adicionado ao carrinho com a quantidade correta e exibido no resumo do carrinho

<img width="1300" height="336" alt="image" src="https://github.com/user-attachments/assets/b40485a8-cdcb-4fe7-b4ec-6107e9da300c" />


ID: TC002
Título: Remover produto do carrinho

Pré-condição:
Produto já adicionado ao carrinho

Passos:

Acessar o carrinho
Clicar no botão "Remove" do produto

Resultado Esperado:
O produto deve ser removido e o carrinho atualizado corretamente

<img width="580" height="148" alt="image" src="https://github.com/user-attachments/assets/c0830cf5-cea2-45f9-9f7e-b11a0bfb03f8" /> <img width="165" height="93" alt="image" src="https://github.com/user-attachments/assets/6527a277-a77a-4309-8d86-38652cd5316d" />


ID: TC003
Título: Checkout com sucesso

Pré-condição:
Usuário com produto no carrinho

Passos:

Acessar o carrinho
Clicar em "CHECK OUT"
Preencher dados válidos (nome, endereço, pagamento)
Confirmar pedido

Resultado Esperado:
Pedido deve ser finalizado com sucesso e mensagem de confirmação exibida



ID: TC004
Título: Validação de cupom inválido

Pré-condição:
Produto no carrinho

Passos:

Acessar o carrinho
Inserir um cupom inválido
Clicar em "Apply"

Resultado Esperado:
Sistema deve exibir mensagem de erro informando que o cupom é inválido
<img width="441" height="319" alt="image" src="https://github.com/user-attachments/assets/1aeeea99-1643-4cf2-b56a-062ebcdfb15f" />


ID: TC005
Título: Buscar produto inexistente

Pré-condição:
Usuário na página inicial

Passos:

Inserir um nome de produto inexistente na busca
Pressionar Enter

Resultado Esperado:
Sistema deve exibir mensagem como "No results found for(nome do item)"

<img width="303" height="188" alt="image" src="https://github.com/user-attachments/assets/c92e6e97-7e33-4587-9e84-ede6f9834019" />



