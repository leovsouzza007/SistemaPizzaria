# 🍕 Sistema de Pizzaria em PHP

Um sistema desenvolvido em **PHP + MySQL** para gerenciar clientes, produtos e pedidos de uma pizzaria, com interface administrativa e acompanhamento de status em tempo real.

---

## 📌 Funcionalidades

### 👤 Clientes
- Cadastro de clientes (Nome, E-mail, CPF, Telefone, Endereço)
- Edição e exclusão de clientes
- Histórico de pedidos por cliente

### 🍕 Produtos
- Cadastro de sabores de pizzas, bebidas e adicionais
- Preços dinâmicos por tamanho e borda
- Descrição detalhada de cada produto
- CRUD completo (Criar, Listar, Editar, Excluir)

### 🛒 Pedidos
- Identificação do cliente que fez o pedido
- Seleção de itens do cardápio (pizzas, bebidas, adicionais)
- Escolha da forma de pagamento (PIX, Cartão, Dinheiro)
- Acompanhamento de status:
  - **Retirada:** `Em preparo` → `Pronto`
  - **Entrega:** `Em preparo` → `Pronto` → `Saiu para entrega`

### 🖥️ Interface Administrativa
- Gerenciamento de clientes e pedidos
- Alteração de status em tempo real
- Listagem dos produtos cadastrados

---

## 🗄️ Modelo de Banco de Dados (Resumo)

- **clientes** → informações dos clientes  
- **produtos** → bebidas, pizzas, adicionais  
- **pedidos** → dados do pedido (cliente, forma de pagamento, status)  
- **pedido_itens** → produtos de cada pedido  

---

## 🚀 Tecnologias Utilizadas
- **PHP** (com PDO para banco de dados)  
- **MySQL**  
- **HTML, CSS, JavaScript** (frontend básico)  
- **Ajax ou WebSockets** (atualização de status em tempo real)  

---

## 📂 Estrutura do Projeto (sugestão)
