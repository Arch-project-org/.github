# Guia de Contribuição

Obrigado por investir o seu tempo a contribuir para o Arch Project.

## Convenção de Nomenclatura de Branches
Crie a sua branch a partir da `Develop` utilizando os seguintes prefixos:
* `feat/`: Para novas funcionalidades (ex: `feat/integracao-supabase`)
* `fix/`: Para correção de bugs (ex: `fix/erro-responsividade-header`)
* `docs/`: Para documentação (ex: `docs/atualiza-readme`)
* `refactor/`: Para refatoração de código sem alteração de funcionalidade (ex: `refactor/otimiza-calculo-area`)
* `chore/`: Para tarefas de manutenção, dependências e configurações (ex: `chore/atualiza-vite`)
* Ou criação automatica a partir do quadro kanban, sempre crie uma branch a partir da `develop`

## Padrão de Mensagens de Commit (Conventional Commits)
As mensagens de commit devem seguir a estrutura: `tipo(escopo): descrição #numero taks`

**Tipos permitidos:** `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`.
**Exemplos:**
* `feat(auth): adiciona validacao de token JWT #20`
* `fix(ui): corrige desalinhamento no botao de submissao #28`
* `docs(readme): insere instrucoes de instalacao local #138`

Mensagens devem ser no imperativo ("adiciona", não "adicionado").

## Submissão de Código
1. Faça um *fork* ou crie a sua *branch*.
2. Garanta que o seu código passa no lint e nos testes locais (`npm run test`).
3. Abra o Pull Request utilizando o template padrão.
