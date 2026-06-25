# Test Cases - E-commerce Project

## 🧪 TC-001 - Login com sucesso

**Descrição:** Validar login com credenciais válidas.

**Pré-condição:**
Usuário cadastrado no sistema.

**Passos:**
1. Acessar página de login
2. Inserir e-mail válido
3. Inserir senha válida
4. Clicar em "Login"

**Resultado esperado:**
Usuário deve ser autenticado e redirecionado para a página inicial.

**Tipo:** Positivo

---

## 🧪 TC-002 - Login com senha inválida

**Descrição:** Validar erro ao inserir senha incorreta.

**Pré-condição:**
Usuário cadastrado no sistema.

**Passos:**
1. Acessar página de login
2. Inserir e-mail válido
3. Inserir senha incorreta
4. Clicar em "Login"

**Resultado esperado:**
Sistema deve exibir mensagem de erro "Credenciais inválidas".

**Tipo:** Negativo

---

## 🧪 TC-003 - Cadastro de novo usuário

**Descrição:** Validar criação de conta com dados válidos.

**Passos:**
1. Acessar página de cadastro
2. Inserir nome, e-mail e senha válidos
3. Clicar em "Cadastrar"

**Resultado esperado:**
Usuário deve ser criado com sucesso e logado automaticamente.

**Tipo:** Positivo

---

## 🧪 TC-004 - Adicionar produto ao carrinho

**Descrição:** Validar adição de produto ao carrinho.

**Passos:**
1. Acessar lista de produtos
2. Selecionar um produto
3. Clicar em "Adicionar ao carrinho"

**Resultado esperado:**
Produto deve aparecer no carrinho com quantidade correta.

**Tipo:** Positivo

---

## 🧪 TC-005 - Finalizar compra

**Descrição:** Validar fluxo de checkout.

**Passos:**
1. Adicionar produto ao carrinho
2. Acessar carrinho
3. Clicar em "Finalizar compra"
4. Confirmar pagamento

**Resultado esperado:**
Compra deve ser concluída com sucesso.

**Tipo:** Positivo
