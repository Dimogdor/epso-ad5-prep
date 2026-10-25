# Préparation · EPSO/AD/427/26

App d'entraînement pour le concours européen EPSO/AD/427/26 (Graduate Administrators, grade AD5).
Fichier HTML unique, JavaScript vanilla, aucune dépendance, aucun build, aucun compte.

## Modules

- **Verbal** · 181 textes au format réel, tous au niveau de l'examen : un passage de 150 à 185 mots, quatre affirmations A/B/C/D, une seule pleinement démontrée par le texte. La correction donne le verdict de chaque affirmation (vrai, faux, ne peut pas dire) et sa raison. Les sessions tirent en priorité des textes pas encore vus. Chronomètre global de session. La moitié des textes sont hors sujet européen, comme au concours. Chaque texte d'entraînement compte au moins une affirmation « ne peut pas dire », et un tiers environ en comptent deux, comme dans les recueils récents. La méthode détaille les combinaisons de réponses et les glissements de sens à repérer.
- **Numérique + abstrait** · cinq options par question. Session numérique niveau examen : trente-deux familles de séries où un jeu de données porte cinq questions possibles de quatre à six opérations, dont trois sont tirées à chaque fois. Les formats couvrent les tableaux, les graphiques en barres ou en courbes, les camemberts imbriqués, les graphiques distance-temps, les horaires de train et les barres sans valeurs à estimer. Les calculs portent sur les unités, les cellules manquantes, les tendances, le décalage horaire, les taux de change via l'euro, l'inflation, le seuil de rentabilité, les barèmes par tranches, l'optimisation de fret, les temps de passage, les ratios immobiliers, l'identité du PIB, les unités d'énergie et les intérêts composés. Certaines questions proposent « Impossible à déterminer avec ces données », juste quand les données ne suffisent vraiment pas. Chaque mauvaise option correspond à une erreur typique. Session abstraite niveau examen : dix-neuf familles de séries de cinq cadres à éléments multiples (deux ou trois règles indépendantes, règles conditionnelles, alternances, pointeur, indicateur décalé, rebond, serpentin, relation de comptage, éléments parasites à ignorer), avec des variantes de dessin. D'une session à l'autre, une famille ne revient qu'une fois toutes les autres passées. S'y ajoutent des items « même ensemble » à deux règles, avec la règle enfreinte par chaque option fausse. Les anciennes questions courtes restent disponibles en échauffement. Une méthode détaillée accompagne les deux tests : démarche en sept temps, erreurs attendues par les options, raccourcis, cas où cocher « Impossible à déterminer », fabrication des séries abstraites et règles qui reviennent.
- **Examen blanc en mode TAO** · la partie 1 complète (verbal 35 min, numérique 20 min, abstrait 10 min) ou chaque test seul, dans l'interface décrite par les instructions TAO du concours : minuteur par partie, barre de navigation, signets et vue d'ensemble, réponses modifiables jusqu'à la soumission, calculatrice à l'écran (point décimal, virgule refusée, historique), bloc-notes texte et dessin, surligneur, élimination des réponses, zoom, avertissements avant soumission, soumission automatique à la fin du temps. Correction détaillée à la fin seulement.
- **Connaissances UE** · cours en 9 sections et 382 questions, jouables en anglais ou en français, avec une fiche sur ce que le test interroge.
- **Compétences numériques** · cadre DigComp et 207 questions, jouables en anglais ou en français, avec le profil des questions posées aux administrateurs.
- **EUFTE** · six consignes au format réel, avec consigne et document source en anglais ou en français, chacune avec une correction visant le haut de la grille et une explication critère par critère sur les cinq « anchors » publiés par EPSO. La méthode explique comment préparer la documentation avant l'épreuve et rédiger pour une lecture rapide.
- **Cours** · 31 sections de référence, 169 fiches thématiques et un glossaire repliable de 59 sigles développés puis expliqués. Chaque section est écoutable sur place.
- **Le concours** · modalités, calendrier, choix des deux langues, taux de réussite, dix règles stratégiques et plan de préparation en deux parties. Une partie « Après la liste de réserve » prépare les entretiens de recrutement : les huit compétences générales, la méthode STAR, la motivation, des questions types et l'entretien à distance. Huit zones « Mes exemples STAR » gardent tes brouillons sur l'appareil.
- **Paramètres** · thème, réglages de lecture audio, file d'attente, diagnostic vocal, réinitialisation.

Les tests 3 à 5 se passent en Langue 2 : un sélecteur « English / Français » sur chacun de ces onglets bascule les questions, les explications et les sujets EUFTE. L'anglais est proposé par défaut, et le choix est mémorisé.

Dans les trois moteurs de session, l'ordre des options est permuté à l'affichage : la bonne réponse ne reste jamais à la même place. En numérique, « Aucune de ces réponses » et « Impossible à déterminer avec ces données » restent épinglées en dernière position, comme au concours.

## Sources

Les méthodes ajoutées en octobre 2026 sont des synthèses rédigées pour l'app à partir de *The Ultimate EU Test Book, Administrators* (A. Baneth, 2025). Chaque section concernée le signale. Aucun exercice du livre n'est reproduit : les textes, séries et questions de l'app sont originaux. Les faits datés du livre ont été mis à jour (720 députés, 21 pays dans la zone euro, Haute représentante Kaja Kallas).

## Lecture audio

Le cours et l'ensemble des fiches forment 209 chapitres écoutables dans n'importe quel ordre, chacun retenant la phrase exacte où la lecture s'est arrêtée. Pendant l'écoute, **la phrase lue est surlignée dans le texte du cours** et un clic sur une phrase y déplace la lecture.

La synthèse est celle du système (API `speechSynthesis`) : aucun texte n'est envoyé à un service externe, et tout fonctionne hors ligne une fois la voix installée. La qualité dépend entièrement de la voix : les voix neuronales sont remontées en tête du sélecteur. La lecture continue écran verrouillé, avec les commandes sur l'écran de verrouillage.

Un diagnostic intégré teste la voix et renvoie vers l'installation d'un moteur vocal quand l'appareil n'en a pas. Si une voix est acceptée sans rien produire, l'app bascule seule sur la suivante.

## Utilisation

Ouvrir `epso_ad5_prep.html` dans un navigateur. La progression est enregistrée localement, sans compte ni serveur. Thème clair, sombre ou automatique.

Si le dépôt est publié via GitHub Pages, l'app est directement accessible à l'URL de la Page.
