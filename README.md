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
```

Para abrir: duplo clique no `index.html`.

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

## Checklist antes de divulgar

- [ ] Abrir no celular e conferir o menu (três riscos no canto superior direito)
- [ ] Testar todos os botões de WhatsApp — devem abrir com a mensagem pronta
- [ ] Conferir o número no link `wa.me`
- [ ] Testar os três links de projeto
- [ ] Passar o mouse nos links para ver o foco do teclado (`Tab`)
- [ ] Conferir que não há nenhum texto de exemplo sobrando
