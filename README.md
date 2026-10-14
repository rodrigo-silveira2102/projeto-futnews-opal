# ⚽ FutNews — Agente Inteligente de Notícias

**Aplicação de inteligência artificial desenvolvida no Google Opal para automatizar a busca, organização e apresentação de notícias.**

O **FutNews** é um projeto desenvolvido durante a **Imersão de Agentes de IA para Negócios**, utilizando a plataforma Google Opal para criar um fluxo automatizado de pesquisa e apresentação de informações.

A solução combina pesquisa na web, processamento de conteúdo por inteligência artificial e geração de interfaces para transformar resultados de busca em uma experiência de consulta organizada e acessível.

---

## 🎯 Objetivo

Desenvolver um agente de inteligência artificial capaz de automatizar o processo de pesquisa, seleção e apresentação de notícias, reduzindo a necessidade de consultar diferentes fontes manualmente.

O projeto busca:

- Automatizar pesquisas de notícias na internet.
- Utilizar parâmetros definidos pelo usuário.
- Selecionar três notícias relevantes e recentes.
- Organizar os resultados com títulos, resumos e links.
- Apresentar as informações em uma interface visual.
- Explorar a criação de aplicações com IA utilizando ferramentas no-code.

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Aplicação |
|---|---|
| Google Opal | Desenvolvimento e orquestração do agente |
| Inteligência Artificial Generativa | Processamento, organização e formatação das informações |
| Pesquisa Web | Recuperação de notícias recentes |
| HTML | Estrutura da interface de apresentação |
| CSS | Estilização e organização visual |
| Prompt Engineering | Definição das instruções de cada etapa |

## 🏗️ Arquitetura do Projeto

O FutNews utiliza um fluxo de processamento construído no Google Opal, estruturado em etapas de entrada, pesquisa, processamento e apresentação de resultados.

### Etapa 1 — Entrada do Usuário

O fluxo recebe parâmetros de pesquisa que orientam o agente na identificação de notícias relevantes.

Entre os parâmetros utilizados estão:

- Setor ou assunto de interesse.
- Região geográfica.
- Data de referência.

### Etapa 2 — Pesquisa Automatizada

O agente utiliza recursos de pesquisa na web para localizar notícias relacionadas aos parâmetros informados.

As instruções solicitam a seleção de três notícias recentes, com fontes e endereços verificáveis.

### Etapa 3 — Processamento das Informações

Os resultados são organizados por inteligência artificial, utilizando uma estrutura padronizada:

- Título da notícia.
- Resumo em português do Brasil.
- Link para a fonte.
- Organização numerada dos resultados.

### Etapa 4 — Formatação

Uma etapa específica organiza as informações para apresentação, preservando os títulos e resumos e estruturando os links associados às notícias.

### Etapa 5 — Geração da Interface

O resultado é apresentado em uma página HTML, com estilização CSS e estrutura visual organizada.

A interface permite consultar as notícias selecionadas de maneira objetiva, sem necessidade de analisar manualmente os resultados brutos da pesquisa.

---

## 🧠 Inteligência Artificial Aplicada

O projeto explora o uso de IA generativa em diferentes etapas de processamento.

**Pesquisa orientada por contexto**

A busca considera os parâmetros informados pelo usuário para direcionar os resultados.

**Organização das informações**

A inteligência artificial transforma os resultados encontrados em conteúdos estruturados, facilitando sua interpretação.

**Geração de interface**

As informações processadas são utilizadas na composição de uma página HTML, demonstrando a integração entre geração de conteúdo e apresentação visual.

## 📁 Estrutura do Repositório

```text
futnews/
│
├── prompts/
│   ├── pesquisa.md
│   ├── formatacao.md
│   └── geracao-pagina.md
│
├── images/
│   ├── fluxo-opal.png
│   └── interface-final.png
│
└── README.md
```

A estrutura separa as instruções utilizadas no agente dos registros visuais do desenvolvimento.

## 🚀 Como Funciona

1. O usuário informa os parâmetros da pesquisa.
2. O agente consulta fontes disponíveis na web.
3. A inteligência artificial seleciona e organiza três notícias.
4. Os resultados são estruturados com títulos, resumos e referências.
5. O sistema gera uma apresentação visual em HTML.
6. O usuário visualiza as notícias em uma página organizada.

## 🔒 Confiabilidade das Informações

O fluxo foi projetado para utilizar notícias obtidas por pesquisa web e solicitar endereços reais para as fontes.

Entretanto, como o conteúdo é processado por inteligência artificial generativa, a conferência das informações e dos links permanece importante.

A atualidade e a precisão dos resultados dependem das fontes recuperadas e da execução da pesquisa.

## 📈 Melhorias Futuras

- Implementar filtros mais detalhados por categoria.
- Adicionar histórico de pesquisas.
- Permitir personalização da quantidade de notícias.
- Incorporar indicadores de relevância e atualidade.
- Ampliar a validação automática das fontes.
- Implementar mecanismos de comparação entre diferentes notícias.
- Expandir as opções de apresentação dos resultados.

## 📌 Considerações Finais

O FutNews demonstra a aplicação de inteligência artificial generativa na automação de processos de pesquisa e organização de informações.

O desenvolvimento com Google Opal permitiu explorar a construção de agentes de IA por meio de ferramentas no-code, integrando etapas de entrada de dados, pesquisa, processamento de conteúdo e geração de interfaces.

O projeto representa uma experiência prática de automação orientada por inteligência artificial, com possibilidades de aplicação em diferentes contextos de pesquisa, monitoramento de informações e produção de conteúdo.

---

**Projeto desenvolvido durante a Imersão de Agentes de IA para Negócios, utilizando Google Opal.**
