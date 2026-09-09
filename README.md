# Aurora Blog

Um blog simples construído com **Astro + MDX**, criado para **estudos**. Projeto fictício e minimalista focado em boas práticas de arquitetura Astro, separação de responsabilidades, componentização e tipagem com TypeScript.

## O que foi feito

- **Astro + MDX** — Geração de site estático com conteúdo escrito em MDX, permitindo usar componentes Astro dentro dos artigos
- **Content Collections** — Schema tipado com `zod` para validar os metadados dos posts (título, descrição, data, autor, categoria e tags)
- **Componentes reutilizáveis** — `Header`, `Footer`, `PostCard` e `Callout` como componentes Astro isolados com props tipadas
- **Layouts** — `BaseLayout` para a estrutura global do site e `PostLayout` específico para artigos
- **CSS customizado** — Variáveis de tema em arquivo global, com estilos scoping por componente
- **Roteamento automático** — Páginas estáticas por arquivo em `src/pages/`, incluindo rota dinâmica para artigos `[slug]` e filtro por tags
- **SEO básico** — `<title>`, `<meta description>` e HTML semântico em cada página

## Requisitos

- Node.js >= 22.12.0
- npm >= 10

## Stack

- **Astro** v7
- **MDX** para conteúdo
- **TypeScript** para tipagem
- **CSS** customizado com variáveis de tema

## Estrutura

```text
src/
├── components/       # Componentes reutilizáveis
├── content/blog/     # Posts em MDX
├── layouts/          # Layouts da aplicação
├── pages/            # Rotas
├── styles/           # Estilos globais
└── content.config.ts # Configuração das collections
```

## Comandos

| Comando | Ação |
| :--- | :--- |
| `npm run dev` | Inicia o servidor de desenvolvimento |
| `npm run build` | Gera o site estático em `./dist/` |
| `npm run preview` | Visualiza o build localmente |
