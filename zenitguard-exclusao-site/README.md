# ZenitGuard — página de exclusão de conta (Play Console)

Site de **uma página** só para colar a URL no Google Play (**Segurança dos dados → exclusão de contas**).

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `zenitguard-exclusao`) — pode ser **público**.
2. Envie **toda esta pasta** para a raiz do repositório (`index.html`, `CNAME`, `.nojekyll`).
3. No GitHub: **Settings → Pages**
   - **Source:** Deploy from branch
   - **Branch:** `main` / pasta **`/ (root)`**
   - Salvar
4. Aguarde 1–5 min. O site fica em:
   - `https://SEU_USUARIO.github.io/zenitguard-exclusao/`  
   (se o repo tiver outro nome, a URL segue o nome do repo)

## Domínio personalizado (como no site principal)

1. Edite o arquivo **`CNAME`** e coloque **um** domínio (exemplo):
   ```
   exclusao.zenitguard.com
   ```
2. No painel do seu domínio, crie um registro **CNAME**:
   - Nome: `exclusao` (ou o subdomínio que escolher)
   - Aponta para: `SEU_USUARIO.github.io`
3. No GitHub Pages, em **Custom domain**, confirme o mesmo domínio e ative **HTTPS** (pode demorar até 24 h).

**URL para o Play Console:**  
`https://exclusao.zenitguard.com/` (ou a URL do GitHub Pages, se não usar domínio)

## Ajustar e-mail

Troque `privacidade@zenitguard.com` em `index.html` (texto e link `mailto:`) pelo e-mail real dos administradores.

## Arquivos

| Arquivo      | Função                          |
|-------------|----------------------------------|
| `index.html`| Página exigida pelo Google Play |
| `CNAME`     | Subdomínio customizado (opcional)|
| `.nojekyll` | Evita problemas no GitHub Pages |
