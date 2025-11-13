# My V0 Project

Voici mon rendu de test technique.
J'ai choisi de développer le module de quiz pour plusieurs raisons :
- Il est plus facile d'apprendre quelque chose en jouant, et le quiz est très facile à adapter en jeu avec un système de score.
- Il est plus facile d'apprendre à plusieurs ; ce module pourrait faire l'objet d'un développement côté serveur afin d'y jouer en multijoueur.

Mes axes d'amélioration :
- Mettre en place un mode multijoueur, comme évoqué précédemment.
- Améliorer le système de score (par exemple, en prenant en compte le temps de réponse).
- Dans le cas d'un quiz multijoueur, réfléchir à une manière de gérer les scores pour qu'aucun enfant ne subisse de moqueries de la part de ses camarades, que ce soit parce qu'il a toujours le score le plus élevé ou, au contraire, le plus bas.

Vous pourrez tester mon module dans la section "Mes contenus", puis dans un contenu de type quiz comme celui du mercredi 29 octobre, ou directement à l'adresse suivante : [http://test_technique/fiches/revision](http://codeelite74.com:3000/fiches/revision?type=quiz)

## 🚀 Démarrage du projet

### Prérequis

- Node.js 18+ (recommandé)
- npm

### Installation des dépendances

Si les dépendances ne sont pas encore installées, exécutez la commande suivante à la racine du projet :

```bash
npm install
```

**En cas de problèmes d'installation :**

Si vous rencontrez des erreurs lors de l'installation, essayez les solutions suivantes :

1. **Nettoyer le cache npm :**
```bash
npm cache clean --force
```

2. **Supprimer node_modules et package-lock.json puis réinstaller :**
```bash
rm -rf node_modules package-lock.json
npm install
```

3. **Utiliser l'option --legacy-peer-deps si nécessaire :**
```bash
npm install --legacy-peer-deps
```

### Démarrage en mode développement

Pour lancer le serveur de développement :

```bash
npm run dev
```

Le projet sera accessible à l'adresse : [http://test_technique](http://codeelite74.com:3000)

## 📋 Autres commandes disponibles

```bash
npm run build # Construit l'application pour la production
npm run start # Démarre le serveur de production (après build)
npm run lint # Exécute ESLint pour vérifier le code
```
