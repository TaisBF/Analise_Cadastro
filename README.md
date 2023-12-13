## Roteiro de Teste para a Página "Cadastro"

### I. Testes Funcionais

1. **Teste de Cadastro:**
   - **Cenário 1:** Tente se cadastrar com campos de senha vazios.
     - **Passos:**
       - Acesse a página "cadastro".
       - Insira um nome de usuário.
       - Deixe os campos de senha e confirmação de senha em branco.
       - Clique no botão "Sign up".
     - **Esperado:** Deve exibir uma mensagem de erro indicando que os campos de senha não podem estar vazios.

   - **Cenário 2:** Tente se cadastrar com senhas que não coincidem.
     - **Passos:**
       - Acesse a página "cadastro".
       - Insira um nome de usuário.
       - Insira uma senha no campo de senha.
       - Insira uma senha diferente no campo de confirmação de senha.
       - Clique no botão "Sign up".
     - **Esperado:** Deve exibir uma mensagem de erro indicando que as senhas não coincidem.

   - **Cenário 3:** Tente se cadastrar com sucesso.
     - **Passos:**
       - Acesse a página "cadastro".
       - Insira um nome de usuário único.
       - Insira uma senha no campo de senha.
       - Insira a mesma senha no campo de confirmação de senha.
       - Clique no botão "Sign up".
     - **Esperado:** Deve exibir uma mensagem de sucesso indicando que o cadastro foi realizado com êxito.

2. **Teste de Interface Gráfica:**
   - **Cenário 1:** Verifique se a imagem é exibida corretamente.
     - **Passos:**
       - Acesse a página "cadastro".
     - **Esperado:** Deve exibir uma imagem na área designada da página.

### II. Testes Não-Funcionais

1. **Teste de Desempenho:**
   - **Cenário 1:** Avalie o tempo de carregamento da página.
     - **Passos:**
       - Acesse a página "cadastro".
       - Cronometre o tempo necessário para a página ser totalmente carregada.
     - **Esperado:** O tempo de carregamento deve estar dentro de limites aceitáveis.

### III. Correções e Melhorias

1. **Correções:**
   - **Problema 1:** Mensagens de erro.
     - **Solução:** Acrescente a mensagem de erro para o cenario 1 do teste de cadastro.

2. **Melhorias Futuras:**
   - **Melhoria 1:** Implementar uma funcionalidade de recuperação de senha.
   - **Melhoria 2:** Adicionar validações mais robustas nos campos de senha.
   - **Melhoria 3:** Refatorar o código para seguir boas práticas de programação.

