# Contribuindo para o Guia de Desenvolvimento Agêntico

Obrigado por considerar contribuir! Para manter a qualidade deste repositório open-source, siga estas diretrizes:

## Estrutura de Idiomas

- **Conceitos e Técnicas**: Mantemos versões em Inglês (`.en.md`) e Português (`.pt.md`). Se alterar um, por favor tente atualizar o outro ou abra uma issue para tradução.
- **Catálogo (Agentes e Skills)**: **Apenas em Inglês**. Isso garante melhor performance quando esses arquivos são lidos por LLMs.

## Adicionando Conteúdo

### Conceitos (`concepts/`) e Técnicas (`techniques/`)
- Crie arquivos com sufixo de idioma: `nome-do-arquivo.pt.md` (ou `.en.md`).
- Use Markdown padrão.
- Evite "citações sintéticas" (inventar fontes); use links reais.

### Agentes (`catalog/agents/`)
- Use inglês.
- Extensão `.md` (ex: `planner.agent.md`).
- Siga o padrão de frontmatter YAML com `name`, `description`, `tools`, `model`, `handoffs`.

### Skills (`catalog/skills/`)
- Use inglês.
- Crie uma pasta em `catalog/skills/` (ex: `security-review/`).
- O arquivo principal deve ser `SKILL.md` com frontmatter mínimo.
- Mantenha descrições curtas e use `references/` para detalhes longos.

## Pull Requests

1. Siga o padrão de commits convencionais (ex: `feat: add new security skill`).
2. Garanta que os links internos funcionam.
3. Se adicionar um novo conceito, adicione link no `README.md` (se relevante).

A contribuição de todos é essencial para democratizar a engenharia de IA!
