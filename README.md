# Livro Dona Maria

Projeto LaTeX A5 (`memoir`) para a história de Dona Maria, 1950–2025.

## Estrutura

- `main.tex` — apenas arquitetura e ordem das partes/capítulos.
- `preambulo.tex` — coordenador das configurações.
- `estilos/` — identidade visual, paginação, capítulos, imagens e referências.
- `capitulos/` — um arquivo por capítulo.
- `imagens/` — imagens separadas por universo narrativo.
- `mapas/` — mapas e cartografia.
- `bibliografia/` — banco `.bib`.
- `fontes/` — documentos e notas de pesquisa.
- `frontmatter/` — elementos pré-textuais.
- `posfacio/` — elementos finais.
- `anexos/` — material complementar.

## Regra narrativa

Cada capítulo deve transitar entre:
1. contexto histórico;
2. fatos documentados;
3. vida de Dona Maria;
4. memória familiar.

O contexto histórico não deve sufocar a narrativa biográfica.

## Compilação

Para a versão com bibliografia via Biber:

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

No VS Code/LaTeX Workshop, prefira uma receita que use `pdflatex -> biber -> pdflatex -> pdflatex`.

## Nota importante

O primeiro capítulo contém o protótipo com a fotografia do Sputnik. Os demais arquivos são apenas contêineres de conteúdo neste estágio.
