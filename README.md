# CodeStudy Pro - app mobile de estudos de programação

Versão ajustada para celular e geração de APK pelo GitHub Actions.

## O que tem

- Interface mobile com navegação inferior.
- Aulas com explicação real, modelo mental, passo a passo e exemplo comentado.
- Prática guiada com correção local básica.
- Teste rápido por aula e prova geral.
- Desafios práticos por curso.
- Progresso salvo no aparelho com localStorage.
- PWA offline com service worker.
- Estrutura pronta para Capacitor.

## Como testar no celular

Abra `index-mobile-unico.html` no navegador do celular.

## Como usar no GitHub para gerar APK

1. Crie um repositório no GitHub.
2. Envie todos os arquivos deste ZIP.
3. Entre em **Actions**.
4. Rode o workflow **Build Android APK**.
5. Baixe o APK em **Artifacts**.

## Arquivos principais

- `index.html`: versão normal.
- `styles.css`: visual do app.
- `app.js`: lógica do app.
- `data.js`: conteúdo das aulas.
- `index-mobile-unico.html`: versão em um único arquivo para teste rápido.
- `.github/workflows/build-apk.yml`: geração automática do APK.
