Site vonro.ch — guide rapide
1. Mise en ligne sur GitHub Pages
Crée un repo GitHub public (ex. vonro-site).
Ajoute les 4 fichiers (index.html, image.logo1.png, CNAME, README.md) à la racine du repo — tout au même niveau, pas de sous-dossier.
Repo → Settings → Pages → Source : branche main, dossier / (root).
Chez le registrar du domaine vonro.ch, ajoute 4 enregistrements A :
185.199.108.153 · 185.199.109.153 · 185.199.110.153 · 185.199.111.153
Propagation DNS : jusqu'à 24h. Ensuite le site est visible sur https://vonro.ch
Édition sur mobile : ouvre le repo sur github.com puis ajoute un . à la fin de l'URL (ou l'app GitHub) pour un éditeur de code complet dans le navigateur.
2. À faire avant de montrer à l'oncle
[ ] Vérifier que le logo (image.logo1.png) est le bon (V.O.N.R.O échafaudage)
[ ] Remplacer le slider avant/après (section Réalisations) par 2 vraies photos
[ ] Ajouter 2-3 photos de chantiers récents si possible
[ ] Confirmer les chiffres (40 ans, 40+ collaborateurs) si ça a changé
3. Pour un formulaire de contact "silencieux" (optionnel)
Le formulaire envoie actuellement un e-mail via mailto: (ouvre le client mail). Pour un envoi direct sans ouvrir de fenêtre, crée un compte gratuit sur formspree.io ou web3forms.com et remplace l'action du <form id="devis-form"> par celle fournie par le service.