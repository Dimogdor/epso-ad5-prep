# Préparation · EPSO/AD/427/26

App d'entraînement pour le concours européen EPSO/AD/427/26 (Graduate Administrators, grade AD5).
Fichier HTML unique, JavaScript vanilla, aucune dépendance, aucun build, aucun compte.

## Modules

- **Verbal** · 141 textes au format réel : un passage, quatre affirmations A/B/C/D, une seule pleinement démontrée par le texte. Chronomètre global de session. La moitié des textes sont hors sujet européen, comme au concours.
- **Numérique + abstrait** · format vérifié sur l'épreuve blanche officielle : cinq options par question. 16 questions écrites, 20 générateurs sur énoncé, 20 générateurs sur tableau de données ; séries abstraites produites par neuf familles de règles paramétrées sur un rendu SVG procédural. Les deux types d'items du concours sont couverts, la suite à compléter et l'ensemble régi par une règle liant deux attributs. Les deux tests sont chronométrés séparément.
- **Connaissances UE** · cours en 9 sections et 354 questions.
- **Compétences numériques** · cadre DigComp et 193 questions.
- **EUFTE** · six consignes au format réel, chacune avec une correction visant le haut de la grille et une explication critère par critère sur les cinq « anchors » publiés par EPSO.
- **Cours** · 30 sections de référence, 169 fiches thématiques et un glossaire repliable de 59 sigles développés puis expliqués. Chaque section est écoutable sur place.
- **Le concours** · modalités, calendrier, choix des deux langues, dix règles stratégiques et plan de préparation en deux parties.
- **Paramètres** · thème, réglages de lecture audio, file d'attente, diagnostic vocal, réinitialisation.

Dans les trois moteurs de session, l'ordre des options est permuté à l'affichage : la bonne réponse ne reste jamais à la même place. En numérique, « Aucune de ces réponses » reste épinglée en dernière position, comme au concours.

## Lecture audio

Le cours et l'ensemble des fiches forment 208 chapitres écoutables dans n'importe quel ordre, chacun retenant la phrase exacte où la lecture s'est arrêtée. Pendant l'écoute, **la phrase lue est surlignée dans le texte du cours** et un clic sur une phrase y déplace la lecture.

La synthèse est celle du système (API `speechSynthesis`) : aucun texte n'est envoyé à un service externe, et tout fonctionne hors ligne une fois la voix installée. La qualité dépend entièrement de la voix : les voix neuronales sont remontées en tête du sélecteur. La lecture continue écran verrouillé, avec les commandes sur l'écran de verrouillage.

Un diagnostic intégré teste la voix et renvoie vers l'installation d'un moteur vocal quand l'appareil n'en a pas. Si une voix est acceptée sans rien produire, l'app bascule seule sur la suivante.

## Utilisation

Ouvrir `epso_ad5_prep.html` dans un navigateur. La progression est enregistrée localement, sans compte ni serveur. Thème clair, sombre ou automatique.

Si le dépôt est publié via GitHub Pages, l'app est directement accessible à l'URL de la Page.
