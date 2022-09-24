# Programmieren für Volos 2020

### Jupyter Lab starten, wenn es schon installiert ist

Im Finder / Datei-Explorer den richtigen Ordner finden ('/pfv') und 'in Terminal öffnen'.
Im Terminal ggf. noch mal überprüfen, ob alles richtig ist:

- `pwd` > sollte den richtigen Ordner ausgeben
- `ls -l` > listet die Dateien und Unterordner auf. Der Unterorder '/myvenv' muss da sein
- dann das virtuelle Environment starten (eine Art Box, in der nur die gerade benötigten Pakete in der richtigen Version drin sind):
  `source myvenv/bin/activate`, im Terminal sollte vorne (myvenv) vor der Kommandozeile auftauchen
- dann das Jupyter Lab starten mit `jupyter lab`
- im Terminal startet dann ein lokaler Server und ein Browserfenster öffnet sich atomatisch. Falls ihr das Lab lieber in einem anderen Browser nutzen wollt, scrollt ihr ggf. ein bisschen im Terminal zurück, dort ist ein solcher Link mit Sicherheitscode zu finden: http://localhost:8888/lab?token=60dae27ce5a5b755a681e7216c971fdddfddc537bd68cb25 (Das ist nur ein Beispiel, bei euch sieht der Token anders aus)
  Den könnt ihr in den Browser eurer Wahl kopieren. Meine Empfehlung: Chrome oder Firefox.

## Installation

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

`$ pip install jupyterlab`
`$ pip install pandas`
`$ pip install matplotlib`
`$ pip install openpyxl`
`$ pip install xlrd`
`$ pip install plotnine`

### 6. Jupyter lab starten

Wenn das Installieren geklappt hat, kannst du jetzt `jupyter lab` starten:

`$ jupyter lab`

### 7. Das erste Notebook öffnen

Es öffnet sich ein Browserfenster, Du siehst links eine Dateistruktur. Da klickst du bitte auf:

**01_jupyter_lab.ipynb**

Dann geht es in deinem Browser weiter. Das Terminal bitte offen lassen, denn dort läuft dein lokaler Server für das `Jupyter Lab` - so ähnlich wie gestern bei `runserver`.
