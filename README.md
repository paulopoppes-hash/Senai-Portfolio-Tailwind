# Senai-Portfolio-Tailwind

Portfolio de Projetos — Tailwind CSS

## Descrição

Página de portfolio de projetos desenvolvida com **HTML5** e **Tailwind CSS**, conforme proposto na **Aula 07 - Atividade 02** da disciplina Frameworks Front-end.

O objetivo da atividade é criar um projeto que utilize **pelo menos 30 classes utilitárias diferentes** do Tailwind CSS, aplicando cores, tipografia, espaçamentos, dimensões, bordas, posicionamento, flexbox, grid e responsividade. A entrega deve incluir prints do código, da aplicação em funcionamento, uma lista das classes utilizadas com suas respectivas funções e o link para o projeto desenvolvido.

O portfolio apresenta uma navegação fixa, uma seção de destaque (hero), uma grade de projetos com cards, uma seção de habilidades com tags e um rodapé — tudo estilizado exclusivamente com classes utilitárias do Tailwind, sem nenhum CSS customizado.

## Tecnologias utilizadas

- **HTML5** — estrutura semântica da página
- **Tailwind CSS (via CDN)** — framework CSS Utility-First para estilização

## Como o protótipo funciona

O portfolio e dividido nas seguintes seções:

1. **Navegação (`<nav>`)**: barra de navegação fixa no topo (`sticky top-0 z-50`) com links para Início, Projetos, Sobre e Contato.
2. **Hero / Seção de destaque (`<section>`)**: fundo `bg-indigo-900` com texto branco, título grande (`text-5xl font-bold`) e um botão de chamada para ação.
3. **Grade de projetos**: layout em grid responsivo (`grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8`) com cards (`bg-white rounded-xl shadow-md p-6 hover:shadow-lg transition border border-gray-100`) contendo ícone, título, descrição e link.
4. **Seção de habilidades**: fundo `bg-gray-100` com tags de habilidades (`px-4 py-2 bg-white border border-gray-300 rounded-full text-sm font-medium`) organizadas com `flex flex-wrap justify-center gap-4`.
5. **Rodapé (`<footer>`)**: simples com texto centralizado e borda superior (`border-t border-gray-200 py-8 text-center text-gray-500`).

Todas as cores, espaçamentos, dimensões, bordas e disposições são controladas exclusivamente por classes utilitárias do Tailwind, demonstrando a abordagem Utility-First.

## Lista detalhada das classes utilitárias aplicadas (30+)

Abaixo, todas as classes do Tailwind utilizadas no projeto, organizadas por categoria, com suas respectivas funções:

### Layout e Flexbox / Grid
| Classe | Função |
|--------|--------|
| `flex` | Define display flex |
| `flex-col` | Direção dos itens em coluna |
| `grid` | Define display grid |
| `grid-cols-1` | Uma coluna no grid base |
| `md:grid-cols-2` | Duas colunas em telas médias |
| `lg:grid-cols-3` | Três colunas em telas grandes |
| `gap-4` | Espaço de 1rem entre itens |
| `gap-8` | Espaço de 2rem entre itens |
| `items-center` | Alinhamento central vertical (flex/grid) |
| `justify-center` | Alinhamento central horizontal (flex/grid) |
| `justify-between` | Espaço entre itens nas extremidades |
| `flex-wrap` | Permite quebra de linha em flexbox |

### Espaçamentos (Padding / Margin)
| Classe | Função |
|--------|--------|
| `p-4` | Padding de 1rem em todos os lados |
| `p-6` | Padding de 1.5rem em todos os lados |
| `px-4` | Padding horizontal de 1rem |
| `py-16` | Padding vertical de 4rem |
| `mb-4` | Margin-bottom de 1rem |
| `mt-8` | Margin-top de 2rem |
| `mt-16` | Margin-top de 4rem |
| `mx-auto` | Margin horizontal automático (centraliza) |

### Dimensões (Largura / Altura / Tamanho máximo)
| Classe | Função |
|--------|--------|
| `w-16` | Largura de 4rem (64px) |
| `h-16` | Altura de 4rem (64px) |
| `max-w-6xl` | Largura máxima de 72rem |
| `max-w-2xl` | Largura máxima de 42rem |
| `min-w-0` | Largura mínima zero |

### Cores (Background e Texto)
| Classe | Função |
|--------|--------|
| `bg-white` | Fundo branco |
| `bg-gray-50` | Fundo cinza quase branco |
| `bg-indigo-900` | Fundo indigo escuro (hero) |
| `bg-indigo-100` | Fundo indigo claro |
| `bg-green-100` | Fundo verde claro (ícones) |
| `bg-blue-100` | Fundo azul claro |
| `bg-purple-100` | Fundo roxo claro |
| `bg-pink-100` | Fundo rosa claro |
| `bg-orange-100` | Fundo laranja claro |
| `text-white` | Texto branco |
| `text-gray-900` | Texto cinza escuro |
| `text-gray-600` | Texto cinza médio |
| `text-gray-500` | Texto cinza claro |
| `text-indigo-600` | Texto indigo |

### Bordas e Arredondamento
| Classe | Função |
|--------|--------|
| `border` | Borda de 1px |
| `border-gray-100` | Borda cinza claro |
| `border-gray-200` | Borda cinza muito claro |
| `border-t` | Borda apenas no topo |
| `rounded-xl` | Borda arredondada de 0.75rem (12px) |
| `rounded-lg` | Borda arredondada de 0.5rem (8px) |
| `rounded-full` | Borda completamente arredondada (círculo/pílula) |

### Tipografia
| Classe | Função |
|--------|--------|
| `text-5xl` | Tamanho de fonte 3rem (h1 hero) |
| `text-3xl` | Tamanho de fonte 1.875rem (títulos de seção) |
| `text-xl` | Tamanho de fonte 1.25rem |
| `text-lg` | Tamanho de fonte 1.125rem |
| `text-sm` | Tamanho de fonte 0.875rem |
| `font-bold` | Peso de fonte 700 |
| `font-semibold` | Peso de fonte 600 |
| `font-medium` | Peso de fonte 500 |
| `text-center` | Alinhamento de texto central |

### Posicionamento
| Classe | Função |
|--------|--------|
| `sticky` | Posicionamento sticky |
| `top-0` | Fixo no topo quando sticky |
| `z-50` | Índice de camadas (z-index) 50 |

### Responsividade (prefixos)
| Classe | Função |
|--------|--------|
| `md:` | Aplica a partir de telas médias (768px) |
| `lg:` | Aplica a partir de telas grandes (1024px) |
| `md:grid-cols-2` | Grid com 2 colunas em md |
| `lg:grid-cols-3` | Grid com 3 colunas em lg |

### Efeitos e Utilitários
| Classe | Função |
|--------|--------|
| `shadow` | Sombra simples |
| `shadow-md` | Sombra média |
| `shadow-lg` | Sombra grande |
| `hover:shadow-lg` | Sombra grande ao passar o mouse |
| `transition` | Transição suave em mudanças |
| `text-decoration: underline` via hover | Sublinhado no hover |

**Total de classes utilitárias distintas utilizadas: mais de 35 classes.**

## Como executar

1. Abra o arquivo `index.html` em qualquer navegador moderno.
2. O Tailwind CSS e carregado via CDN (`<script src="https://cdn.tailwindcss.com">`), portanto e necessaria conexão com a internet para que os estilos sejam aplicados.

Não e necessária instalação de dependências (`npm install`) pois o projeto utiliza o Tailwind via CDN.

## Requisitos atendidos (Aula 07 - Atividade 02)

- [x] Projeto com pelo menos 30 classes diferentes do Tailwind CSS
- [x] Classes para cores, tipografia, espaçamentos, dimensões, bordas, posicionamento, flexbox, grid e responsividade
- [x] Documentação com lista das classes utilizadas e suas respectivas funções
- [x] Link para o projeto desenvolvido

## Repositorio principal

[senai-framework-frontend](https://github.com/paulopoppes-hash/senai-framework-frontend)
