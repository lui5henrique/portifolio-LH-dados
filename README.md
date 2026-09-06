# Portfólio — Luis Henrique

Site pessoal (portfólio) de **Luis Henrique**, Analista de Dados & BI na AGU (Advocacia-Geral
da União), em Recife/PE.

🔗 **Site publicado:** https://portifolio-lh-dados.vercel.app

## Sobre o projeto

Site estático, front-end puro (sem framework, sem build step) — HTML, CSS e JavaScript
vanilla. Foi construído para apresentar experiência profissional, formação, certificações,
skills e projetos reais (com links para os repositórios no GitHub).

### Seções

1. **Início** — hero com foto, headline e estatísticas rápidas (registros tratados, painéis
   e sistema entregues na AGU).
2. **Sobre** — trajetória pessoal e profissional.
3. **Projetos** — cards com os principais projetos (painéis Power BI da AGU, análises em
   Python/SQL), cada um linkando para o repositório correspondente no GitHub.
4. **Experiência** — linha do tempo profissional.
5. **Formação & Certificações** — formação acadêmica, certificações (Google, IBM) e cursos
   (Data Science Academy), incluindo o que está em andamento.
6. **Skills** — hard skills (por categoria) e soft skills.
7. **Contato** — e-mail e redes (LinkedIn, GitHub, Instagram).

## Stack

- HTML5 semântico
- CSS3 (custom properties, Grid, Flexbox — sem framework)
- JavaScript vanilla (menu mobile, scroll reveal, nav ativa, botão "voltar ao topo")
- Fontes: [Manrope](https://fonts.google.com/specimen/Manrope), [Inter](https://fonts.google.com/specimen/Inter) e [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono), via Google Fonts

## Estrutura de pastas

```
.
├── index.html
├── assets/
│   ├── css/style.css
│   └── js/main.js
├── img/
│   ├── eu capa bolso.png     # foto usada no hero
│   └── favicon.svg
└── README.md
```

## Rodando localmente

Não há build nem dependências. Basta abrir o `index.html` diretamente no navegador, ou
servir a pasta com qualquer servidor estático, por exemplo:

```bash
npx serve .
```

## Deploy

O site é publicado na [Vercel](https://vercel.com) a partir deste repositório. Todo push
para a branch `main` gera um novo deploy automaticamente (integração Git da Vercel).

## Manutenção

Este projeto é mantido com o auxílio do [Claude Code](https://claude.com/claude-code).
Atualizações de conteúdo (textos, projetos, experiências) e de design são commitadas e
enviadas para este repositório assim que aplicadas.
