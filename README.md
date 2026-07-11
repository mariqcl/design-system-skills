# Design System Skills

Duas [skills do Claude Code](https://docs.claude.com/en/docs/claude-code/skills) feitas para **designers** — mesmo sem experiência com código — trabalharem com design systems entre o Figma e o Storybook.

| Skill | O que faz |
|-------|-----------|
| [`/ds-to-code`](./ds-to-code/SKILL.md) | Guia o designer desde a instalação do Storybook até visualizar os componentes do Figma funcionando como um catálogo interativo. |
| [`/use-ds`](./use-ds/SKILL.md) | Monta telas e protótipos reutilizando os componentes que **já existem** no Storybook (via Storybook MCP). Nunca cria componentes novos — apenas consome os existentes. |

As duas são pensadas para serem **didáticas**: explicam cada passo em linguagem simples, sem jargão, e sempre esperam sua confirmação antes de avançar.

## Como instalar

As skills ficam na pasta `~/.claude/skills/` da sua máquina. Para instalar:

```bash
git clone https://github.com/<seu-usuario>/design-system-skills.git
cp -r design-system-skills/ds-to-code ~/.claude/skills/
cp -r design-system-skills/use-ds ~/.claude/skills/
```

Depois, dentro do Claude Code, é só chamar `/ds-to-code` ou `/use-ds`.

## Como usar

- **Começando do zero?** Use `/ds-to-code` para configurar o Storybook e trazer seus componentes do Figma.
- **Já tem o Storybook rodando?** Use `/use-ds` para montar telas e protótipos reaproveitando o que já existe.

## Licença

[MIT](./LICENSE) — sinta-se à vontade para usar, modificar e compartilhar.
