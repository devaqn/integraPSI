# ✅ O que foi entregue — Integra Psicanálise

---

## 🌐 Site Institucional

O site completo da Integra Psicanálise, desenvolvido do zero, sem template, com identidade visual exclusiva.

### O que o site tem:

- **Página principal** com todas as seções integradas em uma única experiência fluida
- **Hero animado** com foto da sede, estatísticas do curso e chamadas de ação
- **Barra de confiança** com os 4 diferenciais da escola (formação reconhecida, unidades, turmas ativas, pluralidade)
- **Seção "Por que a Integra?"** com foto, texto institucional e lista de diferenciais
- **5 cards de módulos** interativos — ao tocar/passar o mouse, cada card se expande e mostra as disciplinas daquele módulo
- **Mural de professores** com fotos e descrições, navegável no mobile
- **Depoimentos** de alunos com design de cartão limpo
- **Seção de unidades** com as 4 cidades (Recife sede, Caruaru, Campina Grande e João Pessoa)
- **Card de expansão** com bússola animada e botão de votação para a próxima cidade
- **Condições de ingresso** com scroll horizontal no mobile
- **FAQ** com perguntas e respostas colapsáveis
- **Formulário de contato** funcional (integrado ao Netlify)
- **Botão WhatsApp flutuante** com animação de atenção periódica
- **Botão voltar ao topo**
- **Loader animado** com o símbolo da escola ao navegar entre páginas
- **Flash da logo** ao clicar em qualquer botão

### Páginas:
- `index.html` — Página principal
- `sede/recife.html` — Página da unidade sede (Recife)
- `sede/caruaru.html` — Página da unidade Caruaru
- `sede/campina-grande.html` — Página da unidade Campina Grande
- `sede/joao-pessoa.html` — Página da unidade João Pessoa

### Tecnologias:
Desenvolvido em HTML, CSS e JavaScript puros — sem WordPress, sem plugins, sem dependências externas. Roda rápido, é fácil de manter e não gera custos de plataforma.

---

## 📄 Landing Page de Conversão

Uma página separada, focada em capturar inscrições. Mais direta e persuasiva que o site principal.

### O que a landing page tem:

- **Header fixo** com logo e botão de contato imediato
- **Hero de alta conversão** com título, subtítulo, estatísticas (5 módulos, 27 disciplinas, 1.500h, 4 unidades) e dois botões de ação
- **Barra de credibilidade** com ícones e frases de confiança
- **Seção "Por que a Integra?"** resumida com os 3 pilares principais
- **5 cards de módulos** com efeito visual ao passar o mouse
- **Depoimentos** de alunos reais
- **Seção de unidades** com cards de cada cidade
- **Card de votação** com bússola animada para a próxima filial
- **FAQ** com respostas colapsáveis (abre uma de cada vez)
- **CTA final** em fundo terracota com chamada direta para inscrição
- **Botão WhatsApp flutuante** com animação de atenção
- **Botão voltar ao topo**
- **Flash da logo** ao clicar em qualquer botão

---

## 🤖 Bot de WhatsApp

Um atendente automático profissional que funciona 24 horas por dia no WhatsApp da escola.

### O que o bot faz:

- **Recebe e boas-vindas** qualquer pessoa que manda mensagem pela primeira vez
- **Exibe um menu organizado** com as opções: Sobre o curso, Módulos, Unidades, Processo seletivo, Falar com consultor
- **Responde automaticamente** cada opção com informações completas e formatadas
- **Lista todas as 4 unidades** com nome, cidade e estado
- **Apresenta os 5 módulos** com nome e número de disciplinas
- **Conecta o interessado com um consultor** — ao escolher essa opção, o bot notifica um administrador no WhatsApp com o nome e o link direto para o contato do cliente
- **Funciona com qualquer número** — mesmo que o contato esteja salvo no celular (resolve automaticamente o número real)
- **Roda em servidor 24h** via PM2 (gerenciador de processos)

---

## 🎨 Identidade Visual

Toda a identidade foi desenvolvida com consistência entre site, landing page e bot:

| Elemento       | Valor        |
|----------------|--------------|
| Cor principal  | Terracota `#8C3211` |
| Cor de acento  | Lima `#A8C640` |
| Cor de fundo   | Off-white `#FAF8F5` |
| Cor de destaque | Creme `#F2E6DF` |
| Tipografia | Serif elegante + Sans moderno |

---

## 🔧 Infraestrutura

- **Hospedagem:** Netlify (deploy automático)
- **Formulário:** Netlify Forms (sem back-end necessário)
- **Bot:** Node.js + PM2 (servidor dedicado)
- **Redirecionamentos:** configurados via `_redirects`
- **Segurança:** headers HTTP configurados via `netlify.toml`
- **Código comentado:** todos os arquivos têm comentários explicativos para facilitar edições futuras

---

## 📦 Arquivos entregues

```
Raiz do projeto
├── index.html              — Site principal
├── landing/                — Landing page de conversão
│   ├── index.html
│   ├── landing.css
│   └── landing.js
├── sede/                   — Páginas de cada unidade
│   ├── recife.html
│   ├── caruaru.html
│   ├── campina-grande.html
│   └── joao-pessoa.html
├── assets/
│   ├── css/style.css       — Estilo global
│   └── js/main.js          — JavaScript global
├── bot integrapsiwhatsapp/ — Código do bot
├── _redirects              — Rotas Netlify
└── netlify.toml            — Headers de segurança
```

---

*Desenvolvido exclusivamente para a Integra Psicanálise — A Nova Escola.*
