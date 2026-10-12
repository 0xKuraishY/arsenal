# Impacket pour le pentester — atexec

**Domaine :** Red team · **Niveau :** avancé · **Langue du PDF :** anglais

Décorticage pratique d'`impacket-atexec`, l'un des exécuteurs de commandes à
distance de la suite Impacket (Fortra). Le guide montre, pas à pas et contre un
contrôleur de domaine de laboratoire, comment l'outil abuse du Planificateur de
tâches Windows (interface MSRPC `ATSVC`/`TSCH`) pour exécuter une commande,
récupérer sa sortie via `ADMIN$` puis effacer sa trace.

## Au programme

- Le mécanisme d'`atexec` : tâche planifiée temporaire, exécution, récupération
  de la sortie, nettoyage — et sa place face à `psexec`, `smbexec`, `wmiexec`.
- Les quatre voies d'authentification Active Directory : mot de passe en clair,
  Pass-the-Hash (NTLM), Pass-the-Ticket (Kerberos) et Pass-the-Key (clé AES).
- Obtention d'un reverse shell PowerShell interactif via `-silentcommand`.
- Les options opérationnelles : `-dc-ip`, `-codec`, horodatage et sortie de débogage.

## Prérequis

Droits d'administrateur local sur la cible, connaissance de SMB et des bases
d'Active Directory.

> **Usage.** Strictement réservé aux systèmes dont vous avez la propriété ou
> l'autorisation explicite de test.

📄 [`impacket-atexec.pdf`](impacket-atexec.pdf) · 12 pages
