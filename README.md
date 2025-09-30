# Feed-n-Tech

Un site communautaire destiné aux passionnés et professionnels de l'infrastructure basé sur les retours d'utilisations.
Le but est de partager des retours d'expérience et guides techniques sous forme de contributions Git. 
Les contributions se font uniquement via **Git** (pull requests), et le site est mis à jour automatiquement grâce à la CI/CD.  

---

## Objectifs

- Favoriser le partage asynchrone de connaissances
- Proposer un contenu validé par la communauté
- Utiliser Git comme moteur de collaboration

---

## Exemples de contributions
- Un article sur "Utilisation du terminal CLI"
- Un guide "Mettre en place un service"
- Retour d'expérience "Facilité de création d'utilisateur Ubuntu"

## Format JSON à respecter
```
{
  "title": "Installer Debian sur un serveur",
  "author": "Rémi L.",
  "date": "2025-09-30",
  "tags": ["linux", "installation", "debian"],
  "content": "Mon retour d’expérience sur l’installation de Debian 12 sur un serveur maison..."
}
```

---

## Comment contribuer ?

### 1. Forker le projet
Créez une copie du dépôt sur votre compte GitHub.

### 2. Cloner votre fork
```
bash
git clone https://github.com/votre-compte/feed-n-tech.git
cd feed-n-tech
```

### 3. Créer une branche
`git checkout -b ajout-<nom_de_votre_article>`

### 4. Ajouter votre contribution
modifier le fichier `articles.json` et ajoutez une nouvelle entrée à la fin de la liste, exemple :
```
{
  "date": "2025-10-01",
  "author": "Votre Nom",
  "article_title": "Titre de l’article que vous commentez",
  "opinion": "Votre avis ou commentaire sur l’article, en quelques phrases.",
  "tags": ["tech", "avis", "opensource"]
}
```


---

## Crédits
- Rémi L.
- Sasha CL.
- Edouard D.
