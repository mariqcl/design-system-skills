# Design System Skills

Duas [skills do Claude Code](https://docs.claude.com/en/docs/claude-code/skills) feitas para **designers** — mesmo sem experiência com código — trabalharem com design systems entre o Figma e o Storybook.

| Skill | O que faz |
|-------|-----------|
| [`/ds-to-code`](./ds-to-code/SKILL.md) | Guia o designer desde a instalação do Storybook até visualizar os componentes do Figma funcionando como um catálogo interativo. |
| [`/use-ds`](./use-ds/SKILL.md) | Monta telas e protótipos reutilizando os componentes que **já existem** no Storybook (via Storybook MCP). Nunca cria componentes novos — apenas consome os existentes. |

As duas são pensadas para serem **didáticas**: explicam cada passo em linguagem simples, sem jargão, e sempre esperam sua confirmação antes de avançar.

## Como instalar

Você **não precisa saber programar**. É só baixar e arrastar:

1. Nesta página do GitHub, clique no botão verde **`Code`** → **`Download ZIP`**.
2. Descompacte o arquivo baixado (dê dois cliques nele).
3. Dentro dele há duas pastas: **`ds-to-code`** e **`use-ds`**. Copie as duas.
4. Cole as duas dentro da pasta `~/.claude/skills/` do seu computador.
   - No Mac: abra o Finder, aperte `Cmd + Shift + G`, cole `~/.claude/skills/` e dê Enter.
   - Se a pasta `skills` não existir, é só criar uma com esse nome.
5. Feche e abra o Claude Code de novo.

Pronto! Agora é só chamar `/ds-to-code` ou `/use-ds` dentro do Claude Code.

## Como usar

- **Começando do zero?** Use `/ds-to-code` para configurar o Storybook e trazer seus componentes do Figma.
- **Já tem o Storybook rodando?** Use `/use-ds` para montar telas e protótipos reaproveitando o que já existe.

## Licença

[MIT](./LICENSE) — sinta-se à vontade para usar, modificar e compartilhar.
