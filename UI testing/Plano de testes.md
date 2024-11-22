# Plano de Testes para um Sistema de E-commerce

## Introdução
Este documento detalha o plano de testes para um sistema de e-commerce, com o objetivo de garantir a qualidade e o funcionamento correto das funcionalidades principais.

---

## Escopo

### Funcionalidades
- **Autenticação:** Validar o login de diferentes tipos de usuários (administrador, cliente).  
- **Catálogo de Produtos:** Testar a ordenação e filtragem dos produtos.  
- **Carrinho de Compras:** Verificar a adição, remoção e atualização de itens no carrinho, além do cálculo do valor total.  
- **Finalização da Compra:** Validar o fluxo completo da compra, desde o pagamento até a confirmação do pedido.  
- **Navegação:** Assegurar a facilidade de navegação entre as diferentes páginas do site.  
- **Logout:** Confirmar que a sessão do usuário é encerrada corretamente.  

### Tipos de Testes
- **Funcionais:** Verificar se as funcionalidades do sistema atendem aos requisitos.  
- **Usabilidade:** Avaliar a experiência do usuário durante a interação com o sistema.  
- **Desempenho:** Medir a velocidade e a capacidade de resposta do sistema.  
- **Integração:** Testar a interação entre diferentes componentes do sistema.  
- **Segurança:** Validar a proteção dos dados do usuário e do sistema.  

---

## Casos de Teste



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

## Resultado esperado
- O sistema  autentica o usuário.
- O usuário é redirecionado para a página inicial.


# Caso de Teste: Login com sucesso

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

## Resultado esperado
- O sistema  autentica o usuário.
- O usuário é redirecionado para a página inicial.


 # sCaso de Teste: Login com sucesso

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

## Resultado esperado
- O sistema  autentica o usuário.
- O usuário é redirecionado para a página inicial.



 Caso de Teste: Login com sucesso

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

## Resultado esperado
- O sistema  autentica o usuário.
- O usuário é redirecionado para a página inicial.



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
- **Username**: `error_user     `
- **Password**: `secret_sauce`

## Resultado esperado
- O sistema  autentica o usuário.
- O usuário é redirecionado para a página inicial.


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
   - **Username**: `visual_user``     `
- **Password**: `secret_sauce`

## Resultado esperado
- O sistema  autentica o usuário.
- O usuário é redirecionado para a página inicial.



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


## Resultado esperado
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


## Resultado esperado
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


## Resultado esperado
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


## Resultado esperado
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


## Resultado esperado
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


## Resultado esperado
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
Validar que o usuário consegue sair do sistema corretamente e que todas as sessões são encerradas.

## Pré-condiçõe
- O usuário já deve estar logado no sistema.
- O sistema deve estar em funcionamento.


## Passos
   
1. Clique no menu superior esquerdo
2. Clique em **Logout**


## Resultado
- O sistema retorna a página de login


---

## Ambiente de Teste

### Hardware
- Servidores com especificações mínimas para hospedagem do sistema.  
  

### Software
- Sistemas operacionais: Windows, macOS, Linux, iOS, Android.  
- Navegadores: Chrome, Firefox, Edge, Safari.  
- Ferramentas de teste: Selenium, Cypress.

### Dados
- Dados de teste pré-cadastrados para produtos, usuários.  

---

## Critérios de Aceitação

- **Execução Completa:** 100% dos casos de teste devem ser executados com sucesso.  
- **Correção de Defeitos:** Todos os defeitos críticos devem ser corrigidos.  
- **Estabilidade:** O sistema deve estar estável e apresentar bom desempenho.  

---

## Próximos Passos

1. **Execução dos Testes:** Realizar os testes de acordo com os casos de teste definidos.  
2. **Relatório de Testes:** Elaborar um relatório detalhado com os resultados, incluindo defeitos encontrados e ações corretivas.  
3. **Retestes:** Executar novamente os testes para verificar se os defeitos foram corrigidos.  

---

## Observações

- Este plano de testes é básico e pode ser adaptado conforme a complexidade do sistema e os requisitos do projeto.  
- Testes de usabilidade são importantes para avaliar a experiência do usuário.  
- Automatização de testes pode agilizar o processo e garantir repetibilidade.  
- Testes exploratórios podem identificar problemas não previstos nos casos de teste.

---

## Ferramentas Sugeridas

- **Automação de Testes:** Selenium, Cypress.  
- **Gestão de Testes:** TestRail, Jira.  
- **Captura de Tela:** Snagit.  