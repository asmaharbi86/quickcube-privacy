# QuickCube — site de politique de confidentialité

Mini-site statique hébergé sur **GitHub Pages** pour satisfaire l'exigence du Play Store
concernant la permission `CAMERA` de l'application QuickCube (`com.quickcube.app`).

URL finale : `https://<ton-user-github>.github.io/quickcube-privacy/`

## Publier (3 commandes)

```bash
cd /Users/issambenamara/dev/quickcube-privacy-site
gh auth login   # une fois — choisir GitHub.com, HTTPS, navigateur
gh repo create quickcube-privacy --public --source=. --remote=origin --push
```

Puis dans l'interface GitHub : **Settings → Pages → Source = `main` / root → Save**.

Après 30 à 60 s, la page est disponible sur
`https://<ton-user-github>.github.io/quickcube-privacy/`.
