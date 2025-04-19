# Testes de API - ViaCep

**Endpoint Testado:** https://viacep.com.br/ws/01001000/json/

**Método:** GET  
**Objetivo:** Validar retorno de dados de CEP

**Resultado Esperado:** Código 200 + JSON com informações do endereço  
**Resultado Obtido:** Conforme esperado  
**Status:** ✅ Sucesso

**Testes Extras:**
- Teste com CEP inválido
- Teste com campo vazio
- Verificação de tempo de resposta (<= 2s)

