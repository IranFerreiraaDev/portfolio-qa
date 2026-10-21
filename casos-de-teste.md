## CT-01 - Login com usuário e senha válidos
- **Pré-condição:** estar na página de login
- **Passos:**
  1. Digitar o usuário standard_user
  2. Digitar a senha secret_sauce
  3. Clicar em Login
  4. Direciona para á pagina principal corretamente
- **Resultado esperado:** acessar a página de produtos
- **Resultado obtido:** acessou a página de produtos
- **Status:** Passou

## CT-02 - Login com usuário bloqueado
- **Pré-condição:** estar na página de login
- **Passos:**
  1. Digitar o usuário locked_out_user
  2. Digitar a senha secret_sauce
  3. Clicar em Login
- **Resultado esperado:** o sistema recusar o acesso e mostrar mensagem informando que o usuário está bloqueado
- **Resultado obtido:** o sistema recusou o acesso e mostrou a mensagem de usuário bloqueado
- **Status:** Passou

## CT-03 - Login com senha vazia
- **Pré-condição:** estar na página de login
- **Passos:**
  1. Digitar o usuário standard_user
  2. Deixar o campo de senha vazio
  3. Clicar em Login
- **Resultado esperado:** o sistema deverá recusar o acesso e mostrar mensagem informando que é necessário digitar uma senha
- **Resultado obtido:** o sistema recusou o acesso e mostrou a mensagem: "Epic sadface: Password is required"
- **Status:** Passou

## CT-04 - Login com usuário vazio
- **Pré-condição:** estar na página de login
- **Passos:**
  1. Deixar o campo de usuário vazio
  2. Digitar a senha secret_sauce
  3. Clicar em Login
- **Resultado esperado:** o sistema deverá recusar o acesso e mostrar mensagem informando que é necessário digitar o usuário
- **Resultado obtido:** o sistema recusou o acesso e mostrou a mensagem: "Epic sadface: Username is required"
- **Status:** Passou

## CT-05 - Adicionar produto ao carrinho
- **Pré-condição:** estar logado na página de produtos
- **Passos:**
  1. Clicar no botão "Add to cart" do produto Sauce Labs Backpack
- **Resultado esperado:** o ícone do carrinho, no topo da tela, deverá mostrar o número 1
- **Resultado obtido:** o ícone do carrinho passou a mostrar o número 1
- **Status:** Passou

## CT-06 - Remover produto do carrinho
- **Pré-condição:** ter um produto adicionado ao carrinho
- **Passos:**
  1. Clicar no botão "Remove" do produto adicionado
- **Resultado esperado:** o produto deverá ser removido do carrinho
- **Resultado obtido:** o produto foi removido do carrinho
- **Status:** Passou

## CT-07 - Visualizar carrinho com vários itens
- **Pré-condição:** ter dois ou mais produtos adicionados ao carrinho
- **Passos:**
  1. Clicar no ícone do carrinho, no topo da tela
- **Resultado esperado:** a tela do carrinho deverá abrir listando todos os produtos adicionados
- **Resultado obtido:** a tela do carrinho abriu listando todos os produtos adicionados
- **Status:** Passou

## CT-08 - Checkout sem preencher os dados
- **Pré-condição:** ter produtos no carrinho e estar na tela de informações do checkout
- **Passos:**
  1. Deixar os campos Nome, Sobrenome e CEP vazios
  2. Clicar em "Continue"
- **Resultado esperado:** o sistema deverá recusar o avanço e mostrar mensagem pedindo o preenchimento dos campos
- **Resultado obtido:** Ocorreu como foi pedido, apareceu nos campos pedido para o usuario digitar para seguir a diante.
- **Status:** Passou

## CT-09 - Finalizar compra com dados válidos
- **Pré-condição:** ter produtos no carrinho e estar na tela de informações do checkout
- **Passos:**
  1. Preencher o campo Nome
  2. Preencher o campo Sobrenome
  3. Preencher o campo CEP com números
  4. Clicar em "Continue"
  5. Clicar em "Finish"
- **Resultado esperado:** o sistema deverá concluir a compra e mostrar a mensagem "Thank you for your order"
- **Resultado obtido:** o sistema concluiu a compra e mostrou a mensagem "Thank you for your order"
- **Status:** Passou



