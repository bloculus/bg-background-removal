# bg-background-removal

Outil de suppression de fond d'image, utilisable directement dans le navigateur sans installation.

**URL** : https://bloculus.github.io/bg-background-removal/

## Fonctionnement

- L'IA tourne entièrement côté client (WebAssembly) — aucune image n'est envoyée sur un serveur
- Glisser-déposer ou sélection d'une image (PNG, JPG, WebP)
- Téléchargement du résultat en PNG avec fond transparent

## Modifier et redéployer

```bash
# Cloner le repo
git clone https://github.com/bloculus/bg-background-removal.git

# Modifier index.html, puis :
git add index.html
git commit -m "description de la modification"
git push
```

GitHub Pages met à jour l'URL automatiquement en 1-2 minutes.

## Librairie utilisée

[@imgly/background-removal](https://github.com/imgly/background-removal-js) — licence AGPL-3.0
