# Relatório de Bugs - Automationexercise

##  Ambiente de Testes:
- URL: https://automationexercise.com
- Navegador: Microsoft Edge
- Sistema: Windows 10

---

##  Bug 001 - Registro

**Descrição:** Sessão de Registro permitiu dar informações incorretas e inexistentes.

**Passos:**
1. Fazer registro na sessão `Registro`
2. Adicione email, cep, nome inexistentes
3. Aperte em concluir

**Resultado Esperado:** Site bloquear tentativas de registro com caracteres inexistentes e falsos  
**Resultado Obtido:** O usuario se registra com nome, email, cep falsos e consegue fazer compras  
**Severidade:** Alta 
**Status:** Aberto

![image](https://github.com/user-attachments/assets/7c8123d2-af87-4595-86a0-e514d8ad6535)

##  Bug 002 - Cartão

**Descrição:** Sessão de cartão permitiu dar informações falsas.

**Passos:**
1. Fazer registro na sessão `Paymant`
2. Adicione o nome do cartão, Cvv, numero, data de expiração
3. Aperte em concluir

**Resultado Esperado:** Site bloquear tentativas de compras com cartões inexistentes e falsos  
**Resultado Obtido:** O usuario compra usando um cartão falsocom nome, cvv, data de expiração falsos e consegue fazer compras  
**Severidade:** Alta 
**Status:** Aberto

![image](https://github.com/user-attachments/assets/bed3050d-9a4b-4465-8217-9f9efaf529d7)

##  Bug 003 - Carrinho

**Descrição:** Usuario não consegue visualizar a soma de todos os itens do carrinho.

**Passos:**
1. Adicione itens ao seu carrinho e vá para a sessão `Shopping Cart`
2. Observe que não terá a soma de todos os itens.

**Resultado Esperado:** Soma de todos os itens selecionados na sessão `Home`
**Resultado Obtido:** O usuario não poderá visualizar a soma dos itens, logo, terá que somar por contra própria.  
**Severidade:** Alta 
**Status:** Aberto

![image](https://github.com/user-attachments/assets/c4332d4b-6c69-4497-bb44-98c3a9e1dd20)

##  Bug 004 - Carrinho

**Descrição:** Usuario não consegue alterar a quantidade dos itens do carrinho.

**Passos:**
1. Adicione itens ao seu carrinho e vá para a sessão `Shopping Cart`
2. Observe que não poderá excluir a quantidade desejada de itens.

**Resultado Esperado:** Exclusão de itens selecionados na sessão  `Shopping Cart`
**Resultado Obtido:** O usuario não poderá excluir os itens, logo, terá que exluir da `Shopping Cart` e adicionar o valor desejado.  
**Severidade:** Baixa 
**Status:** Aberto



