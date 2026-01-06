# 🧹 To-Do Pulizie Domestiche

Questa è una **web app semplice e intuitiva** per gestire le pulizie di casa tramite una **to-do list intelligente**, pensata per essere usata **da iPhone come un’app** (tramite GitHub Pages).

L’app organizza le attività in base alla loro **frequenza**:
- giornaliera
- settimanale
- mensile
- straordinaria (in mesi specifici)

Ogni attività compare **automaticamente** secondo regole precise e scompare quando viene completata.

---

## 📱 Come si usa
1. Apri il sito con **Safari**
2. Tocca **Condividi → Aggiungi alla schermata Home**
3. Usala come una normale app

Funziona anche **offline**.

---

## 🔁 Regole di funzionamento

### ✅ Attività giornaliere
- Sono **sempre visibili**
- Si **resettano ogni giorno**
- Anche se completate, ricompaiono il giorno successivo

**Attività incluse:**
- 🌬️ Arieggiare le stanze  
- 🛏️ Rifare i letti  
- 🍽️ Svuotare stoviglie  
- 🧹 Passare aspirapolvere  
- 🧺 Riordinare oggetti fuori posto  
- 🚿 Pulizia veloce bagni  
- 🍽️ Pulire tavolo  
- 🍳 Pulire piano cucina  
- 🗑️ Buttare immondizia  

---

### 🗓️ Attività settimanali
- Compaiono **solo nel giorno della settimana corretto**
- Si resettano il giorno successivo

**Programmazione:**
- **Lunedì** → 🛏️ Materassi e cambio lenzuola, 🪶 Spolverare  
- **Martedì** → 🪶 Spolverare  
- **Mercoledì** → 🚿🧽 Pavimenti e bagni  
- **Giovedì** → 👕 Bucato  
- **Venerdì** → ♻️🧺 Bidoni e tappeti  
- **Domenica** → 🧹 Aspirapolvere  

---

### 🗂️ Attività mensili
- Compaiono **all’inizio del mese**
- Restano visibili **finché non vengono completate**
- Una volta spuntate, **scompaiono**
- Ricompaiono automaticamente il **mese successivo**

**Attività incluse:**
- ❄️ Frigo  
- 🔥 Forno e microonde  
- 🍽️💨 Lavastoviglie e cappa  
- 👕🔄 Lavatrice e asciugatrice  
- 🧹✨ Pulizia profonda aspirapolvere  
- 🪟 Vetri  
- 📏 Battiscopa  
- 🚪 Porte  
- 🔘 Interruttori  
- 🌿 Giardino  

---

### 🚨 Pulizie straordinarie
- Compaiono **solo in mesi specifici**
- Restano visibili per tutto il mese finché non vengono completate
- Ricompaiono automaticamente negli stessi mesi dell’anno successivo

**Programmazione:**
- 🚰 Scarichi → gennaio, giugno, novembre  
- 🛋️ Mobili sotto e dietro → febbraio, giugno, ottobre  
- ☕🫖 Decalcificazione macchina caffè e bollitore → febbraio, luglio, dicembre  
- 🗄️ Interno dei cassetti → gennaio, maggio, settembre  
- ♨️❄️ Termosifoni e condizionatori → maggio, ottobre  
- 🏠 Soffitto e pareti → marzo, luglio, novembre  
- 📦 Spolverare in alto → aprile, agosto, dicembre  
- 🌱 Pavimento giardino → aprile, agosto  
- 🌳 Ordinare giardino → marzo, luglio, novembre  
- 👚 Cambio stagione → aprile, ottobre  
- 🧱 Marciapiede e muri esterni → gennaio, settembre  

---

## 💾 Come vengono salvati i dati
- Lo stato delle attività viene salvato in **localStorage**
- Nessun account richiesto
- Nessun dato inviato online
- I dati restano sul dispositivo

⚠️ Nota: cambiando dominio (es. rinominando la repository) le checklist ripartono vuote.

---

## 🛠️ Tecnologie usate
- HTML
- CSS
- JavaScript
- GitHub Pages

---

## 🎯 Obiettivo
Avere una **gestione chiara, sostenibile e senza stress** delle pulizie di casa, senza dover ricordare tutto a memoria.

---

## ✨ Possibili miglioramenti futuri
- Barra di avanzamento mensile
- Evidenziazione delle priorità
- Nascondere automaticamente le sezioni vuote
- Storico delle attività completate
