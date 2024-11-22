

# Caso de Teste: Login com sucesso

## Objetivo
Verificar se o processo de login funciona corretamente para usuários registrados.

## Pré-condições
- O usuário já deve estar registrado no sistema.
- O sistema deve estar em funcionamento.
- O usuário deve ter acesso ao aplicativo ou site.

## Passos
1. Acesse a página de login.
2. Insira o **Username** e **password** válidos nos campos apropriados.
3. Clique no botão **"Login"**.


## Dados de Entrada 
- **Username**: `standard_user`
- **Password**: `secret_sauce`

## Resultados 
- O sistema  autentica o usuário.
- O usuário é redirecionado para a página inicial.


# Caso de Teste: Login Bloquebdo

## Objetivo
Verificar se o processo de login funciona corretamente para usuários bloqueados.

## Pré-condições
- O usuário já deve estar registrado no sistema.
- O sistema deve estar em funcionamento.


## Passos
1. Acesse a página de login.
2. Insira o **Username** e **password** válidos nos campos apropriados.
3. Clique no botão **"Login"**.


## Dados de Entrada 
- **Username**: `locked_out_user`
- **Password**: `secret_sauce`

## Resultados 
- O sistema  bloqueou o login do usuário.


 # Caso de Teste: Login com produtos com prblema nas fotos

## Objetivo
Verificar se o processo de login funciona corretamente para usuários registrados.

## Pré-condições
- O usuário já deve estar registrado no sistema.
- O sistema deve estar em funcionamento.
- O usuário deve ter acesso ao aplicativo ou site.

## Passos
1. Acesse a página de login.
2. Insira o **Username** e **password** válidos nos campos apropriados.
3. Clique no botão **"Login"**.


## Dados de Entrada 
- **Username**: `problem_user`
- **Password**: `secret_sauce`

## Resultados 
- O sistema  autentica o usuário.
- O usuário é redirecionado para a página inicial fotos não correspondentes aos produtos



 # Caso de Teste: Login com lentidão

## Objetivo
Verificar se o processo de login funciona corretamente para usuários registrados.

## Pré-condições
- O usuário já deve estar registrado no sistema.
- O sistema deve estar em funcionamento.
- O usuário deve ter acesso ao aplicativo ou site.

## Passos
1. Acesse a página de login.
2. Insira o **Username** e **password** válidos nos campos apropriados.
3. Clique no botão **"Login"**.


## Dados de Entrada 
- **Username**: `performance_glitch_user`
- **Password**: `secret_sauce`

## Resultados 
- O sistema  tem uma lentidão parar autenticar o usuário.
- O usuário é redirecionado para a página inicial.



# Caso de Teste: Login com erro ao remover do carrinho

## Objetivo
Verificar se o processo de login funciona corretamente para usuários registrados.

## Pré-condições
- O usuário já deve estar registrado no sistema.
- O sistema deve estar em funcionamento.
- O usuário deve ter acesso ao aplicativo ou site.

## Passos
1. Acesse a página de login.
2. Insira o **Username** e **password** válidos nos campos apropriados.
3. Clique no botão **"Login"**.


## Dados de Entrada 
- **Username**: `error_user     `
- **Password**: `secret_sauce`

## Resultados 
- O sistema  autentica o usuário.
- O usuário é redirecionado para a página inicial.
- Quando o usuário adiciona ao carrinho não é possível remover.


# Caso de Teste: Login com erro no layout do carrinho

## Objetivo
Verificar se o processo de login funciona corretamente para usuários registrados.

## Pré-condições
- O usuário já deve estar registrado no sistema.
- O sistema deve estar em funcionamento.
- O usuário deve ter acesso ao aplicativo ou site.

## Passos
1. Acesse a página de login.
2. Insira o **Username** e **password** válidos nos campos apropriados.
3. Clique no botão **"Login"**.


## Dados de Entrada 
   - **Username**: `visual_user``     `
- **Password**: `secret_sauce`

## Resultados 
- O sistema  autentica o usuário.
- O usuário é redirecionado para a página inicial.
- A posição do carrinho encontra-se em lugar diferente do padrão.



# Caso de Teste: Ordenação por preço crescente

## Objetivo
Garantir que a funcionalidade de ordenação de produtos está funcionando conforme os critérios selecionados pelo usuário.

## Pré-condições
- O usuário já deve estar logado no sistema.
- O sistema deve estar em funcionamento.


## Passos
1. Navegue até a página de **listagem de produtos**.
2. Localize o menu ou dropdown de **Ordenação**.
3. Selecione a opção **"Price(low to high)"**.


## Resultado 
- Os produtos são exibidos em ordem crescente de preço


# Caso de Teste: Ordenação por preço decrescente

## Objetivo
Garantir que a funcionalidade de ordenação de produtos está funcionando conforme os critérios selecionados pelo usuário.

## Pré-condições
- O usuário já deve estar logado no sistema.
- O sistema deve estar em funcionamento.


## Passos
1. Navegue até a página de **listagem de produtos**.
2. Localize o menu ou dropdown de **Ordenação**.
3. Selecione a opção **"Price(high to low)"**.


## Resultado 
- Os produtos são exibidos em ordem decrescente de preço


# Caso de Teste: Ordenação por nome em ordem alfabética

## Objetivo
Garantir que a funcionalidade de ordenação de produtos está funcionando conforme os critérios selecionados pelo usuário.

## Pré-condições
- O usuário já deve estar logado no sistema.
- O sistema deve estar em funcionamento.


## Passos
1. Navegue até a página de **listagem de produtos**.
2. Localize o menu ou dropdown de **Ordenação**.
3. Selecione a opção **"Name(A to Z)"**.


## Resultado
- Os produtos são exibidos em ordem alfabética reversa


# Caso de Teste: Ordenação por nome em ordem alfabética

## Objetivo
Garantir que a funcionalidade de ordenação de produtos está funcionando conforme os critérios selecionados pelo usuário.

## Pré-condições
- O usuário já deve estar logado no sistema.
- O sistema deve estar em funcionamento.


## Passos
1. Navegue até a página de **listagem de produtos**.
2. Localize o menu ou dropdown de **Ordenação**.
3. Selecione a opção **"Name(Z to A)"**.


## Resultado 
- Os produtos são exibidos em ordem alfabética reversa


# Caso de Teste: Fluxo completo de compra

## Objetivo
Validar que o usuário consegue realizar uma compra completa no e-commerce, desde a adição de produtos ao carrinho até a finalização do pedido, garantindo que todas as etapas funcionem corretamente.

## Pré-condições
- O usuário já deve estar logado no sistema.
- O sistema deve estar em funcionamento.


## Passos
1. Navegue até a página de **listagem de produtos**.
2. Insira um ou mais produtos no carrinho
3. Clique no carrinho
4. Clique em **Checkout**
5. Preencha os dados necessários
6. Clique em **Continue**
7. Clique em **Finish**


## Resultado
- Sua compra foi concluída com sucesso



# Caso de Teste: Remoção de itens do carrinho

## Objetivo
Validar que os itens podem ser removidos corretamente do carrinho de compras, atualizando a lista de produtos.

## Pré-condiçõe
- O usuário já deve estar logado no sistema.
- O sistema deve estar em funcionamento.


## Passos
1. Navegue até a página de **listagem de produtos**.
2. Insira um ou mais produtos no carrinho
3. Clique no carrinho
4. Escolha o produto que deseja remover e clique em **Remove**


## Resultado
- A lista de produtos foi atualizada com o produto removidos


# Caso de Teste: Navegação entre páginas

## Objetivo
Verificar se o sistema permite que o usuário navegue entre diferentes páginas sem erros e com carregamento correto dos conteúdos.


## Pré-condiçõe
- O usuário já deve estar logado no sistema.
- O sistema deve estar em funcionamento.


## Passos
1. Navegue até a página de **listagem de produtos**.
2. Clique em um produto
3. Adicione o prdoduo ao carrinho
4. Clique no carrinho 
5. Remova o produto do carrinho
6. Clique no menu superior esquerdo
7. Clique em **Logout**


## Resultado
- O sistema retorna a página de login



# Caso de Teste: Logout

## Objetivo
# Caso de Teste: Navegação entre páginas

## Objetivo
Validar que o usuário consegue sair do sistema corretamente e que todas as sessões são encerradas.

## Pré-condiçõe
- O usuário já deve estar logado no sistema.
- O sistema deve estar em funcionamento.


## Passos
1. Navegue até a página de **listagem de produtos**.
2. Clique em um produto
3. Adicione o prdoduo ao carrinho
4. Clique no carrinho 
5. Remova o produto do carrinho
6. Clique no menu superior esquerdo
7. Clique em **Logout**


## Resultado
- O sistema retorna a página de login

## Pré-condiçõe
- O usuário já deve estar logado no sistema.
- O sistema deve estar em funcionamento.


## Passos
   
1. Clique no menu superior esquerdo
2. Clique em **Logout**


## Resultado
- O sistema retorna a página de login