# Pilotage Notarial

Prototype et dossier de conception du logiciel de gestion et d'automatisation des dossiers
de l'étude notariale Thomas Levy (Paris 16e).

- `index.html` — **prototype fonctionnel v2**, pensé pour Me Thomas Lévy : file « À traiter »
  pré-analysée par l'IA (une lecture, un clic pour approuver), écran Entrées (courriels analysés,
  création/rattachement de dossiers sur approbation, création manuelle en option), dossiers par
  thématique d'expertise et rentabilité €/h, synthèse IA + frise chronologique IA/humain par
  dossier, dossier de démonstration complet (vente en copropriété, 4 anomalies), checklist,
  relances, projet d'acte prérempli, comptabilité, espace LCB-FT, portail client, journal d'audit.
  Application statique autonome (HTML/CSS/JS, aucune dépendance, aucun backend).
- `conception.html` — **dossier de conception** : les 12 livrables du cahier des charges
  (cartographie, modèle de données, workflows BPMN, permissions, écrans, architecture,
  intégrations, automatisations/validations humaines, risques, backlog, plan MVP 6 mois,
  critères d'acceptation).

## Principes non négociables du produit

Le logiciel prépare, l'humain décide : toute rédaction, décision juridique, transmission
officielle, signature, mouvement financier ou clôture reste soumis à une validation humaine
nominative et tracée. Aucune donnée n'est inventée (chaque extraction porte sa source et son
score de confiance). Aucun virement n'est exécuté par l'IA. Les connexions institutionnelles
(Télé@ctes, MICEN…) sont présentées « sous réserve d'agrément ».

**Dossiers, parties et chiffres du prototype sont fictifs.** L'équipe affichée correspond aux
profils publics de l'étude : Me Thomas Lévy (notaire, direction), Me Hélène Rouaud et
Me Julie Azzoulai (notaires salariées), Véronique Michel et Mylène Abensour (notaires
assistantes), Dan Knafo (notaire stagiaire).

## En ligne (Vercel)

- Prototype : https://pilotage-notarial.vercel.app
- Dossier de conception : https://pilotage-notarial-conception.vercel.app

Site statique — aucune donnée réelle, aucun traitement serveur.
