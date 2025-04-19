# Relatório de Bugs - SauceDemo

## 🧪 Ambiente de Testes:
- URL: https://www.saucedemo.com/
- Navegador: Microsoft Edge
- Sistema: Windows 10

---

## 🐞 Bug 001 - Produto duplicado no carrinho

**Descrição:** Ao adicionar um produto, o cliente não pode adicionar mais de uma vez um item no carrinho..

**Passos:**
1. Fazer login com `standard_user`
2. Adicionar o produto "Sauce Labs Backpack"
3. Voltar e tentar adicionar novamente.

**Resultado Esperado:** A quantidade do item aumentaria para 2  
**Resultado Obtido:** Item aparece 1 vez  
**Severidade:** Alta 
**Status:** Aberto

---

## 🐞 Bug 002 - Checkout de informação não funciona.

**Descrição:** Ao entrar na haba Checkout, o usuario poderá adicionar qualquer nome e Cep que irá constar como correto.

**Passos:**
1. Selecionar item
2. No menu carrinho, escolher "checkout"
3. Na sessão de informações, adicione qualquer nome e Cep que irá constar como correto e enviado.

**Resultado Esperado:** Erro ao adicionar cep inexistente  
**Resultado Obtido:** Envio do produto  
**Severidade:** Alta  
**Status:** Aberto
