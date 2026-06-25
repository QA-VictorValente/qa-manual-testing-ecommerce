# Bug Reports - E-commerce Project

---

## 🐞 BUG-001 - Erro ao fazer login com senha válida

**Descrição:**
Sistema está impedindo login mesmo com credenciais corretas.

**Passos para reproduzir:**
1. Acessar página de login
2. Inserir e-mail válido
3. Inserir senha válida
4. Clicar em "Login"

**Resultado atual:**
Sistema exibe mensagem "Credenciais inválidas".

**Resultado esperado:**
Usuário deve ser autenticado e redirecionado para a página inicial.

**Severidade:** Alta  
**Prioridade:** Alta

---

## 🐞 BUG-002 - Produto não aparece no carrinho após adição

**Descrição:**
Após adicionar produto ao carrinho, ele não é exibido corretamente.

**Passos para reproduzir:**
1. Acessar lista de produtos
2. Selecionar produto
3. Clicar em "Adicionar ao carrinho"
4. Abrir carrinho

**Resultado atual:**
Carrinho aparece vazio.

**Resultado esperado:**
Produto deve estar listado no carrinho.

**Severidade:** Alta  
**Prioridade:** Média

---

## 🐞 BUG-003 - Botão de finalizar compra não responde

**Descrição:**
Botão de checkout não executa ação ao ser clicado.

**Passos para reproduzir:**
1. Adicionar produto ao carrinho
2. Acessar carrinho
3. Clicar em "Finalizar compra"

**Resultado atual:**
Nada acontece ao clicar no botão.

**Resultado esperado:**
Sistema deve iniciar fluxo de pagamento.

**Severidade:** Crítica  
**Prioridade:** Alta
