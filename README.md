# Portfolio – Michel-Ange Doubogan - Cybersecurity

## Introduction  
Je suis un développeur spécialisé dans l’automatisation, le développement d’applications Web et la maintenance de services.  
Au fil de mes projets, j’ai souvent dû adapter nos solutions afin de respecter des politiques de sécurité strictes, ce qui a éveillé mon intérêt pour la cybersécurité.  

Pour acquérir et renforcer mes compétences en cybersécurité, je me suis formé sur différentes plateformes d’apprentissage pratique, notamment à travers des environnements de type labs et des parcours structurés. Ces expériences m’ont permis de développer une approche analytique et une meilleure compréhension des menaces réelles.  

Je m’oriente désormais vers des rôles axés sur la défense et la sécurisation de systèmes, tels que **SOC Analyst** ou **Cybersecurity Analyst**, où je peux mettre à profit mes compétences techniques tout en consolidant une expertise approfondie en sécurité de l’information.

---

## Compétences

| Compétence                                                            | Projet associé |
|-----------------------------------------------------------------------|----------------|
| Triage d'alerte en temps réél    | [Phishing SOC Simulation](https://github.com/Setounkpe7/Phishing-SOC-Simulator) |
| Application de la Cyber Kill Chain pour la mitigation des attaques    | [Summit](https://github.com/Setounkpe7/Summit) |
| Rédaction d’un rapport d’incident                                     | [Security Incident Report](https://github.com/Setounkpe7/Security-Incident-Report-HTTP-Malware-Redirect) |
| Détection IDS/IPS (Snort)                                             | [Snort – Live Attacks](https://github.com/Setounkpe7/Snort-Live-Attacks) |
| Automatisation & gestion de fichiers Python                            | [Update-a-File-through-Python](https://github.com/Setounkpe7/Manage-Access-List-With-Python) |
| Gestion des permissions Linux                                          | [File-Permissions-in Linux](https://github.com/Setounkpe7/File-Permissions-Linux) |
| Analyse d’incidents réseau (DNS/ICMP)                                 | [Network-Traffic-Analysis](https://github.com/Setounkpe7/Network-Traffic-Analysis) |
| Évaluation des vulnérabilités système                                 | [Vulnerability-Assessment-Report](https://github.com/Setounkpe7/Vulnerability-Assessment) |
| Audit de sécurité & conformité                                         | [Botium-Toys Security-Assessment](https://github.com/Setounkpe7/Botium-Toys-Security-Assessment) |
| Filtrage & analyse SQL                                                | [Apply Filters to SQL Queries](https://github.com/Setounkpe7/Apply-Filters-SQL-Queries) |
| Analyse des risques & recommandations                                 | [Security Risk Assessment Report](https://github.com/Setounkpe7/Security-Risk-Assessment) |



---

## Outils

### Network  
- Wireshark  
- Snort

### Endpoint  
- Sysinternals Suite  
- OSQuery  
- Windows Event Viewer  

### SIEM  
- Splunk  
- Elastic Stack  

---

## Certifications  
- Google Cybersecurity Professional Certificate  
- CompTIA Security+  

---

## Projets
### [Phishing SOC Simulation](https://github.com/Setounkpe7/Phishing-SOC-Simulator)
Simulation en temps réél de triage d'alertes de type phishing, processus parent-enfant, exécution de scripts malicieux.

### [Summit](https://github.com/Setounkpe7/Summit)  
Simulation immersive de type purple-team visant à améliorer les capacités de détection de PicoSecure via la Pyramid of Pain et la matrice MITRE ATT&CK.  
Compétences clés : analyse de logs, création de règles, investigation SOC.

### [Security Incident Report](https://github.com/Setounkpe7/Security-Incident-Report-HTTP-Malware-Redirect)
Rédaction d'un rapport détaillé sur un incident entraînant l'inaccessibilité d'un site web.

### [Snort-Live-Attacks](https://github.com/Setounkpe7/Snort-Live-Attacks)  
Challenge orienté détection IDS/IPS avec Snort : brute-force SSH, reverse shell, création de règles alert/drop.

### [Network-Attack-Report](https://github.com/Setounkpe7/Network-Traffic-Analysis)  
Analyse d’une attaque de type SYN Flood (DoS) visant un serveur Web : compréhension du handshake TCP, interprétation des logs, recommandations.

### [Apply-Filters-SQL-Queries](https://github.com/Setounkpe7/Apply-Filters-SQL-Queries)  
Projet de filtrage via SQL appliqué à des logs d’authentification : détection d’accès hors horaire, géolocalisation inattendue, segmentation des employés.

### [File-Permissions-in-Linux](https://github.com/Setounkpe7/File-Permissions-Linux)  
Audit et mise à jour des permissions de fichiers/répertoires Linux : application du principe de moindre privilège, manipulation de `chmod`, gestion des fichiers cachés.

### [Update-a-File-through-Python](https://github.com/Setounkpe7/Manage-Access-List-With-Python)  
Automatisation en Python pour gérer une liste « allow_list » d’adresses IP : lecture, transformation, suppression, mise à jour du fichier.

### [Vulnerability-Assessment-Report](https://github.com/Setounkpe7/Vulnerability-Assessment)  
Évaluation des vulnérabilités d’un serveur Linux/MySQL selon la méthode NIST SP 800-30 : classification des risques, scoring, recommandations.

### [Botium-Toys Security-Assessment](https://github.com/Setounkpe7/Botium-Toys-Security-Assessment)  
Audit complet du programme de sécurité d’une entreprise fictive : définition du périmètre, évaluation des contrôles, conformité PCI/GDPR/SOC, plan d’action.

---

## Projets DevSecOps

### [railsgoat-security](https://github.com/Setounkpe7/railsgoat-security)
Hardening DevSecOps d'OWASP RailsGoat (application Rails délibérément vulnérable) : pipeline GitHub Actions à 8 couches (secrets, SAST Brakeman + Semgrep, SCA bundler-audit + Trivy, DAST ZAP, SBOM CycloneDX, Hadolint, Trivy image, signature Cosign sur GHCR), correction des CVE infrastructure et dépendances, registre formel `SECURITY_EXCEPTIONS.md` (28 entrées datées) pour les vulnérabilités intentionnelles acceptées et les CVE OS sans patch upstream.

### [find-one-devsecops-case-study](https://github.com/Setounkpe7/find-one-devsecops-case-study)
Premier case study DevSecOps : pipeline appliqué à la plateforme Find-One (Next.js sur Vercel). Couvre les couches sans image conteneur (secrets, SAST, SCA, SBOM SPDX, DAST ZAP authentifié), avec Dependabot, pre-commit hooks et runbook de rollback.

Ces deux projets ont été développés avec l'aide de l'IA pour accélérer l'implémentation ; les choix d'ingénierie (périmètre, outillage, gating, acceptation de risques) sont les miens.

---

## Contact  
- LinkedIn : [linkedin.com/in/votre-profil](www.linkedin.com/in/michel-ange-doubogan-0731a4129)  
- Email : mdoubogan@yahoo.fr 
