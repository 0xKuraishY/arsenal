# Reverse Engineering d'exécutables Windows — Volume 1

**Domaine :** Reverse engineering · **Niveau :** débutant (prérequis : savoir programmer)

Le point de départ de la série : du zéro absolu en reverse jusqu'à l'analyse de
malwares EXE réels. Pensé pour l'analyste sécurité qui programme déjà (Python/Bash)
mais n'a jamais touché à l'assembleur ou au format PE. Exercices et walkthroughs complets.

## Au programme

- **Mindset & lab** : poser un environnement d'analyse isolé, cadre légal et éthique.
- **Assembleur x86/x64** : registres, pile, instructions, fonctions et conventions d'appel.
- **Format PE** : structure d'un EXE, Import Address Table, sections, signaux d'anomalie.
- **Analyse statique** : triage, prise en main de Ghidra et d'IDA Free, lecture du
  pseudocode, extraction d'une configuration C2.
- **Analyse dynamique** : x64dbg, breakpoints, ProcMon/Process Hacker, capture réseau
  (FakeNet-NG), unpacking.
- **Windows internals pour le RE** : chargement d'un programme, PEB/TEB, API prisées
  des malwares, injection, persistance.
- **Familles de malwares** : ransomware, infostealer, RAT, loader/dropper.
- **Du malware au rapport SOC** : IOCs, règles YARA et Sigma, mapping MITRE ATT&CK.
- **Labs progressifs** : du premier RE guidé à l'extraction de config C2, plan sur 6 mois.

> Environnement d'analyse isolé obligatoire. Usage pédagogique et défensif.

📄 [`re-exe-windows-vol1.pdf`](re-exe-windows-vol1.pdf) · 59 pages
