# Site Visual Veículos — como publicar no GitHub Pages

## O que tem nesta pasta

- `index.html`: o site (página inicial).
- `Logo Animada.dc.html`: a logo animada do topo, carregada pelo `index.html`.
- `support.js`: o código que monta a página no navegador.
- `_ds/`: estilos (cores, espaçamentos, botões).
- `assets/`: logo, fotos dos carros, miniaturas, fachada e logos das marcas.
- `.nojekyll`: arquivo vazio que precisa estar na raiz. Sem ele, o GitHub ignora a pasta `_ds` e o site fica sem estilo.

Não renomeie nem mova os arquivos: os caminhos são relativos.

## Passo a passo

1. Entre em github.com e crie um repositório novo (por exemplo `visual-veiculos`), público.
2. Na página do repositório, clique em **Add file → Upload files**.
3. Arraste **todo o conteúdo desta pasta** (não a pasta em si) para a área de upload. Confira se `index.html`, `.nojekyll`, `_ds` e `assets` estão na raiz.
   - O arquivo `.nojekyll` começa com ponto e pode ficar oculto no seu computador. No Windows: Explorador de Arquivos → Exibir → Itens ocultos. No Mac: Cmd + Shift + ponto.
4. Clique em **Commit changes**.
5. Vá em **Settings → Pages**. Em **Source**, escolha **Deploy from a branch**; em **Branch**, escolha `main` e a pasta `/ (root)`. Clique em **Save**.
6. Em 1 a 3 minutos o endereço aparece no topo dessa mesma tela, no formato `https://SEU-USUARIO.github.io/visual-veiculos/`.

## Domínio próprio (opcional)

Para usar algo como `www.visualveiculos.com.br`:

1. Em **Settings → Pages → Custom domain**, digite o domínio e salve.
2. No painel onde o domínio foi registrado (Registro.br, por exemplo), crie um registro **CNAME** de `www` apontando para `SEU-USUARIO.github.io`.
3. Depois que o domínio funcionar, marque **Enforce HTTPS**.

## Atualizar o site depois

Para trocar fotos ou carros, envie os arquivos novos pelo mesmo **Add file → Upload files**. Arquivos com o mesmo nome são substituídos. O site atualiza sozinho em alguns minutos.

## Antes de publicar

- Confira o ano do Civic, da Saveiro e do HB20, que não estavam nos anúncios.
- Confira as cores dos carros na ficha.
- O mapa usa o endereço Rua Gustavo Bülow, 2673 — Coronel Brito, Venâncio Aires/RS.
