# permis-course-marketplace

Marketplace for the **Permis Côtier de Plaisance** AI tutor plugin.

---

## Option A — Utiliser dans Cowork (recommandé)

Pas besoin de cloner quoi que ce soit. Ouvre Cowork et tape :

```
/plugin marketplace add WilliamMasquelier/permis-course-marketplace
/plugin install permis-course
```

Puis installe les dépendances Python (une seule fois) :

```bash
cd ~/.claude/plugins/cache/permis-course && bash install.sh
```

C'est tout. Lance `/permis-tutor` pour commencer.

---

## Option B — Cloner le repo localement

Pour travailler directement depuis le repo (auteur ou développeur) :

```bash
git clone https://github.com/WilliamMasquelier/permis-course.git
cd permis-course
bash install.sh
```

Le script `install.sh` installe automatiquement `uv` et Python 3.13 si absents, crée le venv, et vérifie que tout fonctionne.

Ouvre ensuite Claude Code dans le dossier `permis-course/`.

---

## Commandes disponibles

| Commande | Ce que ça fait |
|---------|-------------|
| `/permis-tutor` | Session Socratique — révision des flashcards, leçon interactive en français |
| `/permis-scenario` | Scénario de navigation côtière avec debriefing COLREGs |
| `/permis-exam` | Examen blanc complet — 40 questions (seuil : 35/40) |
| `/permis-render` | Re-générer les fichiers HTML et vérification visuelle |
| `/permis-setup` | Vérifier l'installation |
| `/permis-author` | Mode auteur — modifier leçons et notes wiki |

## Mettre à jour

```
/plugin update permis-course
```

Ou dans le repo local : `git pull`

## Source

Plugin : [WilliamMasquelier/permis-course](https://github.com/WilliamMasquelier/permis-course)
