# Reverse Engineering d'exécutables Windows — Volume 3

**Domaine :** Reverse engineering · **Niveau :** expert · **Prérequis :** Volumes 1 et 2

Le niveau expert de la série : kernel, APT, threat intelligence et RE à l'échelle
industrielle. Cas pratiques sur des TTP de groupes documentés.

## Au programme

- **RE kernel-mode** : drivers Windows (.sys), rootkits (SSDT hooking, DKOM, IRP hooks),
  détection depuis l'user-mode, BYOVD.
- **WinDbg kernel debugging** : configuration, commandes essentielles, analyse des pools
  et objets, breakpoints kernel, crash dumps/BSOD, scripts JavaScript.
- **Protocoles C2 avancés** : DNS tunneling, C2 over HTTPS, stéganographie réseau,
  domain fronting, reverse d'un protocole binaire custom.
- **Documents malveillants** : macros VBA et XLM, PDF/OneNote piégés, HTML smuggling,
  outils `olevba`, `peepdf`, `pdf-parser`.
- **Threat intelligence & attribution** : clustering (imphash, SSDEEP), fingerprinting
  de C2, pivoting sur IOCs, Diamond Model, MISP.
- **RE d'exploits** : corruption mémoire, lecture de shellcode, de l'advisory au code.
- **Firmware & UEFI** : extraction, implants, bootkits, Binwalk/UEFITool/Chipsec.
- **RE à l'échelle** : triage de masse, clustering (MinHash/LSH), Ghidra headless, SIEM+SOAR+CTI.
- **Case studies APT** : méthodologie et analyse de malwares de groupes réels.

> Environnement d'analyse isolé obligatoire. Usage pédagogique et défensif.

📄 [`re-exe-windows-vol3.pdf`](re-exe-windows-vol3.pdf) · 52 pages
