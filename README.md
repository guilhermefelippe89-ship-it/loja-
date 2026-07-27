# Loja Virtual

Site estático (HTML/CSS/JS puro, sem build) da loja.

## Deploy automático (GitHub → Netlify)

1. Suba esta pasta para um repositório no GitHub.
2. No Netlify: **Add new site → Import an existing project → GitHub** → selecione o repositório.
3. Build settings:
   - **Build command:** (deixe em branco)
   - **Publish directory:** `.`
4. Clique em **Deploy site**.

A partir daí, todo `git push` para a branch principal gera um novo deploy automático.
