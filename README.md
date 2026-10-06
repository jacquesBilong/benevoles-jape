# Les Bénévoles de la JAPE

Site de la chorale **Les Bénévoles de la JAPE** — EPC Paroisse La Grâce, Bruxelles.

- **Chants** : paroles, tonalité, tempo, solistes, note de départ par voix (Soprano, Alto, Ténor, Basse), accord et gamme.
- **Programmes** : déroulé des cultes, baptêmes, mariages, concerts et événements d'église, avec mode prestation plein écran.
- **Documents** : Guide du responsable de la JAPE (pages transcrites, recherche, référence par page) et Règlement intérieur (incomplet).
- **Choristes** : membres, voix et solos.

## Fonctionnement

Site statique, sans serveur : `index.html` lit le contenu dans `data.json` et les photos dans `images/`.
Cette version publique est en **lecture seule**. Le répertoire se modifie dans l'application de la chorale sur Claude, puis on met à jour `data.json` et `images/` ici.

## Publication

GitHub Pages : *Settings → Pages → Source : Deploy from a branch → `main` / root*.
