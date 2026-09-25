# HamirStudios — Website

Site oficial da **HamirStudios**, desenvolvedora independente de software em Luanda, Angola.

## Estrutura

- `index.html` — Homepage
- `style.css` — Estilos globais
- `onara-ai/index.html` — Página do projecto Onara.AI
- `apoie/index.html` — Página de doações (IBANs)
- `sobre/index.html` — Sobre a empresa e o fundador
- `contacto/index.html` — Contactos
- `assets/` — Imagens e logotipos

## Como publicar no GitHub Pages

1. Cria um repositório **público** no GitHub: `hamirstudios-site`
2. Faz upload de todos os ficheiros deste directório
3. Vai a **Settings → Pages**
4. Em **Source**, escolhe **Deploy from a branch**
5. Escolhe a branch `main` e a pasta `/ (root)`
6. Clica **Save**
7. O site fica disponível em `https://<username>.github.io/hamirstudios-site/`

## Actualizar o site

Para actualizar conteúdo, basta editar os ficheiros localmente e fazer novo commit + push:

```bash
cd ~/hamirstudios-site
git add .
git commit -m "update: descrição da alteração"
git push
