# Rééducation oro-maxillo-faciale

Application d'exercices de rééducation OMF, destinée aux patients suivis en cabinet.
Elle tient dans une seule page web, sans compte ni installation.

## Ce qu'elle contient

26 exercices répartis en sept zones — mandibule, lèvres, joues, langue, ATM,
respiration, voile et pharynx — chacun présenté en deux versions :

- **adulte**, avec les consignes cliniques et les notes du praticien ;
- **enfant**, en langage simple, avec illustrations et consignes de sécurité réécrites.

Les quatre exercices issus de protocoles spécifiquement adultes (apnée obstructive
du sommeil, bruxisme) n'apparaissent pas dans la version enfant.

Chaque exercice dispose d'un minuteur de maintien et d'un compteur de répétitions.
La progression de la séance est conservée d'un jour sur l'autre.

## Confidentialité

**Aucune donnée ne quitte l'appareil.** Le suivi de séance est enregistré dans le
navigateur du patient et n'est transmis à personne. La page ne charge aucune
ressource externe : elle s'affiche à l'identique sans connexion.

## Fonctionnement

Le contenu des exercices est écrit directement dans le HTML ; le script se contente
d'ajouter l'interactivité par-dessus. La page reste donc lisible partout, y compris
là où les scripts ne s'exécutent pas — l'aperçu rapide d'un fichier sur iPhone, par
exemple. Dans ce cas, les minuteurs et compteurs sont masqués plutôt qu'affichés
inertes, et un encadré explique ce qui manque.

## Contenu clinique

Les exercices proviennent des notes de rééducation de la praticienne, complétés par
des exercices issus de la littérature — notamment le protocole oropharyngé de
Guimarães et al. (2009), évalué chez l'adulte présentant un SAOS modéré.

L'ensemble du contenu a été relu et validé par Pauline, kinésithérapeute, le
26 août 2026.

## Avertissement

Ces exercices sont donnés à titre indicatif et ne remplacent pas un bilan ni un
suivi individualisé. Ils doivent être pratiqués selon les instructions du
kinésithérapeute. En cas de douleur, arrêter immédiatement et consulter.
