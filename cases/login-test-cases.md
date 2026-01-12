# Casos de Teste — Login

| ID | Cenário | Pré-condição | Passos | Resultado esperado | Prioridade |
|---|---|---|---|---|---|
| LOGIN-001 | Login válido | Usuário ativo | Informar e-mail e senha válidos > Entrar | Login realizado e redireciona para área logada | P0 |
| LOGIN-002 | Senha inválida | Usuário ativo | E-mail válido + senha inválida > Entrar | Exibe mensagem de erro sem expor detalhes | P0 |
| LOGIN-003 | Usuário inexistente | — | E-mail inexistente + senha qualquer > Entrar | Mensagem de erro genérica | P1 |
| LOGIN-004 | Campos vazios | — | Clicar em entrar sem preencher | Validação de campos obrigatórios | P1 |

