# Filesystem Agent Bonus

This folder demonstrates how to use an agent that can read and reason over files in the `sample_files` directory.

## Prérequis
- Python 3.10+
- Node.js et npx installés (`npm install -g npx` si besoin)
- Dépendances Python du projet installées

## Démarrage rapide

1. **Lancer le serveur MCP Filesystem**

Dans un terminal, exécutez :

```bash
npx -y "@modelcontextprotocol/server-filesystem" bonus/sample_files
```

Laissez ce serveur tourner dans ce terminal.

2. **Lancer l'agent en mode interactif**

Dans un autre terminal, exécutez :

```bash
python bonus/main.py
```

Vous pouvez alors discuter avec l'agent via la ligne de commande. Tapez `/quit` pour quitter.

## Exemple de fichiers
- `favorite_books.txt`
- `favorite_songs.txt`
- `favorite_cities.txt`
- `poem.txt`

## Notes
- Le serveur MCP doit être lancé avant d'utiliser l'agent.

Pour plus d'informations sur le serveur MCP Filesystem, consultez :
https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem
