# Site de Mathilde — Psychologue clinicienne et Psychothérapeute

Site statique (HTML/CSS/JS, sans dépendance) dans `site/`. Les sources de Mathilde (PDF + logos IA) sont dans `sources/`.

## Lancer en local

```bash
python -m http.server 8080 --directory site
```

Puis ouvrir http://localhost:8080

## Pages

- `index.html` : accueil
- `a-propos.html` : Qui suis-je ? + Mon approche
- `consultations.html` : Pour qui, Quand consulter, Conception de la psychothérapie, Où et comment
- `infos-pratiques.html` : horaires, tarif, facture, autres formats, rendez-vous
- `mentions-legales.html`

## Infos à remplacer (surlignées en violet hachuré sur le site, classe `ph`)

- [ ] Nom de famille de Mathilde (toutes les pages, dans `<title>` aussi)
- [ ] Numéro ADELI / RPPS (pied de page + mentions légales)
- [ ] SIRET et adresse professionnelle (mentions légales)
- [ ] Lien Doctolib (rechercher `https://www.doctolib.fr/`)
- [ ] E-mail ou téléphone de contact (infos pratiques + mentions légales)
- [ ] Photo (a-propos.html, bloc `.photo-ph`)
- [ ] Hébergeur (mentions légales)

## Avant la mise en ligne

- Héberger les polices (Cormorant Garamond, Nunito) en local plutôt que via Google Fonts, pour être conforme au RGPD
- Retirer la classe `.ph` une fois les infos remplacées
