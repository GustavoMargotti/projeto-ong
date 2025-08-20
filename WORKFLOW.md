# Workflow e Política de Commits

## Workflow
Usaremos **GitHub Flow**:
1. A branch principal é `main`.
2. Para cada tarefa criamos uma branch (`feature/...` ou `fix/...`).
3. Ao terminar, abrimos Pull Request para `main`.
4. Após revisão, fazemos o merge e apagamos a branch.

## Versionamento
- `main`: branch principal.
- `feature/...`: novas funcionalidades.
- `fix/...`: correções de bugs.

## Commits
Padrão: **Conventional Commits**  
Formato:

### Tipos principais
- feat — nova funcionalidade
- fix — correção de bug
- docs — documentação
- style — ajustes visuais
- refactor — refatoração de código
- chore — manutenção

### Tipos adicionais criados neste projeto
- ux — melhorias de usabilidade
- config — ajustes de configuração
- deploy — alterações de publicação