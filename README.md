# Conventional Commits
## Fonte: [conventionalcommits.org](https://www.conventionalcommits.org/en/v1.0.0/)

## Estrutura principal
`<type>[optional scope]: <description>`  
`[optional body]`  
`[optional footer(s)]`

## Tipos permitidos
- build
- chore
- ci
- docs
- feat
- fix
- perf
- refactor
- revert
- style
- test

## Exemplos
### build
**Cenário:** Atualização das versões de bibliotecas usadas no projeto.  
**Commit:** `build(deps): Update Angular to v12.0.0`

### chore
**Cenário:** Rotina de manutenção geral do projeto.  
**Commit:** `chore(maintenance): Clean up unused code and files`

### ci
**Cenário:** Adicionar uma nova etapa de teste no pipeline de integração contínua.  
**Commit:** `ci(pipeline): Add linting stage to CI process`

### docs
**Cenário:** Atualizar o arquivo README com novas instruções de uso.  
**Commit:** `docs(readme): Update usage section with latest API changes`

### style
**Cenário:** Formatar o código para seguir as diretrizes de estilo do projeto.  
**Commit:** `style(code): Reformat code to adhere to project style guidelines`

### refactor
**Cenário:** Simplificação da lógica de uma função complexa.  
**Commit:** `refactor(user-service): Simplify user data retrieval logic`

### perf
**Cenário:** Otimização de uma consulta SQL para melhorar a performance.  
**Commit:** `perf(database): Optimize SQL query for faster data retrieval`

### test
**Cenário:** Adicionar testes para uma nova funcionalidade.  
**Commit:** `test(auth): Add tests for new OAuth login flow`

## Dicas
- Leia a documentação e tenha esta [página](https://www.conventionalcommits.org/en/v1.0.0/) fixada em seu navegador para consultar até estar fixo em sua mente.
- Utilize o chat CPT e coloque o seguinte prompt: "Por favor, me ajude a criar mensagens de commit seguindo o padrão do Conventional Commits. Preciso de exemplos e orientações sobre como estruturar mensagens de commit para diferentes tipos de alterações no código, como adições de recursos (feat), correções de bugs (fix), refatorações (refactor), melhorias de desempenho (perf), mudanças de documentação (docs), e outros tipos conforme a convenção do Conventional Commits."

