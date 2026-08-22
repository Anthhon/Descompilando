# Sobre o projeto

Este projeto nasceu com o objetivo de disponibilizar um material didático completo, **gratuito** e de **código aberto** sobre a linguagem C, escrito inteiramente em **Português do Brasil**. Seja você um iniciante ou um programador experiente buscando revisitar os fundamentos.

Como um projeto colaborativo, convidamos toda a comunidade a contribuir com sugestões, correções e melhorias. Abaixo você encontra um guia prático para entender a estrutura do projeto e como pode nos ajudar.

## Estrutura do projeto

Para manter o conteúdo organizado e facilitar a colaboração, optamos por dividir cada tópico do livro em um arquivo `.tex` separado. O arquivo principal (`descompilando.tex`) é responsável por juntar todos esses capítulos na compilação final do PDF.

```
. /descompilando/
├── alocacao-de-memoria.tex
├── beneficios_e_aplicacoes.tex
├── bibliotecas.tex
├── condicionais_e_loops.tex
├── configuracao_do_ambiente.tex
├── conversao_de_tipos.tex
├── depuracao.tex
├── descompilando.aux
├── descompilando.log
├── descompilando.pdf
├── descompilando.tex
├── descompilando.toc
├── entrada_e_saida_de_dados.tex
├── escopo.tex
├── funcoes.tex
├── historia_e_contexto.tex
├── images
│   └── illustrations
│       ├── array-in-memory-example.png
│       ├── memory-address-example.png
│       └── memory-segments.png
├── introducao_estrutura_de_dados_e_memoria.tex
├── manipulacao-de-arquivos.tex
├── manipulacao-de-bits.tex
├── obrigado.tex
├── operadores.tex
├── o-que-sao-enderecos.tex
├── o-que-sao-ponteiros.tex
├── padrao_c23.tex
├── primeiro_programa.tex
├── secoes-da-memoria.tex
├── sobre_o_autor.tex
├── sobre_o_livro.tex
├── texput.log
├── variaveis_e_tipos_de_dados.tex
└── vetores.tex
```

### Detalhes importantes sobre a estrutura do projeto

- **Arquivos fracionados**: Cada seção do livro possui seu próprio arquivo `.tex`. Isso evita conflitos em pull requests e torna mais fácil localizar onde fazer uma alteração específica.
- **Imagens**: Todas as imagens devem ser armazenadas na pasta `images/`, usando um endereço relativo ao tipo de imagem utilizada. (como o `images/illustrations` para ilustrações)

## Política de Versionamento (Releases)

Após acumular um conjunto relevante de melhorias, publicaremos novas versões do livro. Para manter a consistência e previsibilidade, adotamos o seguinte esquema de versionamento:

- **`1.1.x`** → Atualizações **pequenas** (ex: correção de erros ortográficos, ajustes pontuais em exemplos de código).
- **`1.x.x`** → Atualizações **medianas** (ex: reformatação geral, padronização de termos técnicos ao longo de toda a obra).
- **`x.x.x`** → Atualizações **grandes** (ex: adição de um novo capítulo, reestruturação significativa do conteúdo).

## Como Contribuir

Todos são muito bem-vindos para colaborar com o projeto! Você pode ajudar de diversas formas, independentemente do seu nível de conhecimento em C ou LaTeX.

### Por onde começar?
1. **Issues**: Encontrou um erro de digitação, um bug no código de exemplo ou tem uma sugestão de melhoria? Abra uma *issue* descrevendo o problema ou a ideia. Ficarei feliz em discutir o assunto com você (e outras pessoas interessadas também podem participar).
2. **Pull Requests (PRs)**: Se você já sabe exatamente o que precisa ser alterado, sinta-se à vontade para corrigir diretamente nos arquivos e abrir um *pull request*. Quanto mais claro for o título e a descrição do PR, mais rápido conseguiremos revisá-lo e mesclá-lo.
3. **E-mail**: Caso prefira um contato mais direto ou não se sinta confortável com o GitHub, você também pode enviar suas reclamações, sugestões ou dúvidas por e-mail (endereço disponível no meu perfil ou nos metadados do projeto).

**Agradecemos imensamente seu interesse e apoio!**
