# Splash de Logo — Vercel

Site estático minimalista com **fundo preto** e **logo centralizada**.

## Como usar

1. Substitua `assets/logo.svg` pela sua logo (`.svg` recomendado ou `.png`).  
   - Se usar PNG, mantenha o mesmo nome **logo.svg** ou altere o `src` em `index.html` para o arquivo novo.
2. (Opcional) Edite `styles.css` se quiser alterar o efeito de *pulse* ou desativar a animação.

## Deploy na Vercel

### Método 1 — Pelo site
1. Vá em **vercel.com/new** e escolha **Import Project**.
2. Selecione a pasta deste projeto (ou o repositório no GitHub).
3. A Vercel detecta como **Static Site**. Clique em **Deploy**.

### Método 2 — Vercel CLI
```bash
npm i -g vercel
vercel
```
> Aceite as opções padrão. Depois use `vercel --prod` para publicar em produção.

## FAQ
- **Preciso de `vercel.json`?** Não. Para este projeto estático simples não é necessário.
- **Como mudo o fundo?** Em `styles.css`, altere `--bg`.
- **Como torno a logo menor/maior?** Ajuste `max-width` da classe `.logo`.
