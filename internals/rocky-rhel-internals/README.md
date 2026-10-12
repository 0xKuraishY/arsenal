# Rocky Linux & RHEL : comprendre le système de l'intérieur

**Domaine :** Internals · **Niveau :** expert · **Édition :** EL10 (RHEL 10.2 / Rocky 10.2)

Le fonctionnement interne des systèmes Enterprise Linux expliqué pour qu'une
commande devienne une évidence plutôt qu'un réflexe mémorisé : le *pourquoi* du
*comment*. Édition EL10, avec les repères EL8 et EL9 et un signalement
systématique de ce qui a changé — car les vieux livres (SysV, ifcfg, iptables,
yum) sont en partie périmés. Chaque chapitre porte un **regard analyste SOC** :
traces laissées, abus possibles, angles morts.

## Au programme

- **Le socle** : généalogie de la famille Enterprise Linux, architecture noyau /
  espace utilisateur, arborescence.
- **Démarrage & systemd** : la chaîne de boot maillon par maillon, systemd en chef
  d'orchestre.
- **Processus, mémoire & noyau** : cycle de vie, modules, paramètres, observation.
- **Logiciels** : RPM et sa base de données, résolution et transactions DNF.
- **Stockage** : disques, LVM, XFS, montage.
- **Réseau** : configuration moderne, pare-feu, synchronisation du temps.
- **Identités & contrôle d'accès** : utilisateurs, NSS, PAM, sudo, SELinux (MAC),
  cryptographie système et OpenSSH, audit et journalisation.
- **Conteneurs & diagnostic** : Podman, mode image, outils d'observation.
- **Synthèse** : anatomie complète d'une connexion SSH, de bout en bout.
- **Annexes** : ce que disent les vieux livres vs. aujourd'hui, carte des artefacts
  pour l'analyste, sources vérifiées.

📄 [`rocky-linux-rhel-internals.pdf`](rocky-linux-rhel-internals.pdf) · 56 pages
