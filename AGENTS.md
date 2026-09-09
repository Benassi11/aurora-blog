# AGENTS.md

## Projeto

Aurora Blog é um blog desenvolvido com Astro + MDX.

## Stack

- Astro
- MDX
- TypeScript
- CSS

## Regras

- Utilize TypeScript quando houver lógica.
- Prefira componentes pequenos e reutilizáveis.
- Não introduza dependências sem necessidade.
- Posts devem ficar em `src/content/blog/`.
- Conteúdo dos posts deve utilizar `.mdx`.
- Componentes reutilizáveis devem ficar em `src/components/`.
- Rotas devem ficar em `src/pages/`.
- Não misture lógica de negócio com componentes de apresentação.
- Preserve a arquitetura existente antes de criar novos diretórios.

## Conteúdo

Os posts utilizam Content Collections do Astro.

Todo post deve possuir:

- `title`
- `description`
- `pubDate`
- `author`
- `category`
- `tags`

## Antes de modificar

1. Leia este arquivo.
2. Consulte `PLAN.md` para entender o estado atual do projeto.
3. Inspecione os arquivos relacionados à tarefa.
4. Faça a menor alteração necessária.
5. Verifique se o projeto continua funcionando.

## Não fazer

- Não criar arquivos desnecessários.
- Não adicionar frameworks frontend sem necessidade.
- Não substituir Astro por outro framework.
- Não transformar conteúdo simples em componentes sem necessidade.
