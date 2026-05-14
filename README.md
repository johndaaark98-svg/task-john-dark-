# TASK JOHN DARK

App task manager personale. PWA installabile su iPhone/Android.

## Struttura file

```
task-john-dark/
├── index.html              ← l'app (HTML + React + tutto dentro)
├── manifest.json           ← manifest PWA per "Add to Home Screen"
├── splash.jpg              ← immagine schermata di benvenuto
├── icon-192.png            ← icona Android
├── icon-512.png            ← icona Android HD
├── icon-maskable-512.png   ← icona Android (variante mascherabile)
├── apple-touch-icon.png    ← icona iOS (Add to Home)
├── favicon-32.png          ← icona browser
└── favicon-16.png          ← icona browser piccola
```

Tutti i file devono stare nella stessa cartella, allo stesso livello.

---

## Come pubblicare su GitHub Pages (gratis)

### 1. Crea l'account GitHub (se non ce l'hai)
Vai su https://github.com → "Sign up". Scegli uno username — sarà parte dell'URL finale.

### 2. Crea un nuovo repository
- Dalla home di GitHub, in alto a destra: `+` → "New repository"
- **Repository name**: `task-john-dark` (o quello che vuoi — sarà parte dell'URL)
- **Public** (deve essere pubblico per usare GitHub Pages gratis)
- ✅ Spunta "Add a README file"
- Clicca "Create repository"

### 3. Carica i file
- Nel repo, clicca "Add file" → "Upload files"
- Trascina **tutti i file** dalla cartella `task-john-dark` (NON la cartella, i file uno per uno o selezionali tutti)
- In fondo, clicca "Commit changes"

### 4. Attiva GitHub Pages
- Nel repo, vai su "Settings" (in alto a destra)
- Dal menu di sinistra: "Pages"
- Sotto "Source": seleziona `Deploy from a branch`
- Branch: `main`, cartella: `/ (root)`, poi "Save"
- Aspetta 1-2 minuti

### 5. Apri il tuo link
GitHub ti darà un URL tipo:
```
https://TUO-USERNAME.github.io/task-john-dark/
```
Apri quello — è la tua app online.

---

## Come installarla sul telefono

### iPhone (Safari)
1. Apri il link su Safari (deve essere Safari, non Chrome)
2. Tocca il pulsante condividi in basso (quadrato con freccia su)
3. Scorri e tocca "Aggiungi a Home"
4. Conferma "Aggiungi"
5. L'icona del polpo apparirà sulla home come una app vera

### Android (Chrome)
1. Apri il link su Chrome
2. Tocca i tre puntini in alto a destra
3. "Installa app" (o "Aggiungi a schermata Home")
4. Conferma

Una volta installata, si apre a tutto schermo come app nativa, senza barra del browser.

---

## Aggiornamenti futuri

Quando vuoi modificare l'app:
1. Vai sul repo GitHub
2. Clicca sul file da modificare (es. `index.html`)
3. Tocca l'icona matita per editare
4. Salva ("Commit changes")
5. In 1-2 minuti la versione online si aggiorna automaticamente

Se vuoi sostituire l'immagine splash o l'icona, basta caricare un file con lo stesso nome (sostituisce il vecchio).

---

## I tuoi dati

I task vengono salvati nel **localStorage del browser/dispositivo**:
- Sul telefono → restano sul telefono
- Sul PC → restano sul PC
- NON sono sincronizzati tra dispositivi

Se vuoi sincronizzazione vera (cloud), serve un backend e diventa un altro progetto.

---

**Costo totale**: zero. GitHub Pages è gratis a vita per repository pubblici.
