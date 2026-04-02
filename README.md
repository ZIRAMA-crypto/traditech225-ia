# TRADITECH 225 — Module IA

Application d'apprentissage du Dioula pour les jeunes ivoiriens.

## Équipe IA
- [Zirama] — Reconnaissance vocale & Chatbot
- [Dorcas] — Traduction

## Modèles utilisés
| Fonctionnalité | Modèle |
|---|---|
| Traduction FR ↔ Dioula | facebook/nllb-200-distilled-600M |
| Reconnaissance vocale | openai/whisper-small |
| Chatbot conversationnel | google/flan-t5-base |

## Structure du projet
- `data/` → datasets bruts et traités
- `traduction/` → notebook NLLB
- `reconnaissance_vocale/` → notebook Whisper
- `chatbot/` → notebook Flan-T5

## Organisation des données
- `raw/` → données brutes collectées
- `processed/` → données nettoyées et formatées
- `splits/` → train / validation / test
