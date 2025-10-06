# ⚡ Informe de Selecció de Sistema d'Alimentació Ininterrompuda (SAI)

## 🧭 1. Introducció
Aquest informe té com a objectiu presentar els càlculs realitzats per determinar la **potència necessària** per a un conjunt d'equips informàtics i la **selecció d’un SAI adequat** per garantir la continuïtat operativa en cas d’interrupcions elèctriques.

---

## 🧮 2. Càlculs realitzats

### 💡 2.1 Potència total dels equips
S'han considerat els següents equips:

| Equip | Model | Potència (W) | Quantitat | Total (W) |
|:------|:------|:-------------:|:----------:|:----------:|
| Monitor | ThinkCentre M90a Gen 6 (24″ Intel) AIO | 230 | 4 | 920 |
| Ordinador | ThinkStation P3 Tower (Intel) | 750 | 4 | 3000 |
| Router | Mesh WiFi 6 AX3000 | 18 | 1 | 18 |
| Impressora multifunció | Brother DCP-L3560CDW | 560 | 1 | 560 |
| **Total sense reserva** | | | | **4498 W** |

Afegint una **reserva del 20%**:

> 🧾 **Potència total requerida:**  
> 4498 W × 1,2 = **5397,6 W**

---

## 🔍 3. Models de SAI analitzats

| Model | Potència (W) | Autonomia | Sortides | Preu (€) | Marca | Imatge |
|:------|:-------------:|:----------:|:----------|:---------:|:-------:|:------------:|
| **Lapara 6000VA/6000W v1.0** | 6000 | 20 min (mitja càrrega) | IEC C13, C19, USB, RS232, RJ45 | **1.647,09** | Lapara | ![SAI Lapara 6000VA/6000W v1.0](img/SAI3) |
| **Riello Sentinel Dual SDU 6000** | 6000 | Ampliable amb bateries | IEC C13, F, USB, RS232 | 1.281,88 | Riello | ![SAI Riello Sentinel Dual SDU 6000](img/SAI2) |
| **Phasak 6000VA Online** | 5400 | No especificada | Terminal Block, USB | 1.129,53 | Phasak | ![SAI Phasak 6000VA Online](img/SAI1) |

---

## ✅ 4. Justificació de la selecció final

Després d’analitzar les opcions disponibles, es recomana el **Lapara 6000VA/6000W v1.0** per les raons següents:

- ⚙️ **Potència suficient:** amb 6000 W, cobreix àmpliament les necessitats dels equips amb la reserva inclosa.  
- 🔋 **Autonomia adequada:** 20 minuts a mitja càrrega permeten un tancament segur dels sistemes.  
- 🔌 **Sortides versàtils:** permeten una connexió flexible dels equips informàtics.  
- 💰 **Relació qualitat-preu:** tot i ser el més car, ofereix les millors prestacions globals.

> Els altres models, tot i complir amb els requisits mínims, presenten limitacions en autonomia o en el tipus de sortides que poden no ser òptimes per a les necessitats concretes.

---

## 🏁 5. Conclusió

La selecció del **SAI Lapara 6000VA/6000W v1.0** és la **més adequada** per garantir la protecció i la continuïtat operativa dels equips informàtics analitzats, complint plenament amb els requisits de **potència** i **autonomia** establerts.

---

### 🧷 Resum visual
| Criteri | Lapara 6000VA | Riello SDU 6000 | Phasak 6000VA |
|:--|:--:|:--:|:--:|
| Potència | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ |
| Autonomia | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐ |
| Tipus de sortides | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐ |
| Preu | ⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐ |
| **Resultat global** | 🥇 **Recomanat** | 🥈 Alternativa | 🥉 Bàsic |

---

✍️ *Informe elaborat per a la selecció tècnica del SAI per a equips informàtics (2025).*

[Tornar a l'inici](../README.md)
