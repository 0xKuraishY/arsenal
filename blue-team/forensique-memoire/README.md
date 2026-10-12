# Forensique de la mémoire vive : analyser une machine en vie

**Domaine :** Blue team · **Niveau :** expert

Lire la RAM comme la scène de crime où l'attaque se déroule vraiment. Ce que la
mémoire révèle et qu'aucune autre source ne donne : l'état réel d'une machine à
l'instant *t*, y compris ce qui n'a jamais touché le disque. Pour l'analyste SOC
confirmé. Développements orientés Windows x86-64, avec renvois Linux ; commandes
et plugins suivant **Volatility 3** (série v2.28).

## Au programme

**Le terrain — comment l'OS organise la mémoire**
- Pourquoi la mémoire vive, et pourquoi maintenant.
- Adressage virtuel, pages et traduction d'adresses.
- Le processus vu par le noyau : EPROCESS, PEB, VAD, threads.
- Le royaume noyau : pools, objets et surface DKOM.

**Acquérir proprement et lire la RAM**
- Acquisition : ordre de volatilité, outils, intégrité, pièges.
- Ce que lit réellement Volatility 3 : couches, symboles, automagic.

**La chasse — détecter en mémoire**
- Injection de code, process hollowing, processus et modules cachés.
- Connexions et artefacts réseau volatils, hooks aveuglant l'EDR.
- Identifiants et clés en clair.

**Mise en perspective**
- Mémoire vive & analyse de binaire : deux moitiés d'une même enquête.
- Méthode, limites et techniques anti-forensiques ; aide-mémoire des plugins.

> Document pédagogique défensif. Toute acquisition mémoire doit être menée dans
> un cadre légal, sur des systèmes dont vous avez la responsabilité ou
> l'autorisation explicite.

📄 [`forensique-memoire-vive.pdf`](forensique-memoire-vive.pdf) · 32 pages
