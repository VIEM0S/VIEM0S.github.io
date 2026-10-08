# Portfolio — Mohamed Solomani Doumbia

Site personnel statique (HTML/CSS/JS, sans dépendance), publié avec GitHub Pages sur https://viem0s.github.io/.

- `index.html` : la page (styles et script intégrés)
- `404.html` : page d'erreur
- `projets/kafora.html` : étude de cas détaillée de Kafora
- `assets/` : photo (JPEG + WebP), icônes, image d'aperçu pour les partages (`og-image.jpg`) et CV en PDF
- `robots.txt`, `sitemap.xml` : référencement

Pour ajouter une capture de projet : déposer l'image dans `assets/` puis remplacer « Capture à venir »
dans la carte du projet par `<img src="assets/nom.webp" alt="…" loading="lazy" />`.

## CV

Le PDF `assets/CV_Mohamed_Solomani_Doumbia.pdf` est généré à partir de `cv/cv.html` (police Carlito incluse dans `cv/fonts/`, QR code dans `cv/qr.svg`).
Pour le modifier : éditer `cv/cv.html`, l'ouvrir dans Chrome, Imprimer → Enregistrer au format PDF, A4, marges « Aucune », « Graphiques d'arrière-plan » coché, puis vérifier qu'il tient sur une page.
