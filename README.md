# Secolo Martins Advocacia — Site Astro

Site institucional com cinco areas de atuacao, pagina sobre, artigos, contato e privacidade.

## Instalar no Windows (PowerShell)

1. Extraia este ZIP.
2. Copie **todo o conteudo** da pasta extraida para a raiz do repositorio `secolo-martins-advocacia` (onde esta a pasta `.git`). Nao apague a pasta `.git`.
3. Abra o terminal **nessa raiz**, onde esta `package.json`.
4. Execute:

```powershell
npm install
npm run dev
```

Se aparecer `astro nao e reconhecido`, significa que as dependencias nao foram instaladas nessa pasta. Rode `npm install` novamente e confira a mensagem de erro. Nao copie `node_modules` para o GitHub.

## Endereco local

Abra a URL indicada pelo Astro no terminal. Como `base` esta configurado para `/secolo-martins-advocacia`, tente `http://localhost:4321/secolo-martins-advocacia/`.

## Testar build

```powershell
npm run build
npm run preview
```

## Publicar no GitHub Pages

1. No repositorio GitHub, Settings > Pages > Source: **GitHub Actions**.
2. Execute `git add .`, `git commit -m "feat: site completo e deploy"` e `git push origin feature/primeira-versao`.
3. Crie um Pull Request de `feature/primeira-versao` para `main` e faca o merge.
4. Acompanhe a aba Actions. A URL sera `https://aremartins.github.io/secolo-martins-advocacia/`.

## Limitacoes importantes

- **Formulario**: desabilitado ate integrar um provedor de envio seguro e definir o e-mail oficial. Nao ha envio real ainda.
- **WhatsApp e Instagram**: aguardam os dados reais; nao foram inventados links.
- **Painel administrativo**: ainda nao implementado; edicao pelo codigo e GitHub por enquanto.
- **Artigos**: pagina informativa sem artigos ficticios.
- Este pacote foi revisado estruturalmente, mas **nao foi possivel executar `npm install`/`npm run build` neste ambiente**, pois a instalacao das dependencias expirou. Teste localmente antes de publicar.
