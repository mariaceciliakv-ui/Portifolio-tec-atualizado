# Portfólio | Maria C. J. Oliveira

Portfólio pessoal de **Business Analyst | Data Analytics | Business Intelligence | Automação e IA**, em uma única página HTML com tema escuro, visual sóbrio e foco em dados.

## Sobre o projeto

O site apresenta trajetória, resultados, stack, formação e projetos de forma objetiva, com linguagem visual inspirada em painéis analíticos: grade discreta, fontes monoespaçadas, KPIs e gráfico de barras.

**Seções**

| Seção | Conteúdo |
|---|---|
| Hero | Apresentação, KPIs e links principais |
| Sobre | Resumo profissional e impacto em 6 frentes |
| Resultados | Gráfico de barras com melhorias medidas e exemplo ilustrativo de SQL |
| Trajetória | Linha do tempo de 2019 até hoje |
| Stack | Ferramentas e competências por categoria |
| Formação | Graduações, bootcamps, cursos e certificações |
| Projetos | 11 projetos com filtro por status |
| Contato | LinkedIn, GitHub, e-mail, WhatsApp e site |

## Tecnologias

- HTML5, CSS3 e JavaScript puro, sem frameworks nem build
- Fontes: [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) e [Inter](https://fonts.google.com/specimen/Inter) (Google Fonts)
- Responsivo, com layout adaptado para celular e tablet

## Como usar

1. Baixe o arquivo `portfolio_maria_dados_v2.html`.
2. Abra no navegador (duplo clique) ou sirva localmente:

```bash
python3 -m http.server 8000
# acesse http://localhost:8000/portfolio_maria_dados_v2.html
```

## Como personalizar

**Textos fixos** (sobre, trajetória, stack, contato): edite direto no HTML, dentro de cada `<section>`.

**Projetos, formação e bootcamps**: ficam em listas no bloco `<script>` no final do arquivo.

```js
// Cada projeto: [grupo, status, nome, subtítulo, descrição, tipo de programação, [tecnologias]]
["dev", "Em desenvolvimento", "RECIA", "Gestão Inteligente...", "Descrição...", "Low-Code/No-Code...", ["Lovable", "Supabase"]]
```

- Grupo `"dev"` aparece em *Desenvolvidos / em desenvolvimento*; `"fut"` em *Futuros e ideias*.
- Para adicionar um projeto, inclua uma nova linha na lista `P`. Para formação, use `E` (graduações) ou `B` (bootcamps).

**Cores**: altere as variáveis no início do CSS.

```css
:root{--bg:#0b0e14;--panel:#121722;--line:#1f2635;--tx:#e6e9ef;--mut:#8b94a7;--ac:#38bdf8;--ac2:#34d399;--warn:#fbbf24}
```

**Gráfico de resultados**: ajuste o atributo `data-w` e o texto de cada barra (valores em %).

> O trecho de SQL na seção *Resultados* é apenas ilustrativo. Substitua por um código seu ou remova.

## Publicação

**GitHub Pages**

1. Crie um repositório e envie o arquivo, renomeando para `index.html`.
2. Em *Settings → Pages*, escolha a branch `main` e a pasta `/ (root)`.
3. O site ficará disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

Também funciona em Netlify, Vercel ou Cloudflare Pages: basta arrastar ou enviar o arquivo.

## Estrutura

```
.
├── index.html   # portfólio completo (HTML + CSS + JS)
└── README.md
```

## Contato

- LinkedIn: [in/maria-c-j-oliveira](https://www.linkedin.com/in/maria-c-j-oliveira)
- GitHub: [mariaceciliakv-ui](https://github.com/mariaceciliakv-ui)
- E-mail: mariacecilia.kv@gmail.com
- Site: [sites.google.com/view/mycvbymaria](https://sites.google.com/view/mycvbymaria)

---

© 2026 Maria C. J. Oliveira · Campinas, SP
