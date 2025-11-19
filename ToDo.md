# 🛠️ i3 MK0 — Restauratie TODO-Lijst
Dit project heeft als doel om een oude **i3 MK0 (2.85mm)** 3D-printer te **restaureren naar originele werkende staat**, zonder grote upgrades.  
Alleen herstellen wat kapot, versleten of fout aangesloten is.

---

## 1️⃣ Project Setup (GitHub & Documentatie)
- [ ] Nieuwe GitHub-repository aanmaken  
- [ ] README.md toevoegen met projectbeschrijving  
- [ ] Mapstructuur aanmaken:
  - [ ] `/firmware-backup`
  - [ ] `/hardware-photos`
  - [ ] `/wiring-photos`
  - [ ] `/docs`
- [ ] Nieuw logboek starten → `/docs/logboek.md`

---

## 2️⃣ Documentatie van de Huidige Staat
- [ ] Foto's maken van de volledige printer  
- [ ] Detailfoto's maken van:
  - [ ] moederbord  
  - [ ] display  
  - [ ] hotend  
  - [ ] extruder  
  - [ ] riemen  
  - [ ] bedrading  
- [ ] In logboek noteren:
  - Wat werkt wel  
  - Wat werkt niet  
  - Wat ontbreekt  
  - Wat beschadigd is  

---

## 3️⃣ Elektronische Backup & Inspectie
- [ ] Firmware uitlezen indien mogelijk (hex-file opslaan in `/firmware-backup`)  
- [ ] Controle van PCB op:
  - [ ] verbrande connectors  
  - [ ] koude soldeerpunten  
  - [ ] losse kabels  
- [ ] Alle kabels labelen  
- [ ] Wiring-foto’s maken en opslaan in `/wiring-photos`

---

## 4️⃣ Mechanische Restauratie
(Geen upgrades — alleen herstellen/schoonmaken)

- [ ] Alle bewegende delen schoonmaken  
- [ ] Lineaire lagers controleren (LM8UU)  
- [ ] Assen schoonmaken en licht smeren  
- [ ] Riemen inspecteren op scheurtjes  
- [ ] Riemspanning corrigeren  
- [ ] Z-stangen reinigen en smeren  
- [ ] Controle of hotend stevig gemonteerd zit  
- [ ] Printbed oppervlakte controleren  
- [ ] Alle schroeven nalopen en vastzetten  

---

## 5️⃣ Elektrische Restauratie
- [ ] PSU spanning testen  
- [ ] Connectors controleren (geen verkleuring/smeltschade)  
- [ ] Endstops testen (X/Y/Z)  
- [ ] Thermistors testen (hotend + bed)  
- [ ] Heater-cartridge testen  
- [ ] Displaykabels verifiëren  
- [ ] Steppers testen (manueel draaien → geen hapering)

---

## 6️⃣ Firmware (Originele Staat Behouden)
- [ ] Marlin-versie controleren (1.0.0 RC2 zichtbaar op display)  
- [ ] Endstop-configuratie testen  
- [ ] Motorrichting controleren  
- [ ] Temperatuurmetingen controleren  
- [ ] *Geen firmware-upgrade uitvoeren tenzij strikt noodzakelijk*

---

## 7️⃣ Functionele Tests
- [ ] Test beweging X-as  
- [ ] Test beweging Y-as  
- [ ] Test beweging Z-as  
- [ ] Homing test uitvoeren  
- [ ] Hotend warmt op?  
- [ ] Heatbed warmt op?  
- [ ] Extruder:
  - [ ] pakt filament  
  - [ ] slipt niet  

---

## 8️⃣ Kalibratie
- [ ] Manueel bed levelen  
- [ ] Extruder E-steps calibreren  
- [ ] Steps per mm controleren (X/Y/Z)  
- [ ] PID autotune uitvoeren voor hotend  
- [ ] PID autotune uitvoeren voor bed  

---

## 9️⃣ Testprint
- [ ] 20mm calibration cube printen  
- [ ] Resultaten beoordelen:
  - laagconsistentie  
  - onder-/overextrusie  
  - ghosting  
  - temperatuurproblemen  
- [ ] Kleine correcties doorvoeren  

---

## 🔟 Documentatie Afronden
- [ ] Voor/na foto's uploaden naar repo  
- [ ] Logbook invullen met uitgevoerde reparaties  
- [ ] README uitbreiden met:
  - Overzicht problemen & oplossingen  
  - Tips voor toekomstig onderhoud  
- [ ] Backups veilig opslaan  

---

## ✔️ Projectstatus
- Restauratie zonder modernisering  
- Focust op reparatie, reiniging en afstelling  
- Originele hardware zo veel mogelijk behouden

