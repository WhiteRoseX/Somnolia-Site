# Somnolia — Support et confidentialité

Site statique en français, adapté aux mobiles et aux ordinateurs. Aucune installation, compilation ou dépendance JavaScript nécessaire.

## Prévisualiser

Depuis ce dossier :

```sh
python3 -m http.server 4173 --bind 127.0.0.1 --directory dist
```

Ouvrir http://127.0.0.1:4173/support/ ou http://127.0.0.1:4173/privacy/.
Les adresses `/support` et `/privacy` sont redirigées vers leurs répertoires par le serveur. La racine ouvre le support.

## Mettre en ligne

Publier le contenu du dossier `dist` sur un hébergement statique qui sert les fichiers `index.html` des répertoires. Aucun service externe n’est nécessaire. Le site n’a pas été publié automatiquement.

## Modifier

- `dist/support/index.html` : questions fréquentes et contact.
- `dist/privacy/index.html` : politique de confidentialité.
- `dist/styles.css` : apparence commune et adaptation mobile.
- `dist/assets/` : logo Somnolia et police Manrope locale (licence incluse).

La politique de confidentialité de l’application et les coordonnées sont reprises du contenu existant dans `SettingsView.swift` à la date du 11 octobre 2026 ; une section distincte décrit le site. Cette reprise ne constitue pas un audit juridique. Avant publication, vérifier que ce texte correspond toujours aux pratiques effectives et compléter, si nécessaire, les informations propres à l’hébergeur choisi.

Les assets ont été copiés. Aucun fichier du projet SleepTrack n’est nécessaire au fonctionnement du site, et aucun fichier de ce projet n’a été modifié.
