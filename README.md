# Carta em Chamas

Um espaço pra escrever o que precisa sair — e depois queimar. Sem login, sem banco de dados, sem `localStorage`, sem analytics. O texto vive só na memória da aba enquanto você digita; ao clicar em **queimar** (ou fechar a página), ele desaparece de verdade.

100% estático — um único `index.html` com CSS e JS embutidos. Sem build, sem dependências além de fontes do Google Fonts.

## Rodar localmente

Só abrir o `index.html` no navegador. Não precisa de servidor.

## Publicar no GitHub Pages

```bash
git init
git add .
git commit -m "primeira versão"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/carta-em-chamas.git
git push -u origin main
```

Depois, no repositório no GitHub: **Settings → Pages → Source: Deploy from a branch → main / (root)**. Em alguns minutos o app fica em `https://SEU_USUARIO.github.io/carta-em-chamas/`.

## Por que é seguro deixar público

O repositório é só o código-fonte de uma página estática — não existe backend, não existe onde os textos das pessoas iriam parar. Cada visitante roda o app isolado na própria máquina; nada volta pra você nem pra ninguém.

## Estrutura

```
carta-em-chamas/
├── index.html   # tudo: markup, estilos e o script da queima
└── README.md
```
