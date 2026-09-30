# projeto-frontend-w3c

Projeto front-end académico de uma ONG fictícia, desenvolvido com foco em HTML semântico, acessibilidade, responsividade, otimização e boas práticas de versionamento.

## Tecnologias utilizadas
- HTML5
- CSS3
- JavaScript
- Git e GitHub
- Vite (build de produção)

## Estrutura
- `index.html`: página inicial
- `projetos.html`: projetos, doações e voluntariado
- `contato.html`: formulário com validações HTML5
- `css/style.css`: layout responsivo, foco visível e modo escuro
- `js/script.js`: alternância de tema e interação do formulário
- `assets/images/`: recursos visuais otimizados

## Acessibilidade
O projeto utiliza landmarks semânticos (`header`, `nav`, `main` e `footer`), textos alternativos, labels, atributos ARIA quando úteis, link para saltar ao conteúdo, navegação por teclado e estados de foco visíveis. As combinações cromáticas foram escolhidas visando os critérios de contraste WCAG.

## Instalação local
1. Clone ou descarregue o repositório.
2. Execute `npm install` se desejar utilizar o ambiente Vite.
3. Execute `npm run dev` para desenvolvimento ou abra `index.html` diretamente no navegador.

## Build
```bash
npm run build
```
A versão otimizada é gerada na pasta `dist`.

## Versionamento
Fluxo baseado em GitFlow: `main` para versões estáveis, `develop` para integração e `feature/` para novas funcionalidades. As mensagens seguem Conventional Commits, por exemplo `feat: adiciona formulário de contato` e `fix: corrige validação dos campos`. As releases utilizam versionamento semântico (`MAJOR.MINOR.PATCH`), com `v1.0.0` representando a primeira versão estável.

## Deploy
O projeto pode ser publicado no GitHub Pages. A branch `main` contém a versão estável destinada à publicação.

## Acessibilidade

O projeto utiliza HTML semântico, textos alternativos em imagens, labels em formulários, navegação por teclado e estados de foco visíveis. Também foram aplicados atributos WAI-ARIA quando necessário, buscando seguir as recomendações de acessibilidade WCAG 2.1.
