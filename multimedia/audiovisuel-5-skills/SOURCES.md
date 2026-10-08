# Skills audiovisuels à vérifier (téléchargés le 08/10/2026)

Rien n'est installé ni rangé dans la bibliothèque. Aucun script n'a été exécuté.

| Skill | Source (GitHub) | Installations skills.sh | Étoiles | Fichiers | À savoir |
|---|---|---|---|---|---|
| ffmpeg | digitalsamba/claude-code-video-toolkit, `.claude/skills/ffmpeg` | 9 985 | 2 176 | 2 | Texte seulement. Licence MIT. |
| talking-head-recut | heygen-com/hyperframes, `skills/talking-head-recut` | 292 255 | 58 766 | 28 | Fonctionne dans un projet HyperFrames. Contient une copie de GSAP et un fichier de test. Licence Apache-2.0. |
| voice-isolator | elevenlabs/skills, `voice-isolator` | 5 034 | 481 | 2 | Demande une clé ElevenLabs (service payant). Licence MIT. |
| speech-to-text | elevenlabs/skills, `speech-to-text` | 9 698 | 481 | 7 | Demande une clé ElevenLabs (service payant). Licence MIT. |
| media-use | heygen-com/hyperframes, `skills/media-use` | 732 258 | 58 766 | 109 | Le plus lourd : 60 scripts Node et Python, dont `telemetry.mjs` (envoi de statistiques d'usage) et `npx-sync.mjs` (téléchargements par npx). Appelle aussi HeyGen et Gemini (clés requises). Fonctionne dans un projet HyperFrames. |

Pour en garder un : le déplacer dans `Skills\<domaine>\` (le gestionnaire le verra tout de suite) et, pour que Claude s'en serve, le copier dans `C:\Users\asoul\.claude\skills\`.
