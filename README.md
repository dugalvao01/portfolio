# Portfolio de Engenharia & Code 🚀

Um portfolio moderno, de alta performance e focado em SEO, construído com Astro, React e TypeScript.

## 🛠 Tech Stack

- **Core**: [Astro](https://astro.build) (Static Site Generation)
- **Linguagem**: TypeScript
- **Estilização**: Tailwind CSS v4
- **Conteúdo**: MDX (Markdown + JSX)
- **Interatividade**: React (Islands Architecture)
- **Deploy**: GitHub Pages (via GitHub Actions)

## 🚀 Como Rodar Localmente

Certifique-se de ter o Node.js v20+ instalado.

1.  **Instale as dependências**:
    ```bash
    npm install
    ```

2.  **Inicie o servidor de desenvolvimento**:
    ```bash
    npm run dev
    ```
    Acesse http://localhost:4321 no seu navegador.

## 📦 Build e Deploy

O projeto está configurado para deploy automático no GitHub Pages.

**Para criar um build de produção localmente:**
```bash
npm run build
# Para visualizar o resultado do build:
npm run preview
```

## 📁 Estrutura do Projeto

```text
/
├── public/          # Assets estáticos (robots.txt, CNAME)
├── src/
│   ├── components/  # Componentes reutilizáveis
│   │   ├── common/  # Header, Footer
│   │   ├── seo/     # SEOHead
│   │   └── islands/ # React Components (ex: ProjectFilter)
│   ├── content/     # Coleções de conteúdo (Projetos MDX)
│   ├── layouts/     # Layout principal
│   └── pages/       # Rotas do site
└── astro.config.mjs # Configuração do Astro
```

## 📝 Customização

1.  **Domínio Customizado**: Edite o arquivo `public/CNAME` com seu domínio.
2.  **Projetos**: Adicione novos arquivos `.mdx` em `src/content/projects/`.
3.  **SEO**: Configure as meta tags em `src/components/seo/SEOHead.astro`.

## 📄 Licença

MIT
