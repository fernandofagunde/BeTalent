# Análise de Riscos 

## 2.1 Login com Diferentes Tipos de Usuários Disponíveis

### Riscos
- **Acesso Não Autorizado:** Possibilidade de falha na validação que permita o acesso indevido a usuários não autorizados.  
- **Exposição de Dados Sensíveis:** Armazenamento ou transmissão de credenciais de forma insegura pode resultar em vazamento de informações.  
- **Ataques de Força Bruta:** Ausência de proteção contra múltiplas tentativas de login pode expor o sistema a ataques.  

### Mitigação
- Implementar autenticação segura com criptografia (ex.: TLS).  
- Habilitar bloqueio de conta após várias tentativas malsucedidas de login.  
- Adotar autenticação multifator (MFA).  

---

## 1.2.2 Ordenação e Filtragem de Produtos

### Riscos
 
- **Falhas na Interface do Usuário:** Erros na exibição ou ausência de mensagens claras podem confundir o usuário.  

### Mitigação
    
- Garantir feedback visual claro para ações do usuário.  

---

## 1.2.3 Fluxo Completo de Compra (do Carrinho até Finalização)

### Riscos
    
- **Pedidos Duplicados:** Requisições repetidas sem controle podem criar múltiplos pedidos.  

### Mitigação
    
- Adotar mecanismos para evitar duplicação de transações.  

---

## 1.2.4 Remoção de Itens do Carrinho

### Riscos
- **Inconsistência no Carrinho:** Itens podem ser removidos incorretamente ou permanecer mesmo após a remoção.  
- **Atualização Lenta:** Lentidão ao atualizar a interface do carrinho após a remoção de itens.  

### Mitigação
- Validar remoções com testes manuais e automatizados.  
- Implementar notificações em tempo real para atualizações no carrinho.  

---

## 1.2.5 Navegação entre Páginas

### Riscos
- **Erros de Carregamento:** Links quebrados ou páginas mal configuradas podem gerar erros 404 ou 500.  
- **Retenção de Estado:** Navegação inadequada pode causar perda de informações (ex.: itens no carrinho desaparecendo).  

### Mitigação
- Realizar testes de navegação em diferentes cenários e dispositivos.  
- Usar ferramentas como cache ou sessões para preservar o estado do usuário.  

---

## 1.2.6 Logout

### Riscos
- **Sessão Não Encerrada:** Sessões podem não ser finalizadas corretamente, permitindo acesso após o logout.  
- **Logout Inesperado:** Erros podem desconectar o usuário sem consentimento.  

### Mitigação
- Garantir que todas as sessões do usuário sejam encerradas no backend.  
- Implementar mensagens claras para usuários quando a sessão for encerrada.  

---

