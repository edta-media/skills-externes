# Skills externes

Copies figées de skills publiés par d'autres auteurs sous licence libre (MIT ou Apache-2.0). Ces copies ne suivent pas les modifications des dépôts d'origine : une mise à jour n'entre ici qu'après vérification.

Téléchargées le 8 octobre 2026. Chaque dossier garde le nom de son auteur et le texte de sa licence. Ce dépôt ne modifie aucun de ces skills.

## Multimédia

| Dossier | Origine | Version d'origine | Licence | Contenu |
|---|---|---|---|---|
| `multimedia/media-os` | github.com/damionrashford/media-os | commit 5014c1e8b23f (17/05/2026) | MIT (`LICENSE` du dossier) | 128 skills : broadcast, production en direct, FFmpeg, OBS, NDI, caméras PTZ, DeckLink, DMX, diffusion. |
| `multimedia/audiovisuel-5-skills/ffmpeg` | github.com/digitalsamba/claude-code-video-toolkit, `.claude/skills/ffmpeg` | branche main du 08/10/2026 (commit 2c99460a5d0c) | MIT | Conversion, compression, extraction audio avec FFmpeg. |
| `multimedia/audiovisuel-5-skills/talking-head-recut`, `media-use` | github.com/heygen-com/hyperframes, `skills/` | branche main du 08/10/2026 | Apache-2.0 | Habillage d'interviews ; boîte à outils média HyperFrames. |
| `multimedia/audiovisuel-5-skills/voice-isolator`, `speech-to-text` | github.com/elevenlabs/skills | branche main du 08/10/2026 (commit 1d08a4a250cf) | MIT | Isolation de la voix, transcription (clé ElevenLabs requise). |

Les licences des cinq skills audiovisuels sont dans `multimedia/audiovisuel-5-skills/LICENCES/`.

### Ajoutés le 09/10/2026

| Dossier | Origine | Version d'origine | Licence | Contenu |
|---|---|---|---|---|
| `multimedia/nvidia-deepstream` | github.com/nvidia/skills (`skills/deepstream-*`) | commit dfdd0805a7a2 (08/10/2026) | Apache-2.0 (code), CC-BY-4.0 (textes) | 3 skills officiels NVIDIA : construire des pipelines GStreamer DeepStream (`deepstream-generate-pipeline`), développer avec le SDK (`deepstream-dev`), mesurer les performances avec Nsight (`deepstream-profile-pipeline`). |
| `multimedia/ograf-graphics` | github.com/heretorecord/ograf-graphics-skill | commit 893b98dbec76 (15/06/2026) | MIT | Habillage antenne (synthés, bandeaux, horloges, scores) conforme à la norme EBU OGraf v1. |
| `multimedia/cli-anything-obs-studio` | github.com/hkuds/cli-anything (`skills/cli-anything-obs-studio`) | commit 34f519533bc1 (22/09/2026) | Apache-2.0 | Édition des collections de scènes OBS en ligne de commande (outil Python à installer séparément). |
| `multimedia/davinci-resolve` | github.com/terminalskills/skills (`skills/davinci-resolve`) | commit a021875c0f1b (03/10/2026) | Apache-2.0 | Automatisation de DaVinci Resolve par son API Python ou Lua. |
| `multimedia/moq` | github.com/moq-dev/moq (`skills/moq`) | commit 18a0ef5a3e61 (09/10/2026) | Apache-2.0 ou MIT | Media over QUIC : diffusion en direct à très faible latence ; renvoie vers la documentation en ligne doc.moq.dev. |
| `multimedia/hyperframes` | github.com/heygen-com/hyperframes (`skills/`) | commit 1de8b5ae3360 (09/10/2026), CLI npm `hyperframes@0.8.143` | Apache-2.0 | 21 skills HyperFrames : vidéo en HTML rendue en MP4. `product-launch-video` transforme un site en pub vidéo (testé le 09/10/2026 sur edata-media.com, résultat validé par Abass). Garder le dossier entier : les skills se renvoient les uns aux autres. |

Les licences de chaque source sont dans le sous-dossier `LICENCES/` de son dossier. Erreurs connues dans ces skills : voir `ERRATA.md`.

## Autres corps de métier

| Dossier | Origine | Version d'origine | Licence | Contenu |
|---|---|---|---|---|
| `autres-corps-de-metier/ddc-construction` | github.com/datadrivenconstruction/ddc_skills_for_ai_agents_in_construction | commit ce45bbfbdd63 (22/08/2026) | MIT (`LICENSE` du dossier) | 238 skills : BIM, chiffrage et métrés, planning, suivi de chantier, qualité, sécurité, réception. 32 livres en PDF. |

## Règles

- Aucun script de ces dossiers n'a été exécuté ni audité. Lire un skill avant de s'en servir.
- Mise à jour : télécharger la nouvelle version d'origine, comparer, puis remplacer le dossier ; noter le nouveau commit dans ce tableau.
