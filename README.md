# Site de serviços — Cezar Vellozo

Landing page de venda de serviços de desenvolvimento web. HTML e CSS puros, sem framework,
sem build e sem dependência externa.

**No ar:** [augusto10vellozo-coder.github.io/site-servicos](https://augusto10vellozo-coder.github.io/site-servicos/)

[![Página inicial do site de serviços](docs/preview.jpg)](https://augusto10vellozo-coder.github.io/site-servicos/)

## Arquivos

```
index.html      → estrutura e conteúdo
styles.css      → todo o estilo (comentado por seção)
logo-mark.svg   → símbolo (cabeçalho e favicon)
logo.svg        → versão completa com nome e assinatura
casos/          → case interno (controle de faturas de energia)
```

Para abrir: duplo clique no `index.html`.

## Case interno

[`casos/controle-faturas.html`](casos/controle-faturas.html) apresenta a automação de faturas de
energia: leitura de PDFs, conferência de emissão e economia solar. As capturas usam dados fictícios;
o código do sistema é privado.

## No ar

O site é publicado pelo GitHub Pages a partir da branch `main`:

```
https://augusto10vellozo-coder.github.io/site-servicos/
```

Para atualizar, edite os arquivos, faça commit e push. O Pages publica sozinho em 1–2 minutos.

## O que editar primeiro

| O que | Onde |
|---|---|
| WhatsApp | `index.html`, final do arquivo, variável `numero` (`5554994535730`) |
| Cor de destaque | `styles.css`, variável `--destaque` |
| Nome / marca | `index.html`, bloco `.marca` e rodapé |
| Textos dos serviços | `index.html`, seção `id="servicos"` |
| Projetos | `index.html`, seção `id="projetos"` (título, texto, link e imagem) |
| Perguntas frequentes | `index.html`, seção `id="perguntas"` |

## Imagens dos projetos

As três imagens da seção de projetos são carregadas dos sites que já estão no ar
(`taskbio.com.br`, o demo do painel e o Sabor de Casa). Isso mantém o projeto leve e sem
duplicar arquivos. Se quiser tudo local, baixe as imagens para uma pasta `img/` e troque os
`src` no `index.html`.

## Ao editar

- Confira o menu em tela pequena (três riscos no canto superior direito).
- Os botões de WhatsApp usam a variável `numero`, no fim do `index.html`.
- Os três links de projeto apontam para sites que já estão no ar.
- Navegue com `Tab` para conferir o foco visível.
