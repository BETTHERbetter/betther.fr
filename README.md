# Site BETTHER

Site vitrine one-page pour BETTHER — Bureau d'étude thermique.
Le site est **entièrement contenu dans `index.html`** (images, vidéo et polices sont embarquées ; seules les animations utilisent un script GSAP chargé depuis un CDN public). Aucune installation, aucun build.

## Contenu du dossier

- `index.html` — le site complet (c'est la page qui s'affiche).
- `.nojekyll` — indique à GitHub Pages de servir les fichiers tels quels (ne rien traiter).
- `README.md` — ce fichier (facultatif, non affiché aux visiteurs).

## Publier sur GitHub Pages (méthode simple, via le site web)

1. Va sur https://github.com et connecte-toi (crée un compte si besoin).
2. Clique sur **New** (nouveau dépôt / repository).
   - **Repository name** : par exemple `betther` (ou `betther-site`).
   - Coche **Public**.
   - Coche **Add a README** est inutile (on a déjà le nôtre) — laisse décoché.
   - Clique **Create repository**.
3. Sur la page du dépôt, clique **Add file ▸ Upload files**.
4. **Glisse-dépose** les fichiers de ce dossier (`index.html`, `.nojekyll` et, si tu veux, `README.md`).
   - ⚠️ Le `.nojekyll` commence par un point : s'il n'apparaît pas dans ton explorateur de fichiers, active « afficher les fichiers cachés », ou ce n'est pas grave — le site marche aussi sans lui.
5. En bas, clique **Commit changes**.
6. Va dans **Settings** (onglet du dépôt) ▸ menu de gauche **Pages**.
7. Sous **Build and deployment ▸ Source**, choisis **Deploy from a branch**.
8. **Branch** : sélectionne `main` et le dossier `/ (root)`, puis **Save**.
9. Attends 1 à 2 minutes, recharge la page **Pages** : l'adresse de ton site apparaît en haut, du type :
   `https://<ton-nom-utilisateur>.github.io/betther/`

C'est en ligne. À chaque fois que tu remplaces `index.html` (Add file ▸ Upload files, même nom), le site se met à jour tout seul en 1–2 min.

## Adresse personnalisée (nom de domaine)

Si tu achètes un domaine (ex. `betther.fr`), tu peux le brancher dans **Settings ▸ Pages ▸ Custom domain**. Dis-le-moi et je te guide.

## Bon à savoir

- Le fichier fait ~12 Mo (à cause de la vidéo embarquée) : c'est accepté par GitHub Pages (limite 100 Mo/fichier), mais le premier chargement peut être un peu long sur mobile. Si tu veux l'alléger, je peux remettre une image à la place de la vidéo.
- Le site force le thème sombre et fonctionne sans connexion à un serveur : il n'y a rien d'autre à configurer.
