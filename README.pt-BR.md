# Voyage

**Português (Brasil)** | [English](README.md)

Um app de mídia social para postar sobre suas viagens e se inspirar nas aventuras dos seus amigos.

**Código:** repositório público. Documentação revisada em 01/10/2026.

## Status

Projeto de estudo do período do curso Full Stack da Code Institute (últimos commits em 2023). O README anterior era o texto padrão inalterado do Create React App; foi substituído por este documento em 01/10/2026. O projeto não está atualmente publicado em uma URL pública conhecida.

## Objetivo

Voyage é o front-end de um app de compartilhamento de fotos de viagem: usuários postam sobre suas viagens e acompanham as aventuras uns dos outros, no estilo do walkthrough "Moments" do curso (o nome do pacote ainda é `moments`). A API correspondente para projetos dessa stack é um backend em Django REST Framework; este repositório contém apenas o front-end React.

## Stack técnica

Do `package.json`:

- React 18 com `react-scripts` (Create React App) e React Router
- React Bootstrap e Bootstrap
- Axios para chamadas de API, `jwt-decode` para tratamento de tokens
- `react-infinite-scroll-component`, `react-toastify`
- Testing Library (jest-dom, react, user-event)

## Rodar localmente

```bash
npm install
npm start
```

Abre em `http://localhost:3000`. Uma API de backend rodando é necessária para dados reais. Outros scripts: `npm test`, `npm run build`. Um script `heroku-prebuild` restou da configuração original de deploy no Heroku; nenhum deploy atual foi verificado.

## Registro de desenvolvimento

O conjunto exato de funcionalidades e as notas originais de planejamento não foram reconstruídos nesta atualização de documentação, e nenhum histórico de processo é inventado aqui. O histórico do git é a fonte para detalhes de implementação.

## Testes

As dependências do Testing Library estão presentes, mas a suíte de testes não foi executada nesta atualização. Antes de qualquer reuso, rode `npm install` e `npm test` e verifique o app contra um backend ativo.

## Créditos e status de licença

Iniciado com Create React App e baseado no template do walkthrough "Moments" da Code Institute. Nenhum arquivo `LICENSE` foi encontrado na raiz do repositório nesta revisão; código de template de terceiros mantém seus termos originais, e esta atualização não aplica uma nova licença sobre eles.
