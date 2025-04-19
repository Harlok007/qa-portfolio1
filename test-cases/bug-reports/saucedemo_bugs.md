# Relatório de Bugs - SauceDemo

##  Ambiente de Testes:
- URL: https://www.saucedemo.com/
- Navegador: Microsoft Edge
- Sistema: Windows 10

---

##  Bug 001 - Produto duplicado no carrinho

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

##  Bug 002 - Checkout de informação não funciona.

**Descrição:** Ao entrar na haba Checkout, o usuario poderá adicionar qualquer nome e Cep que irá constar como correto.

**Passos:**
1. Selecionar item
2. No menu carrinho, escolher `checkout`
3. Na sessão de informações, adicione qualquer nome e Cep que irá constar como correto e enviado.

**Resultado Esperado:** Erro ao adicionar cep inexistente  
**Resultado Obtido:** Envio do produto  
**Severidade:** Alta  
**Status:** Aberto

##  Bug 003 - Remoção de item do carrinho.

**Descrição:** O usuario irá selecionar um item, entretanto quando o usario clica em remover o item não sai do carrinho.

**Passos:**
1. Selecionar item na sessão produtos
2. Na sessão produtos, escolher `Remove`

**Resultado Esperado:** Excluir o produto do carrinho  
**Resultado Obtido:** Nenhuma ação do botão
**Severidade:** Média  
**Status:** Aberto

##  Bug 004 - Performace do site.

**Descrição:** O usuario irá se deparar com a lentidão ao fazer login.

**Passos:**
1. Adicionar as credenciais de login

**Resultado Esperado:** Velocidade ao entrar na proxima sessão
**Resultado Obtido:** Lentidão de alguns segundos
**Severidade:** Baixa  
**Status:** Aberto

##  Bug 005 - Ordem de produtos.

**Descrição:** O usuario ao clicar em ordem, irá se deparar com um erro grafico de ordem de produtos no qual o usuario irá se confundir.

**Passos:**
1. Efetue o Login
2. Ao clicar em `Filtragem` escolha uma ordem
   
**Resultado Esperado:** Ordem de A-Z, Produto mais barato - produto mais caro, etc...
**Resultado Obtido:** Erro visual no qual troca as ordens dos itens
**Severidade:** Média 
**Status:** Aberto
