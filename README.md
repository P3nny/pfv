# Programmieren für Volos 2020

### 1. Repo clonen

Du öffnest auf deinem Computer ein Terminal. Stelle sicher, dass du an einer Stelle bist, an der du einen Ordner anlegen willst, zum Beispiel auf dem Desktop.
Gib das hier in dein Terminal ein:

   `$ git clone https://github.com/P3nny/pfv.git`

Dieser Befehl lädt die Dateien, die wir für den Daten-Tag brauchen, von Github in ein neues Verzeichnis herunter.

### 2. In das Verzeichnis wechseln

Wechsele in deinem Terminal in das neue Verzeichnis:

   `$ cd pfv`

### 3. Virtuelles Environment aufsetzen

In deinem neuem Verzeichnis legst du bitte ein neues virtuelles Environment an, das nennst du wieder `myvenv`, wie gestern:

   - MacOS/Linux: `$ python3 -m venv myvenv`
   - Windows: `> python -m venv myvenv`

### 4. Virtuelles Environment aktivieren

Dann aktivierst du das virtual Environment:

   - MacOS/Linux: `$ source myvenv/bin/activate`
   - Windows (git bash): `$ ./myvenv/Scripts/activate`
   - Windows (Powershell): `> myvenv\Scripts\Activate.ps1`
   - Windows (CMD/Eingabeaufforderung): `> myvenv\Scripts\activate.bat`

### 5. Benötigte Pakete installieren

Mit diesem Befehl installierst du benötigte Python-Pakete auf deinem Rechner:

`$ pip install -r requirements.txt`

### 6. Jupyter lab starten

Wenn das Installieren geklappt hat, kannst du jetzt `jupyter lab` starten:

   `$ jupyter lab`

### 7. Das erste Notebook öffnen

Es öffnet sich ein Browserfenster, Du siehst links eine Dateistruktur. Da klickst du bitte auf:

   **01_jupyter_lab.ipynb**

Dann geht es in deinem Browser weiter. Das Terminal bitte offen lassen, denn dort läuft dein lokaler Server für das `Jupyter Lab` - so ähnlich wie gestern bei `runserver`.
