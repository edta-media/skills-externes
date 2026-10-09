# Errata : erreurs connues dans les skills de ce dépôt

Les copies de ce dépôt restent figées telles que publiées par leurs auteurs. Les erreurs constatées sont listées ici : **lire cette page avant d'appliquer une consigne des skills cités.**

## ffmpeg-synth (multimedia/media-os/skills/ffmpeg-synth)

- **Erreur** : le skill affirme que le générateur `sine` de ffmpeg sort à pleine échelle (0 dBFS) et conseille d'ajouter `volume=-20dB` pour obtenir une tonalité d'alignement.
- **Constaté** : le générateur `sine` sort à **environ −18 dBFS** en crête (amplitude 1/8 par défaut). Mesuré le 09/10/2026 avec `volumedetect` sur le projet BAREL Live : −18,1 dBFS en crête.
- **Conséquence** : appliquer la recette donne une tonalité vers −38 dBFS, 20 dB trop bas.
- **À faire** : mesurer le niveau produit (`volumedetect`) et régler l'amplitude en conséquence ; −18 dBFS correspond au niveau d'alignement européen EBU R68, −20 dBFS au niveau SMPTE (repères à confirmer dans les textes).

## ndi-docs (multimedia/media-os/.claude/skills/ndi-docs)

- **Erreur** : le skill affirme que le kit NDI standard n'est gratuit que pour un usage non commercial, et que la redistribution commerciale demande le kit NDI Advanced.
- **Selon la documentation officielle NDI** (consultée le 09/10/2026) : la bibliothèque du kit NDI standard peut être utilisée dans des produits gratuits **ou commerciaux** sans redevance, à condition d'afficher un lien vers ndi.video près de chaque endroit où NDI est utilisé ou choisi, sur le site et dans la documentation du produit. Le kit NDI Advanced est une offre à redevance, avec fonctions avancées, certification et support.
- **Ce qui fait foi** : le contrat de licence livré à la racine du kit NDI. À lire avant toute commercialisation.
- Sources : https://docs.ndi.video/docs/sdk/licensing ; https://docs.ndi.video/all/faq/sdk/what-are-the-differences-between-the-ndi-sdk-and-the-ndi-advanced-sdk
