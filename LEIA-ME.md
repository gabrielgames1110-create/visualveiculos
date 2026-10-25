# Site Visual Veículos — como publicar no GitHub Pages

Esta pasta tem 95 arquivos. O envio pelo site do GitHub aceita até 100 arquivos de uma vez, então dá para mandar tudo junto.

## O que tem aqui

- `index.html`: o site.
- `Logo Animada.dc.html`: a logo animada do topo.
- `support.js`: o código que monta a página no navegador.
- `ds/`: estilos do site.
- `assets/`: logo, fotos dos carros, fachada e logos das marcas.

Não renomeie nem mova nada. O GitHub diferencia maiúsculas de minúsculas nos nomes.

## Passo a passo

1. Se você já tinha enviado a versão anterior, apague o repositório antigo (Settings → Delete this repository) ou crie um novo. Assim não sobra arquivo antigo misturado.
2. Crie um repositório público, por exemplo `visual-veiculos`.
3. Na página do repositório, clique em **uploading an existing file** (ou **Add file → Upload files**).
4. Abra esta pasta no computador, selecione **tudo o que está dentro dela** (Ctrl+A no Windows, Cmd+A no Mac) e **arraste** para a área de upload do GitHub.
   - Arraste. O botão "choose your files" não envia pastas, e aí as fotos ficam de fora.
   - Espere a lista terminar de carregar. Ela precisa mostrar as pastas `assets` e `ds`.
5. Clique em **Commit changes**.
6. Vá em **Settings → Pages**. Em **Source**, escolha **Deploy from a branch**. Em **Branch**, escolha `main` e `/ (root)`. Clique em **Save**.
7. Em 1 a 3 minutos o endereço aparece nessa mesma tela: `https://SEU-USUARIO.github.io/visual-veiculos/`.

## Conferir se subiu certo

Na página principal do repositório, você deve ver `assets`, `ds`, `index.html`, `Logo Animada.dc.html`, `support.js` e `LEIA-ME.md`. Dentro de `assets/estoque`, devem aparecer as 5 pastas dos carros, com as fotos `01.webp`, `02.webp` etc.

Se faltar alguma pasta, envie só ela de novo pelo mesmo caminho (Add file → Upload files, arrastando a pasta).

## Atualizar depois

Envie os arquivos novos pelo mesmo caminho. Arquivos com o mesmo nome são substituídos. O site atualiza em alguns minutos.
