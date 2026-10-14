# Projetinho

    npm install
    npm run dev

## Deploy (GitHub Pages)
Troque `projetinho` pelo nome do seu repositório em: `vite.config.js` (base), `src/routes.jsx` (basename),
`index.html` (favicon), `src/pages/Home/index.jsx` (src da imagem) e `package.json` (homepage).

    git init
    git add .
    git commit -m "Primeiro commit"
    git branch -M main
    git remote add origin https://github.com/usuario-github/nome-do-repositorio.git
    git push -u origin main
    npm run deploy

Depois: Settings > Pages > Deploy from a branch > gh-pages.
