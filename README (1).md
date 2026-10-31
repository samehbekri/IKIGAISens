# IKIGAISens™
### En quête de ma raison d'être · 生き甲斐

**IKIGAISens™** est une application web interactive pour découvrir son ikigai, c'est-à-dire **trouver sa raison d'être : la raison de se lever chaque matin**.

Le parcours guide la personne à travers les quatre cercles de l'ikigai. Il dessine ensuite une rosace personnelle où se révèlent la Passion, la Mission, la Profession, la Vocation et, au cœur, l'Ikigai.

👉 **Ouvrir l'application :** `https://<votre-nom>.github.io/<nom-du-depot>/`

---

## Le parcours

| Rubrique | Contenu |
|---|---|
| **Introduction** | Ce qu'est l'ikigai, avec une animation d'ouverture : les quatre cercles se rejoignent et l'IKIGAI apparaît en relief au centre |
| **Mode d'emploi** | Interactif, avec des icônes cliquables : les 6 étapes, les 8 types de questions avec une zone d'essai, les 13 zones de la rosace |
| **Utilité de l'outil** | Ce qu'il apporte, pour qui, un déroulé en atelier sur 3 séances, ce que l'outil n'est pas |
| **Exemple** | Un parcours fictif entièrement rempli, pour voir le résultat attendu |
| **Cercle 1 · Ce que j'aime** | Activités, ce qui vous anime, ce qui touche votre cœur, vos rêves |
| **Cercle 2 · Ce que je sais faire** | Succès, qualités, les 24 forces de caractère, talents, compétences |
| **Cercle 3 · Ce que je peux apporter** | Modèles inspirants, valeurs, révoltes, message à transmettre |
| **Cercle 4 · Mes activités idéales** | Métiers rêvés, inspirations, bénévolat, croyances limitantes |
| **Ma rosace** | Les mots reliés aux cercles et aux intersections, l'équilibre entre les cercles, un diagnostic, la phrase « Mon ikigai, c'est… » |
| **Suites** | Six actions pour faire vivre ses résultats |
| **À propos** | La conceptrice, avec un lien en bas de chaque page |

Chaque cercle se termine par un **bilan** : la personne remplit un disque de mots, avec des suggestions tirées de ses réponses, et choisit ses émotions.

---

## L'enregistrement des réponses

- **Automatique** : chaque réponse est enregistrée dans le navigateur dès qu'elle est écrite. L'indicateur **✓ Enregistré** en haut de page le confirme.
- **Reprise** : à la réouverture, l'accueil propose **« Reprendre là où j'en étais »**.
- **Document Word** : le bouton **« Enregistrer mes réponses (Word) »**, en bas de page, produit un document lisible avec toutes les réponses, la rosace et le diagnostic. Ce même fichier permet de **reprendre** le parcours sur un autre appareil avec **« Reprendre depuis mon fichier Word »**.

> Les réponses restent sur l'appareil de chaque participant : **aucune donnée n'est envoyée à un serveur**.
> Conseil pour les participants : revenir par le même lien, dans le même navigateur, en dehors de la navigation privée, et enregistrer le fichier Word à la fin de chaque séance.

---

## Mise en ligne sur GitHub Pages

1. Déposez `index.html` (et ce `README.md`) à la racine du dépôt.
2. Allez dans **Settings → Pages**.
3. Dans **Source**, choisissez **Deploy from a branch**, la branche `main` et le dossier `/ (root)`, puis enregistrez.
4. Après une à deux minutes, l'application est disponible à l'adresse `https://<votre-nom>.github.io/<nom-du-depot>/`.

L'application tient dans **un seul fichier** (`index.html`). Il n'y a rien à installer ni à compiler. Elle fonctionne sur ordinateur, tablette et téléphone, en mode clair et en mode sombre.

### Ressources externes
| Ressource | Usage |
|---|---|
| Google Fonts (Gloock, Figtree, Nanum Pen Script) | Typographie |
| [docx 9.6.1](https://www.npmjs.com/package/docx) via jsDelivr | Création du document Word |
| [JSZip 3.10.1](https://stuk.github.io/jszip/) via cdnjs | Lecture du document Word lors de la reprise |

Une connexion internet est nécessaire pour les polices et pour l'enregistrement en Word. Tout le reste fonctionne hors ligne.

---

## Conception et sources

**Conception :** Sameh Bekri. Enseignante à l'Université Virtuelle de Tunis, elle est experte en andragogie, en ingénierie pédagogique et en développement du potentiel humain.
Contact : samehbekri@gmail.com

Inspiré du livre *Ikigai : le secret des Japonais pour une vie longue et heureuse*, Héctor García et Francesc Miralles (2018).

---

## Droits

© 2026 **Sameh Bekri** – IKIGAISens™. Tous droits réservés.
IKIGAISens™ est une marque revendiquée par Sameh Bekri.
La conception, le questionnaire interactif, les analyses et le parcours ne peuvent être reproduits ou diffusés sans l'autorisation de la conceptrice.
