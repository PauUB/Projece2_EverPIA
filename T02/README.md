# Estudi i Selecció d’un SAI per a TecnoGestió S.L.

## 🏢 Descripció de l’empresa

**TecnoGestió S.L.** és una empresa dedicada a la gestió documental i l’assessorament informàtic. Disposa d’un petit despatx amb:

- 4 ordinadors de sobretaula
- 1 impressora-fotocopiadora multifunció
- 1 router d’accés a Internet

A causa de les constants incidències amb el subministrament elèctric, la direcció ha decidit adquirir un **SAI (Sistema d’Alimentació Ininterrompuda)** per garantir la continuïtat del servei i protegir els equips.

---

## 📋 Tasques a realitzar

### 1. Inventari d’equips

EquipQuantitatConnectat al SAI?JustificacióOrdinador de sobretaula4✅ SíProtecció de dades i continuïtat| Monitor                     | 4         | ✅ Sí              | Necessari per visualitzar i apagar   |
| Router                      | 1         | ✅ Sí              | Mantenir connexió a Internet         |
| Impressora multifunció      | 1         | ❌ No              | Consum elevat, no essencial en emergència |

---

### 2. Consulta de consum dels dispositius

DispositiuModel triatConsum (W)Consum (VA)PCHP ProDesk 400 G6250 W312 VAMonitorDell P2419H18 W22 VA| Router         | TP-Link Archer C6        | 12 W       | 15 VA       |

**Total consum:**

- **PCs**: 4 × 250 W = 1000 W → 1248 VA  
- **Monitors**: 4 × 18 W = 72 W → 88 VA  
- **Router**: 12 W → 15 VA  

**Total global:**  
- **Watts:** 1084 W  
- **VA:** 1351 VA

---

### 3. Càlcul de potència total amb reserva

- **Reserva del 20%:**  
  - **Watts amb reserva:** 1084 W × 1.2 = **1300.8 W**  
  - **VA amb reserva:** 1351 VA × 1.2 = **1621.2 VA**

---

### 4. Determinació de l’autonomia

- **Objectiu:** Mantenir els equips funcionant durant **10 minuts** per guardar treballs i apagar correctament.

---

### 5. Recerca de models de SAI

#### 🔍 Models analitzats

ModelPotència (VA)Potència (W)AutonomiaSortidesPreu (€)MarcaAPC Back-UPS Pro 15001500 VA865 W~10 min6x IEC220 €APC| Eaton Ellipse PRO 1600 | 1600 VA       | 1000 W       | ~12 min   | 8x IEC   | 250 €    | Eaton     |
| Salicru SPS SOHO+ 1600 | 1600 VA       | 960 W        | ~10 min   | 6x Schuko| 230 €    | Salicru   |

---

### 6. Informe tècnic

- **Càlculs realitzats:** Potència total amb reserva de 1300 W / 1621 VA  
- **Autonomia mínima requerida:** 10 minuts  
- **Models analitzats:** APC, Eaton, Salicru  
- **Selecció final:** **Eaton Ellipse PRO 1600** per la seva potència adequada, bona autonomia i fiabilitat de marca.

---

## 📚 Material de suport

- Apunts RA1AA3: El SAI

---

## 📁 Contingut de la carpeta del projecte

La carpeta del projecte inclou els següents elements:

- README.md → Document explicatiu amb el resum del projecte i les tasques realitzades.
- [Solucio.md](Solucio.md) → Arxiu amb l'informe tècnic complet, càlculs i justificació de la selecció del SAI.
- img/ → Carpeta amb imatges de suport, com esquemes, captures de models de SAI, gràfics de consum, etc.

---
