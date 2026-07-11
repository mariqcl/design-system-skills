# Design System Skills

Duas [skills do Claude Code](https://docs.claude.com/en/docs/claude-code/skills) feitas para **designers** — mesmo sem experiência com código — trabalharem com design systems entre o Figma e o Storybook.

| Skill | O que faz |
|-------|-----------|
| [`/ds-to-code`](./ds-to-code/SKILL.md) | Guia o designer desde a instalação do Storybook até visualizar os componentes do Figma funcionando como um catálogo interativo. |
| [`/use-ds`](./use-ds/SKILL.md) | Monta telas e protótipos reutilizando os componentes que **já existem** no Storybook (via Storybook MCP). Nunca cria componentes novos — apenas consome os existentes. |

As duas são pensadas para serem **didáticas**: explicam cada passo em linguagem simples, sem jargão, e sempre esperam sua confirmação antes de avançar.

## Como instalar

1. Nesta página do GitHub, clique no botão verde **`Code`** → **`Download ZIP`**.
2. Descompacte o arquivo baixado (dê dois cliques nele).
3. Dentro dele há duas pastas: **`ds-to-code`** e **`use-ds`**. Copie as duas.
4. Cole as duas dentro da pasta de skills do Claude Code no seu computador:

   **No Mac** 🍎
   - Abra o **Finder**, aperte `Cmd + Shift + G`, cole `~/.claude/skills/` e dê Enter.

   **No Windows** 🪟
   - Abra o **Explorador de Arquivos**, clique na barra de endereço no topo, cole `%USERPROFILE%\.claude\skills\` e dê Enter.

   > Se a pasta `skills` não existir, é só criar uma com esse nome dentro da pasta `.claude`.
5. Feche e abra o Claude Code de novo.

Pronto! Agora é só chamar `/ds-to-code` ou `/use-ds` dentro do Claude Code.

### Quer usar só em um projeto de trabalho?

Você não precisa instalar as duas skills nem instalar para o computador inteiro. Dá pra colocar **só a `ds-to-code`** ou **só a `use-ds`** dentro de um projeto específico.

Para isso, coloque a pasta da skill que você quer (`ds-to-code` **ou** `use-ds`) dentro de `.claude/skills/` na raiz do seu projeto de trabalho. Ex.:

```
meu-projeto/
├── CLAUDE.md
└── .claude/
    └── skills/
        └── use-ds/        ← só a skill que você quer
            └── SKILL.md
```

Assim ela só aparece quando você abre o Claude Code nesse projeto. O nome `.claude/skills/` é fixo (é onde o Claude Code procura as skills), mas o projeto pode ser qualquer um seu.

## Como usar

- **Começando do zero?** Use `/ds-to-code` para configurar o Storybook e trazer seus componentes do Figma.
- **Já tem o Storybook rodando?** Use `/use-ds` para montar telas e protótipos reaproveitando o que já existe.

## Licença

[MIT](./LICENSE) — sinta-se à vontade para usar, modificar e compartilhar.
