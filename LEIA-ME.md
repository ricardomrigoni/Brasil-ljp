# Brasil — Liberdade, Justiça e Poder (versão app)

Pasta pronta para o GitHub Pages. Depois de publicada, o site pode ser instalado no celular como app e funciona sem internet.

## Arquivos
- `index.html` — o site completo
- `manifest.webmanifest` — nome, cores e ícones do app
- `sw.js` — guarda o site no aparelho (uso offline)
- `icons/` — ícones do app
- `.nojekyll` — avisa o GitHub para publicar os arquivos como estão

## Publicar no GitHub Pages (pelo navegador, sem programar)
1. Entre em github.com e crie uma conta, se ainda não tiver.
2. Clique em **New repository**. Dê um nome (ex.: `brasil-ljp`), marque **Public** e clique em **Create repository**.
3. Na página do repositório, clique em **uploading an existing file**.
4. Arraste para a janela **todo o conteúdo desta pasta** (index.html, manifest.webmanifest, sw.js, .nojekyll e a pasta icons). Clique em **Commit changes**.
   - O `.nojekyll` começa com ponto e pode ficar oculto no seu computador. Ele é opcional; se não aparecer, siga sem ele.
5. Vá em **Settings → Pages**. Em **Branch**, escolha `main` e a pasta `/ (root)`. Clique em **Save**.
6. Espere 1 ou 2 minutos. O endereço aparece no topo da mesma página: `https://SEU-USUARIO.github.io/brasil-ljp/`.

## Instalar no celular
- **iPhone:** abra o endereço no Safari → botão Compartilhar → **Adicionar à Tela de Início**.
- **Android:** abra no Chrome → menu ⋮ → **Instalar app** (ou **Adicionar à tela inicial**).

## Atualizar depois
1. No repositório, use **Add file → Upload files** e envie o novo `index.html` (ele substitui o antigo).
2. Abra `sw.js`, clique no lápis e troque `ljp-v13` por um número novo (ex.: `ljp-v14`). Salve.
3. No celular, feche e abra o app duas vezes para ele pegar a versão nova.

## Atenção
No plano gratuito, o GitHub Pages é **público**: qualquer pessoa com o endereço consegue abrir o site.
