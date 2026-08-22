# Sobre o projeto

Este projeto nasceu com o objetivo de disponibilizar um material didático completo, **gratuito** e de **código aberto** sobre a linguagem C, escrito inteiramente em **Português do Brasil**. Seja você um iniciante ou um programador experiente buscando revisitar os fundamentos.

Como um projeto colaborativo, convidamos toda a comunidade a contribuir com sugestões, correções e melhorias. Abaixo você encontra um guia prático para entender a estrutura do projeto e como pode nos ajudar.

## Estrutura do projeto

Para manter o conteúdo organizado e facilitar a colaboração, optamos por dividir cada capítulo do livro em uma pasta dentro de `chapters/`. Cada pasta contém um arquivo com o nome do capítulo, que define suas seções e inclui as partes do conteúdo, além de um arquivo `.tex` separado para cada parte. O arquivo principal (`descompilando.tex`) é responsável por juntar todos esses capítulos na compilação final do PDF.

```
. /descompilando/
├── chapters
│   ├── indice
│   │   ├── indice.tex
│   │   ├── sobre_o_autor.tex
│   │   └── sobre_o_livro.tex
│   ├── introducao-a-linguagem-c
│   │   ├── beneficios_e_aplicacoes.tex
│   │   ├── historia_e_contexto.tex
│   │   └── introducao-a-linguagem-c.tex
│   ├── ambiente-de-desenvolvimento
│   │   ├── ambiente-de-desenvolvimento.tex
│   │   ├── configuracao_do_ambiente.tex
│   │   └── primeiro_programa.tex
│   ├── conceitos-basicos-de-programacao
│   │   ├── conceitos-basicos-de-programacao.tex
│   │   ├── operadores.tex
│   │   ├── variaveis_e_tipos_de_dados.tex
│   │   ├── conversao_de_tipos.tex
│   │   ├── funcoes.tex
│   │   ├── bibliotecas.tex
│   │   ├── escopo.tex
│   │   ├── condicionais_e_loops.tex
│   │   ├── entrada_e_saida_de_dados.tex
│   │   └── manipulacao-de-arquivos.tex
│   ├── estrutura-de-dados-e-memoria
│   │   ├── estrutura-de-dados-e-memoria.tex
│   │   ├── introducao_estrutura_de_dados_e_memoria.tex
│   │   ├── o-que-sao-enderecos.tex
│   │   ├── o-que-sao-ponteiros.tex
│   │   ├── vetores.tex
│   │   ├── alocacao-de-memoria.tex
│   │   └── secoes-da-memoria.tex
│   ├── extra
│   │   ├── extra.tex
│   │   ├── manipulacao-de-bits.tex
│   │   ├── depuracao.tex
│   │   └── padrao_c23.tex
│   └── consideracoes-finais
│       ├── consideracoes-finais.tex
│       └── obrigado.tex
├── images
│   └── illustrations
│       ├── array-in-memory-example.png
│       ├── memory-address-example.png
│       └── memory-segments.png
├── descompilando.tex
└── README.md
```

### Detalhes importantes sobre a estrutura do projeto

- **Capítulos fracionados**: Cada capítulo possui sua própria pasta em `chapters/`, e cada seção do livro possui seu próprio arquivo `.tex` dentro dela. Isso evita conflitos em pull requests e torna mais fácil localizar onde fazer uma alteração específica.
- **Arquivo do capítulo**: O arquivo `.tex` com o nome da pasta do capítulo (ex: `chapters/extra/extra.tex`) é quem agrupa as seções (`\section`/`\subsection`) e inclui as partes via `\input`. Para adicionar uma nova seção, basta editá-lo — não é necessário mexer no `descompilando.tex`.
- **Imagens**: Todas as imagens devem ser armazenadas na pasta `images/`, usando um endereço relativo ao tipo de imagem utilizada. (como o `images/illustrations` para ilustrações)

## Política de Versionamento (Releases)

Após acumular um conjunto relevante de melhorias, publicaremos novas versões do livro. Para manter a consistência e previsibilidade, adotamos o seguinte esquema de versionamento:

- **`1.1.x`** → Atualizações **pequenas** (ex: correção de erros ortográficos, ajustes pontuais em exemplos de código).
- **`1.x.x`** → Atualizações **medianas** (ex: reformatação geral, padronização de termos técnicos ao longo de toda a obra).
- **`x.x.x`** → Atualizações **grandes** (ex: adição de um novo capítulo, reestruturação significativa do conteúdo).

## Como Contribuir

Todos são muito bem-vindos para colaborar com o projeto! Você pode ajudar de diversas formas, independentemente do seu nível de conhecimento em C ou LaTeX. Consulte o guia completo em [CONTRIBUTING.md](CONTRIBUTING.md).
