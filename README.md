# Partie 6 : Sécurité de la plateforme

Chiffrer les échanges, gérer les identités, durcir le cluster et sortir les secrets des manifests.

**Auteure :** Hanin Haj Youssef — Master DevOps & Cloud

## Contenu

| TP | Outil(s) | Dossier | Statut |
|----|----------|---------|--------|
| TP16 | cert-manager, Keycloak | `tp16-cert-manager-keycloak/` | En cours |
| TP17 | RBAC, PSS, NetworkPolicy, Kyverno, Falco | `tp17-securite-k8s/` | En cours |
| TP18 | Vault, External Secrets, Sealed Secrets | `tp18-gestion-secrets/` | En cours |

## TP16 : HTTPS et gestion des identités
HTTPS avec une CA de lab (cert-manager), IAM avec Keycloak : OIDC, rôles, oauth2-proxy.

## TP17 : Sécurité Kubernetes en profondeur
RBAC, Pod Security Standards, NetworkPolicy, Policy as Code (Kyverno), analyse continue et détection à l'exécution (Falco).

## TP18 : Gestion des secrets
Coffre-fort (Vault), synchronisation (External Secrets), chiffrement pour Git (Sealed Secrets), rotation.

## Prérequis
Cluster du TP14, chart du TP15 ; le TP18 utilise aussi Floci (TP13).
