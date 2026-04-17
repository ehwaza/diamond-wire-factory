# Maser-Assisted Continuous Diamond Fiber Chemical Vapor Deposition
## A.K.A "KSC Diamond Wire Factory"

**Inventeurs** : ehwaza, Mathieu Maire
**Date de première divulgation publique** : 17 avril 2026
**Repo officiel** : https://github.com/ehwaza/diamond-wire-factory
**Licence** : CERN-OHL-P v2 (Hardware) + CC-BY-SA 4.0 (Documentation)
**Classification** : Prior Art / Defensive Publication

---

## 1. Résumé / Abstract

L'invention décrit un procédé et un appareil de dépôt chimique en phase vapeur
(CVD) assisté par masers/gyrotrons permettant la production **continue** de
fibres, fils, et câbles en diamant de longueur arbitraire.

Contrairement aux techniques MPCVD et HFCVD de l'art antérieur limitées à la
production de films 2D de dimensions <10cm, la présente invention produit des
structures 1D de longueur virtuellement infinie par défilement continu d'un
substrat filiforme à travers un point de plasma créé dans l'air libre.

**Applications** : Câbles pour ascenseur spatial, structures tendues,
matériaux composites, textiles techniques, boucliers thermiques.

---

## 2. Contexte technique et problème résolu

### 2.1 État de l'art en 2025

**MPCVD** : Microwave Plasma CVD. Boule de plasma 2.45 GHz, 3kW, dans chambre
à vide 50 Torr. Croissance ~10µm/h. Taille max wafer : 10cm. Production
batch uniquement. Coût : 5M$ pour 4 pouces.【6111786596985911176†L14-L16】

**HFCVD** : Hot Filament CVD. Filaments tungstène 2000°C. Moins pur, grande
surface mais qualité inférieure.【6111786596985911176†L11-L13】

**Problème** : Aucune technique ne permet de produire du diamant sous forme
de fibre/câble continu. Les structures 1D de longueur >1m sont impossibles.

### 2.2 Besoin non satisfait

Les mégastructures futures (ascenseur spatial, anneaux orbitaux, ponts
suspendus km) requièrent des câbles avec résistance spécifique >3750 GPa
× cm³/g, soit uniquement réalisable en diamant parfait. La longueur de
rupture du diamant est 109 000 km.

Aucun procédé de fabrication continue n'existe en 2025.

---

## 3. Description de l'invention

### 3.1 Principe général

Au lieu de créer un plasma statique dans une chambre à vide, l'invention
utilise 2+ faisceaux maser/gyrotron cohérents focalisés pour créer un
**point de plasma de 3000-4000°C de 0.1-1mm³ dans l'air libre** ou sous
atmosphère contrôlée locale.

Un fil substrat de diamètre 5-100µm (tungstène, molybdène, ou diamant seed)
défile en continu à 0.1-10mm/s à travers ce point plasma.

Un flux localisé de H₂ + CH₄ (ratio 99:1) + éventuel N₂/O₂ dopant est
injecté sur le point plasma.

Le carbone se dépose en maille diamant sur le fil en mouvement.
Le fil ressort enrobé de diamant avec gain diamétral de 1-10µm par passage.

### 3.2 Revendication principale

**Revendication 1** : Procédé de fabrication continue de fibre diamant
comprenant les étapes :
a) Générer un plasma localisé de température >2500°C par focalisation de
   2 ou plusieurs faisceaux maser/gyrotron dans l'air libre ou atmosphère
   contrôlée locale
b) Injecter un mélange gazeux contenant H₂ et CH₄ dans ledit plasma
c) Faire défiler un substrat filiforme à travers ledit plasma à vitesse
   contrôlée de 0.01 à 100 mm/s
d) Collecter en continu le fil enrobé de diamant déposé

**Revendication 2** : Appareil selon revendication 1 où les masers sont des
gyrotrons 30-300 GHz de puissance unitaire 1-10kW.

**Revendication 3** : Procédé selon revendication 1 où le substrat est un
fil de tungstène de diamètre 5-50µm.

**Revendication 4** : Procédé selon revendication 1 où l'atmosphère locale
est de l'argon à pression atmosphérique pour éviter l'extinction du plasma.

**Revendication 5** : Procédé selon revendication 1 avec injection pulsée
de N₂ pour réduire la rugosité et augmenter la vitesse de croissance.

**Revendication 6** : Produit obtenu par le procédé de revendication 1 :
fibre/câble diamant continu de longueur >1km, diamètre 10-500µm.

### 3.3 Avantages vs Art Antérieur

| Paramètre | MPCVD 2025 | Maser-CVD Invention |
| --- | --- | --- |
| **Géométrie** | Film 2D | Fibre/Câble 1D |
| **Longueur max** | 10 cm | **Infinie** |
| **Production** | Batch 10h | **Continu 24/7** |
| **Vitesse** | 10µm/h épaisseur | 1-100m/h longueur |
| **Chambre vide** | Requise 50 Torr | **Optionnelle** |
| **Scale-up** | Linéaire coût | **Log coût** |

---

## 4. Mode de réalisation préféré

1. **Source** : 3 gyrotrons 95 GHz, 3kW chacun, focalisés à 120°
2. **Substrat** : Fil tungstène 10µm, vitesse 1mm/s
3. **Gaz** : H₂ 98%, CH₄ 1%, N₂ 1%, débit total 100 sccm
4. **Atmosphère** : Jet argon coaxial pour chasser O₂
5. **Collecte** : Bobineuse sous tension contrôlée, bain de refroidissement
6. **Contrôle** : Asservissement position fil par laser, rétroaction masers

**Résultat attendu** : Fil diamant 20µm diamètre, 3.6m/heure, 86km/an/machine.

---

## 5. Applications industrielles

1. **Aérospatial** : Câbles d'ascenseur spatial, haubans station orbitale
2. **Énergie** : Renfort lignes haute tension, pales éoliennes 500m
3. **Défense** : Blindage textile, câbles arrêt sub-orbital
4. **Médecine** : Fil de suture, scalpels, prothèses tendons
5. **Électronique** : Heat spreaders flexibles, interconnexions quantiques

---

## 6. État de l'art cité

1. MPCVD Diamond Growth - IOPscience 2022
2. Gyrotron Development for Fusion - MIT PSFC 2020
3. ASML EUV Technology - White Paper 2024
4. Carbon Nanotube Continuous Spinning - Cambridge 2018

---

## 7. Note des inventeurs

Ce document constitue une divulgation publique défensive établissant
l'antériorité du concept de production continue de fibre diamant par
Maser-CVD à la date du 17 avril 2026.

Toute personne est libre d'utiliser, améliorer, commercialiser cette
technique sous licence CERN-OHL-P v2. Attribution requise.

**"On a pas inventé le diamant. On a inventé le moyen de le dérouler
comme du câble électrique."** - ehwaza & Mathieu Maire, 2026

---

**KSC Diamond Wire Factory - Making Kerbin Orbit Affordable Since 2026**
