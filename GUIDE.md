# Guide de gestion — Képaru Noreyni

## Liens importants

| | Lien |
|---|---|
| Site en ligne | https://lem2003.github.io/keparu-noreyni/ |
| GitHub | https://github.com/LeM2003/keparu-noreyni |
| Instagram | https://www.instagram.com/keparunoreyni |
| TikTok | https://www.tiktok.com/@keparou_noreyni |

---

## Panneau Admin

Accès réservé au gérant du site.

1. Va sur le site : https://lem2003.github.io/keparu-noreyni/
2. Dans la barre d'adresse, ajoute `#admin` à la fin → `.../#admin`
3. Entre le mot de passe
4. Gère les stocks depuis le panneau

**Ce que tu peux faire depuis l'admin :**
- Activer/désactiver le badge "Stock limité" sur chaque produit (T-Shirt Noir, Blanc, Blanc 2)
- Les réglages sont sauvegardés automatiquement dans ton navigateur

---

## Ajouter un nouveau produit

1. Place les 2 photos (face avant + face arrière) dans le dossier `images/`
2. Demande à Claude de l'ajouter avec les noms des fichiers et le prix

---

## Mettre à jour une image

1. Remplace le fichier image dans le dossier `images/` en gardant exactement le même nom
2. Push sur GitHub — le site se met à jour automatiquement

---

## Faire une modification sur le site

Ouvre Claude Code et décris ce que tu veux changer. Claude vérifiera toujours avec toi avant de modifier quoi que ce soit.

---

## Structure des fichiers

```
keparu noreyni/
├── index.html        → tout le site (HTML + CSS + JS)
├── images/           → toutes les photos et le logo
│   ├── Logo .jpeg
│   ├── T-shirt noir — face avant.jpeg
│   ├── T-shirt noir — face arrière.jpeg
│   ├── T-shirt blanc — face avant.jpeg
│   ├── T-shirt blanc — face arrière.jpeg
│   ├── T-shirt Blanc 2 face avant.jpeg
│   └── T-shirt Blanc 2 face arrière.jpeg
├── README.md         → description publique sur GitHub
└── GUIDE.md          → ce fichier (privé, pour le gérant)
```
