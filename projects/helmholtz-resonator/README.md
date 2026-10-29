# Résonateur de Helmholtz — acoustique expérimentale

**Statut :** documentation en cours  
**Contexte :** TIPE de CPGE MPI  
**Thèmes :** acoustique, résonance, oscillateur harmonique, traitement du signal

## Présentation

Ce projet étudie la résonance d'un résonateur de Helmholtz : une cavité reliée à l'extérieur par une ouverture étroite. L'air du col peut être assimilé à une masse oscillante, tandis que la compressibilité de l'air de la cavité joue le rôle de force de rappel.

L'objectif est de comparer des mesures expérimentales de résonance à un modèle physique simplifié.

## Dispositif expérimental

- Générateur basse fréquence (GBF) et haut-parleur
- Microphone et oscilloscope
- Résonateurs de volumes de cavité et de géométries de col variés
- Balayages en fréquence et enregistrements de signaux temporels

## Méthode

1. Exciter le résonateur sur une plage de fréquences.
2. Enregistrer la réponse mesurée.
3. Tracer la réponse en fonction de la fréquence et repérer le pic de résonance.
4. Analyser les signaux temporels et, si pertinent, leur spectre en fréquence.
5. Comparer les mesures au modèle et discuter des incertitudes et des hypothèses.

## Modèle

Un modèle simplifié du résonateur de Helmholtz donne la fréquence de résonance approchée. Celui-ci suppose une cavité compacte, de petites oscillations et une approximation adéquate de l'air du col par une masse ponctuelle. Les mesures réelles peuvent différer à cause des pertes, de la géométrie, du couplage avec le haut-parleur et le microphone, et de l'incertitude sur la longueur effective.

## Outils d'analyse

- Python
- NumPy
- Matplotlib
- SciPy

## Structure du dépôt

```text
helmholtz-resonator/
├── data/          # Ajouter ici les fichiers de mesures (CSV)
├── notebooks/     # Analyse exploratoire (optionnel)
├── src/           # Scripts d'analyse réutilisables
├── figures/       # Graphiques exportés
└── README.md
```
