# HGB Construtora — Site

Site institucional estático da HGB Construtora, preparado para GitHub e GitHub Pages.

## Estrutura

```text
hgb-construtora-site/
├── index.html                 # arquivo publicado pelo GitHub Pages
├── src/
│   └── index.html             # cópia-fonte para edição
├── assets/
│   └── README.md              # instruções dos arquivos locais
├── .gitignore
├── .nojekyll
└── README.md
```

## Arquivos de mídia necessários

Coloque dentro da pasta `assets/`:

- `logo-hgb.jpg`
- `construcao-casa-moderna-2.mp4`

Sem esses arquivos, a marca d'água e o vídeo local não serão carregados. O restante do site continuará funcionando.

## Ativar GitHub Pages

1. Abra o repositório no GitHub.
2. Entre em **Settings** → **Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch **main** e a pasta **/(root)**.
5. Clique em **Save**.

O `index.html` fica na raiz, portanto não é necessário build, Node.js ou framework.
