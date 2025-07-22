# Plano de Testes - Loja de Roupas (https://byandreyafreitas.com.br/)

## 📌 Objetivo

Testar as funcionalidades principais do site de e-commerce, garantindo que as ações do usuário funcionam corretamente e sem erros.

---

## 📋 Funcionalidades a serem testadas

1. Cadastro de usuário
2. Login de usuário
3. Adição de produtos ao carrinho
4. Finalização de compra (checkout)
5. Logout

---

## 🔍 Tipos de Teste

- Teste Funcional
- Teste de Fluxo
- Teste de Validação de Campo

---

## 🧪CT - Casos de Teste

### CT-001 - Cadastro com dados válidos

| ID                 | CT-001                                                             |
| ------------------ | ------------------------------------------------------------------ |
| Funcionalidade     | Cadastro de novo usuário                                           |
| Pré-condição       | Estar na página de cadastro                                        |
| Passos             | 1. Preencher todos os campos válidos <br> 2. Clicar em "Registrar" |
| Resultado Esperado | Usuário é redirecionado para o painel de conta                     |
| Tipo               | Funcional                                                          |

---

### CT-002 - Login com dados inválidos

| ID                 | CT-002                                                       |
| ------------------ | ------------------------------------------------------------ |
| Funcionalidade     | Login                                                        |
| Pré-condição       | Ter um usuário não registrado                                |
| Passos             | 1. Informar email/senha incorretos <br> 2. Clicar em "Login" |
| Resultado Esperado | Mensagem de erro é exibida                                   |
| Tipo               | Validação                                                    |

---

### CT-003 - Login com dados válidos

| ID                 | CT-003                                                     |
| ------------------ | ---------------------------------------------------------- |
| Funcionalidade     | Login                                                      |
| Pré-condição       | Ter um usuário válido                                      |
| Passos             | 1. Informar email/senha corretos <br> 2. Clicar em "Login" |
| Resultado Esperado | Usuário é redirecionado para o pagina principal            |
| Tipo               | Validação                                                  |

---

### CT-004 - Adicionar produto ao carrinho

| ID                 | CT-004                                                        |
| ------------------ | ------------------------------------------------------------- |
| Funcionalidade     | Carrinho de compras                                           |
| Pré-condição       | Estar logado                                                  |
| Passos             | 1. Escolher produto <br> 2. Clicar em "Adicionar ao carrinho" |
| Resultado Esperado | Produto é adicionado com sucesso                              |
| Tipo               | Funcional                                                     |

---

## 📝 Observações

Esse plano foi criado com fins educativos para demonstrar a estrutura de um teste funcional manual.

---
