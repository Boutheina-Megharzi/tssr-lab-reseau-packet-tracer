# tssr-lab-reseau-packet-tracer
Laboratoire réseau Cisco Packet Tracer : topologie simple, adressage IP, configuration d’un routeur et de switchs, tests de connectivité
# Laboratoire réseau virtuel : Cisco Packet Tracer

Laboratoire réseau Cisco Packet Tracer : topologie simple, adressage IP, configuration d'un routeur et de switchs, tests de connectivité.

## Statut
🟡 **En cours.** Avancement :
- [ ] Topologie construite
- [ ] PC configurés (IP, masque, passerelle)
- [ ] Routeur configuré
- [ ] Switchs configurés
- [ ] Tests de connectivité réalisés
- [ ] Panne simulée et corrigée
- [ ] Captures d'écran ajoutées

## Objectif
Relier deux réseaux locaux avec un routeur et vérifier que les machines communiquent entre elles.

## Compétences travaillées
- Adressage IPv4 (adresse, masque, passerelle)
- Configuration de base d'un routeur et de switchs Cisco
- Tests de connectivité (`ping`, `tracert`)
- Diagnostic d'une panne simple

## Environnement
- Logiciel : Cisco Packet Tracer (version : [à compléter])
- Matériel simulé : 1 routeur, 2 switchs, 4 PC
- Réseau : adresses privées uniquement

## Architecture

```
 LAN A : 192.168.10.0/24                  LAN B : 192.168.20.0/24

 PC1 ─┐                                              ┌─ PC3
      ├─ SW1 ── G0/0 [ R1 ] G0/1 ── SW2 ─┤
 PC2 ─┘                                              └─ PC4
```

## Plan d'adressage
| Appareil | Interface | Adresse IP | Masque | Passerelle |
|---|---|---|---|---|
| R1 | G0/0 | 192.168.10.1 | 255.255.255.0 | n/a |
| R1 | G0/1 | 192.168.20.1 | 255.255.255.0 | n/a |
| PC1 | carte réseau | 192.168.10.10 | 255.255.255.0 | 192.168.10.1 |
| PC3 | carte réseau | 192.168.20.10 | 255.255.255.0 | 192.168.20.1 |

(Tableau complet à compléter pour SW1, SW2, PC2 et PC4.)

## Réalisation
1. **Construction de la topologie** : [à compléter]
2. **Configuration des PC** : [à compléter]
3. **Configuration du routeur** : [à compléter]
4. **Configuration des switchs** : [à compléter]

## Tests de connectivité
| Test | Commande | Résultat attendu | Résultat obtenu |
|---|---|---|---|
| Même LAN | `ping 192.168.10.11` | Réponse | [à compléter] |
| Vers la passerelle | `ping 192.168.10.1` | Réponse | [à compléter] |
| Entre les deux LAN | `ping 192.168.20.10` | Réponse | [à compléter] |
| Chemin suivi | `tracert 192.168.20.10` | 2 sauts | [à compléter] |

## Panne simulée
- **Panne introduite** : [à compléter]
- **Symptôme observé** : [à compléter]
- **Raisonnement** : [à compléter]
- **Correction** : [à compléter]

## Difficultés rencontrées
- [problème] → [solution]

## Pistes d'amélioration
- Ajouter un serveur DHCP
- Ajouter des VLAN
