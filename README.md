 # Dona Maria — Uma vida entre décadas

Projeto de um livro estruturado em **LaTeX** sobre a jornada de Dona Maria, nascida em **1953**. A obra acompanha sua história pessoal em diálogo com as transformações do mundo e do Brasil, percorrendo o período de **1950 a 2025**.

## Estrutura do livro

Cada década será organizada em três perspectivas:

1. **O mundo na década** — acontecimentos históricos, culturais, sociais e tecnológicos.
2. **O Brasil na década** — contexto político, econômico e cultural do país.
3. **A vida de Dona Maria na década** — memórias, experiências, relações, desafios e conquistas pessoais.

### Períodos abordados

- Décadas de 1950 e 1960
- Década de 1970
- Década de 1980
- Década de 1990
- Década de 2000
- Década de 2010
- Anos de 2020 a 2025

## Objetivos

- Registrar a trajetória e as memórias de Dona Maria.
- Contextualizar sua vida no tempo e no espaço.
- Preservar histórias familiares para as próximas gerações.
- Produzir um livro organizado, editável e compilável em LaTeX.

## Organização sugerida

```text
.
├── README.md
├── main.tex
├── chapters/
│   ├── decada-1950-1960.tex
│   ├── decada-1970.tex
│   ├── decada-1980.tex
│   ├── decada-1990.tex
│   ├── decada-2000.tex
│   ├── decada-2010.tex
│   └── 2020-2025.tex
├── images/
└── bibliography.bib
```

## Como compilar

Com uma distribuição LaTeX instalada, execute:

```bash
pdflatex main.tex
pdflatex main.tex
```

Ou utilize uma ferramenta como `latexmk`:

```bash
latexmk -pdf main.tex
```

## Observação

O conteúdo histórico servirá como contexto para as memórias pessoais. As informações biográficas, fotografias e relatos de Dona Maria devem ser reunidos e revisados com a família antes da publicação.
