# Projeto GTI 1 — Site de Empresa de Jogos

Meu primeiro projeto front-end, desenvolvido como desafio de trainee na GTI — Empresa Júnior da UFC.

---

## Sobre o Projeto

Este site foi criado como **primeiro desafio do processo trainee da GTI**, empresa júnior da Universidade Federal do Ceará (UFC). O objetivo era direto: construir uma página web completa usando apenas HTML e CSS, sem backend ou framework, a partir de um briefing fornecido com especificações de cliente real.

O tema escolhido foi uma **empresa fictícia de desenvolvimento de jogos**, o que me permitiu explorar uma estética visual vibrante — cores neon, tipografia retrô e uma paleta dark inspirada na cultura gamer.

---

## Contexto

Na GTI, os trainees recebem um briefing com especificações de um cliente e precisam entregar uma solução funcional dentro de um prazo. Neste caso:

- **Cliente:** Iury
- **Categoria:** Empresa de Desenvolvimento de Jogos
- **Requisito:** Página completa em HTML e CSS puro, sem backend

Foi meu primeiro contato com a dinâmica de um projeto com especificações de cliente, estrutura de entrega e versionamento com Git.

---

## Tecnologias

- **HTML5** — Estrutura semântica com seções bem definidas
- **CSS3** — Estilização completa, layout e responsividade
  - CSS Grid e Flexbox para estrutura de layout
  - CSS Custom Properties (variáveis) para paleta de cores consistente
  - Scroll-Driven Animations (`animation-timeline: view()`) para animações da timeline
  - `@keyframes` para efeitos de entrada deslizante das seções
  - Media queries para responsividade (mobile, tablet, desktop)
- **Google Fonts** — `Press Start 2P` (estilo retrô/pixel) e `Roboto Slab`
- **Font Awesome 6.4.2** — Ícones de interface e redes sociais

---

## Estrutura do Site

Página única (single-page) com navegação por âncoras, composta pelas seguintes seções:

| Seção | Descrição |
|---|---|
| **Header / Nav** | Barra de navegação com links âncora para cada seção |
| **Banner** | Hero section com imagem de fundo e call-to-action |
| **Serviços** | Cards de serviços: Áudio, Design e Programação |
| **Portifólio** | Galeria com 6 jogos em cards interativos com hover |
| **Sobre** | Timeline animada com os valores da empresa |
| **Time** | Cards da equipe com links para redes sociais |
| **Clientes** | Logos dos clientes e parceiros |
| **Contato** | Formulário com layout em grid assimétrico |
| **Footer** | Copyright, redes sociais e links de termos |

---

Depois, abra o arquivo `index.html` diretamente no navegador.

> **Obs.:** As animações de scroll utilizam a Scroll-Driven Animations API (`animation-timeline: view()`). Para funcionarem corretamente, use um navegador baseado em Chromium atualizado (Chrome 115+, Edge 115+). O Firefox ainda tem suporte parcial a essa API.

---

## Paleta de Cores

| Variável CSS | Valor | Uso |
|---|---|---|
| `--color-2` | `#090C3A` | Fundo principal — azul profundo |
| `--color-4` | `#25d1f0` | Destaque ciano |
| `--color-5` | `#F363B4` | Destaque rosa/magenta — títulos e acentos |
| `--color-6` | `#3C3E73` | Fundo dos cards — roxo acinzentado |
| `--font-color-clara` | `#dbdbdb` | Texto corrido |

---

## Primeiros Passos

Este projeto é um marco honesto na minha trajetória como desenvolvedor.

Quando o desenvolvi, eu estava aprendendo as bases do front-end — descobrindo como o HTML estrutura um documento, como o CSS posiciona e estiliza elementos, e como transformar um layout estático num design com personalidade. Não havia JavaScript, nenhum framework, nenhuma abstração: só marcação e estilo.

Olhando hoje, consigo ver claramente o que era inexperiência — o `<title>` ainda está como "Document", há inconsistências de nomenclatura, escolhas de estrutura que faria diferente. Mas também consigo ver o que funcionou: a estética coesa, o grid responsivo, as animações de scroll implementadas com CSS puro usando uma API que era bastante moderna na época.

Mantenho esse repositório público porque faz parte de onde comecei. Todo desenvolvedor tem um primeiro projeto — esse é o meu.

---

## Autor

**Caio Vinicius** — Trainee GTI · UFC
