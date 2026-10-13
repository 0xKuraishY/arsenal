<div align="center">

<img src="assets/logo.svg" alt="Arsenal" width="96">

# Arsenal

Guides techniques de cybersécurité en français, du niveau débutant à expert.<br>
Rédigés par **0xKuraishY**.

[![Licence : CC BY-NC-SA 4.0](https://img.shields.io/badge/licence-CC_BY--NC--SA_4.0-lightgrey)](LICENSE)

</div>

---

## À propos

Une collection de guides techniques pensés pour aller au fond des sujets :
le **pourquoi** autant que le **comment**. Chaque document explique les
mécanismes, pas seulement les commandes, avec des schémas, des exemples
concrets et un regard orienté terrain.

Les guides sont organisés par domaine ci-dessous. Chaque dossier contient
le PDF et une courte description.

---

## Méthode de création

Transparence sur la fabrication de ces documents :

- **Rédaction assistée par IA.** Les guides sont mis en forme à l'aide d'un
  modèle de langage. L'IA sert à la structuration, à la rédaction et à la
  mise en page.
- **Conception et cadrage humains.** Les sujets, les plans, les angles et les
  consignes de rédaction (les *prompts*) sont définis par un **analyste SOC
  en poste**, à partir de besoins réels du terrain. Le choix de ce qui est
  important, de la profondeur et du niveau d'exigence est humain.
- **Sources vérifiées.** Le contenu s'appuie sur des sources de référence
  (documentation officielle des éditeurs, spécifications, pages de manuel,
  publications des autorités de cybersécurité), citées en annexe de chaque
  guide. Les informations sensibles aux versions sont vérifiées au moment de
  la rédaction.

En clair : l'IA écrit, un professionnel de la cybersécurité décide du quoi,
du comment et vérifie que ça tient. Ces documents restent une base de travail
et d'apprentissage : recoupez toujours une information critique avec la source
officielle correspondante.

---

## Catalogue

Les guides marqués *(à venir)* sont en préparation : leur dossier décrit
déjà le contenu prévu, le PDF arrivera dans un prochain ajout.

### Blue team
| Guide | Niveau | Description |
|-------|--------|-------------|
| [Réponse à incident](blue-team/reponse-incident/) | Tous | Sécuriser, détecter et réagir à une compromission |
| [Analyse de risque](blue-team/analyse-de-risque/) | Expert | EBIOS RM, quantification FAIR, Monte-Carlo |
| [Detection engineering](blue-team/detection-engineering/) *(à venir)* | Avancé | Concevoir des détections qui tiennent |
| [Détection d'anomalies](blue-team/detection-anomalies/) | Avancé | Statistiques & ML : lignes de base, scores, UEBA, et pourquoi l'« IA » fait du bruit |
| [Forensique mémoire](blue-team/forensique-memoire/) | Expert | Analyser une machine en vie (Volatility 3) |

### Red team
| Guide | Niveau | Description |
|-------|--------|-------------|
| [Impacket — atexec](red-team/impacket/) | Avancé | Exécution à distance et attaques d'authentification AD |
| [WinRM pentest](red-team/winrm-pentest/) | Avancé | Exploitation et post-exploitation WinRM |
| [Active Directory](red-team/active-directory/) *(à venir)* | — | Attaque et post-exploitation Active Directory |

### Reverse engineering
| Guide | Niveau | Description |
|-------|--------|-------------|
| [RE Windows — Vol. 1](reverse-engineering/re-exe-windows-vol1/) | Débutant | Fondamentaux du reverse d'exécutables |
| [RE Windows — Vol. 2](reverse-engineering/re-exe-windows-vol2/) | Intermédiaire | Techniques avancées |
| [RE Windows — Vol. 3](reverse-engineering/re-exe-windows-vol3/) | Expert | Niveau avancé |
| [Malware : anatomie & obfuscation](reverse-engineering/malware-anatomie-obfuscation/) | Avancé | Décorticage de code malveillant |

### Internals
| Guide | Niveau | Description |
|-------|--------|-------------|
| [Rocky Linux & RHEL](internals/rocky-rhel-internals/) | Expert | Le système Enterprise Linux de l'intérieur |
| [Windows internals](internals/windows-internals/) *(à venir)* | Expert | Windows vu par un défenseur : jetons, LSASS, ETW, artefacts |

### Identité & cryptographie
| Guide | Niveau | Description |
|-------|--------|-------------|
| [Kerberos, NTLM & AD](identity-crypto/kerberos-ntlm-ad/) *(à venir)* | Expert | L'authentification Windows et le pourquoi de chaque attaque |
| [Identité cloud](identity-crypto/identite-cloud/) *(à venir)* | Expert | OAuth, OIDC, SAML et leurs attaques modernes |
| [Cryptographie appliquée](identity-crypto/cryptographie-appliquee/) *(à venir)* | Avancé | TLS 1.3, PKI et ce qui casse en pratique |

### Détection réseau
| Guide | Niveau | Description |
|-------|--------|-------------|
| [Analyse réseau](network-detection/analyse-reseau/) *(à venir)* | Avancé | Voir au-delà du chiffrement : JA4, beaconing, Zeek, Suricata |

---

## Comment lire ces guides

Chaque chapitre suit la même logique :

- **L'idée clé** en une phrase
- **Le mécanisme**, expliqué en profondeur
- **Les commandes** pour l'observer soi-même
- **Un regard terrain** (détection, pièges, angles morts)
- **À retenir** en fin de chapitre

---

## Licence & usage

Ces documents sont publiés à des fins **éducatives et de recherche**.
Leur contenu ne doit être utilisé que sur des systèmes dont vous avez la
propriété ou l'autorisation explicite de test.

Sauf mention contraire, l'ensemble est sous licence
[CC BY-NC-SA 4.0](LICENSE) : partage et adaptation autorisés, avec
attribution, sans usage commercial, à conditions identiques.

---

<div align="center">

**0xKuraishY** · Guides mis à jour régulièrement

Si cette collection vous est utile, pensez à mettre une étoile au dépôt.

</div>