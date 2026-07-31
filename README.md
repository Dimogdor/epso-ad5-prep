# Dossier de préparation · EPSO/AD/427/26

App d'entraînement pour le concours européen EPSO/AD/427/26 (Graduate Administrators, grade AD5). Fichier HTML unique, JavaScript vanilla, aucune dépendance, aucun build.

## Modules

- **Verbal** · 141 textes au format réel du concours : un passage, quatre affirmations A/B/C/D, une seule pleinement démontrée par le texte. Chronomètre global de session.
- **Numérique + abstrait** · format du concours vérifié sur l'épreuve blanche officielle : cinq options par question ; en numérique la cinquième est « Aucune de ces réponses » dans un peu plus de la moitié des cas, cinq valeurs chiffrées sinon, comme au concours. 16 questions écrites, 20 générateurs sur énoncé et 20 générateurs sur tableau de données ; séries abstraites produites par neuf familles de règles paramétrées sur un rendu SVG procédural, cinq figures candidates étiquetées A à E, les rotations portant un repère qui tourne avec la figure pour rester lisibles. Les deux types d'items du concours sont couverts : la suite à compléter et l'ensemble régi par une règle liant deux attributs, y compris des règles doubles. Les deux tests sont chronométrés séparément.
- **Connaissances UE** · cours en 9 sections et 354 questions.
- **Compétences numériques** · cadre DigComp et 193 questions.
- **EUFTE** · six consignes au format réel : un rôle, un destinataire, un document à produire et un rapport source. Chaque sujet est accompagné d'une correction rédigée pour atteindre le haut de la grille et d'une explication critère par critère, sur les cinq « anchors » publiés par EPSO.
- **Annexe** · 30 sections de référence, dont 9 d'actualité européenne destinées à l'EUFTE, et 169 fiches thématiques condensées.
- **Écoute** · le cours UE et l'annexe entière lus à voix haute, soit 208 chapitres écoutables dans n'importe quel ordre. Chaque chapitre retient la phrase exacte où la lecture s'est arrêtée, indépendamment des autres : rouvrir l'app reprend là où on en était. Vitesse réglable de 0,5× à 2× en cours de lecture, file d'attente, enchaînement automatique, suivi du texte à l'écran, saut à une phrase par un clic, raccourcis clavier. Un bouton d'écoute est aussi posé sur chaque section du cours et de l'annexe, et la barre de lecture survit aux changements d'onglet.
- **Stratégie** · plan de préparation et règles générales.

Dans les trois moteurs de session, l'ordre des options est permuté à l'affichage : la bonne réponse ne reste jamais à la même place d'une session à l'autre. En numérique, « Aucune de ces réponses » reste épinglée en dernière position, comme au concours.

## Utilisation

Ouvrir `epso_ad5_prep.html` dans un navigateur. La progression est enregistrée localement par le navigateur, sans compte ni serveur.

La lecture audio passe par la synthèse vocale du système (API `speechSynthesis`) : aucun texte n'est envoyé sur un service externe et, la voix une fois installée, tout fonctionne hors ligne. La qualité dépend entièrement de la voix choisie — les voix neuronales (« Natural » sous Edge, « Google français » sous Chrome, voix améliorées d'Apple) sont d'un tout autre niveau que les voix système historiques ; elles sont remontées en tête du sélecteur. Sous iOS, la lecture s'interrompt quand l'écran se verrouille, limite du système et non de l'app.

Si le dépôt est publié via GitHub Pages, l'app est directement accessible à l'URL de la Page.
