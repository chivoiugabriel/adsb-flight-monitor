# ADS-B Real-Time Flight Tracker

![Project Status](https://img.shields.io/badge/status-completed-green)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![SQLite](https://img.shields.io/badge/Database-SQLite-lightgrey)

## 📖 Descriere Proiect
Acest proiect reprezintă lucrarea mea de licență și constă în dezvoltarea unui sistem complet de procesare și vizualizare în timp real a datelor ADS-B (Automatic Dependent Surveillance–Broadcast).

Aplicația interceptează pachetele de date emise de aeronave, le decodează și le afișează pe o hartă interactivă, permițând monitorizarea traficului aerian într-o anumită arie geografică.

### 🎥 Demo
[Link către prezentarea video pe YouTube](https://youtu.be/TbAoq7PAWK0)

## 🚀 Funcționalități Cheie
* **Decodare în timp real:** Procesarea mesajelor ADS-B brute primite de la receptoare.
* **Stocare Persistență:** Salvarea istoricului de zbor într-o bază de date **SQLite** pentru analize ulterioare.
* **Vizualizare Web:** Interfață web interactivă (WebMap) care afișează poziția, altitudinea și viteza avioanelor.
* **Identificare Zbor:** Corelarea codului ICAO cu informații despre compania aeriană și tipul aeronavei.

## 🛠️ Tehnologii Utilizate
* **Limbaj principal:** Python
* **Bază de date:** SQLite
* **Frontend/Vizualizare:** HTML, JavaScript, Leaflet.js (pentru hărți)
* **Hardware (Opțional):** RTL-SDR (pentru recepția semnalului radio)

## 📂 Structura Proiectului
* `/core` - Scripturile principale de procesare a datelor.
* `/web` - Interfața grafică și serverul web.
* `/db` - Schema bazei de date și interogări SQL.

## 🔧 Cum să rulezi proiectul
1. Clonează acest repository:
   ```bash
   git clone [https://github.com/chivoiugabriel/adsb-flight-monitor.git](https://github.com/chivoiugabriel/adsb-flight-monitor.git)
