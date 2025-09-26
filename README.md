# Wiki Grupo Ora — GitHub Pages (v2)

Este pacote está **pronto para publicar no GitHub Pages**.

## Passos
1. Crie um repositório e **faça upload de tudo na raiz** (incluindo `index.html`, `.nojekyll`, `assets/`, `data/` e as pastas de conteúdo).  
2. Em **Settings → Pages**: Source = *Deploy from a branch*, Branch = *main* e Folder = */(root)*.  
3. Acesse o link do Pages.  
4. Para adicionar/editar cartões da home, edite `data/wiki.json`.

## Observações
- `.nojekyll` garante que arquivos/pastas com `_` não sejam ignorados.  
- `viewer.html` renderiza Markdown no navegador (sem build).  
- Você pode apontar links do `wiki.json` para arquivos `.md` **ou** links externos (Drive/Docs/Sites).
