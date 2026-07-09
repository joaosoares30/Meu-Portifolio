# João Soares | Portfólio Pessoal

Site de portfólio pessoal desenvolvido para apresentar informações profissionais, habilidades técnicas, projetos e um canal de contato direto.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

## 🔗 [Demo](https://joaosoares30.github.io/Meu-Portifolio/)

## 📋 Sobre o Projeto

Landing page single-page com design escuro (dark mode), moderno e totalmente responsivo, contendo:

- **Início** — seção hero de apresentação
- **Sobre** — resumo profissional, links sociais e cards de habilidades
- **Projetos** — grade de cards com os trabalhos desenvolvidos
- **Contato** — formulário de contato

## 🛠️ Tecnologias Utilizadas

- **HTML5** — estruturação semântica do conteúdo
- **CSS3** — estilização, Grid Layout, Flexbox, animações e media queries para responsividade
- **[Font Awesome 6](https://fontawesome.com/)** — ícones (redes sociais e tecnologias)
- **[Google Fonts](https://fonts.google.com/)** — fonte Inter

## 📁 Estrutura de Arquivos

```
├── index.html      # Estrutura e conteúdo da página
├── style.css       # Estilização completa do site
└── README.md       # Este arquivo
```

## 🎨 Paleta de Cores

| Cor | Hex | Uso |
|---|---|---|
| Azul Grafite (fundo) | `#0f172a` | Fundo principal |
| Azul Escuro (seções) | `#1e293b` | Fundo alternado das seções |
| Ciano (destaque) | `#38bdf8` | Cor de destaque, links e botões |
| Cinza Claro (texto) | `#94a3b8` | Textos secundários |
| Branco (texto) | `#f8fafc` | Textos principais |

## 🚀 Como Executar

Como é um projeto estático (sem dependências ou build), basta:

1. Clonar o repositório
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Abrir o arquivo `index.html` diretamente no navegador

   ou, para melhor experiência (live reload), usar a extensão **Live Server** do VS Code.

## 📱 Responsividade

O layout se adapta a três faixas principais:

- **Desktop** (> 968px): grid completo com múltiplas colunas
- **Tablet** (≤ 968px): ajuste do grid "Sobre" para coluna única e projetos em 2 colunas
- **Mobile** (≤ 768px): navbar em coluna, projetos em 1 coluna e formulário empilhado

## ✏️ Personalização

Antes de publicar, lembre-se de atualizar:

- [ ] Links dos projetos em `index.html` (atualmente apontam para `seu-usuario/seu-repositorio-*`)
- [ ] Links de redes sociais (GitHub, LinkedIn, e-mail)
- [ ] Ação/integração do formulário de contato (atualmente sem back-end — ver seção abaixo)
- [ ] Imagens reais dos projetos (atualmente usando ícones como placeholder)

## ⚠️ Observações Técnicas

- O formulário de contato ainda **não possui envio funcional** (sem `action`/backend ou serviço como Formspree/EmailJS). Recomenda-se integrar um serviço de envio de e-mails ou um backend próprio.
- Há uma inconsistência estrutural na seção de projetos: as tags de âncora (`<a>`) dos cards estão aninhadas de forma incorreta, o que pode causar comportamento inesperado em alguns navegadores. Recomenda-se revisar para que cada `<a class="project-card-link">` envolva apenas seu respectivo card, sem aninhamento.

## 📄 Licença

Este projeto está disponível para uso pessoal e educacional. Sinta-se à vontade para usar como base para o seu próprio portfólio, dando os devidos créditos.

## 👤 Autor

**João Soares**

- GitHub: [@joaosoares30](https://github.com/joaosoares30)
- LinkedIn: [João Martins Pinto Soares](https://www.linkedin.com/in/jo%C3%A3o-martins-pinto-soares-bb76752ab/)
