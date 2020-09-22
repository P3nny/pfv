# Eigenes Notebook bei Github veröffentlichen

- Terminal öffnen

- Bist Du im richtigen Ordner?
  Sorge dafür, dass Du an einem Ort bist, den Du wiederfindest, zum Beispiel in deinem 'Desktop'-Ordner

  `pwd`, dann vielleicht `cd Desktop` oder `cd ..`

- Neues repo bei github anlegen

  Den https-Link deines Repos kopieren und hier statt meinem Beispiel einfügen:

  `git clone https://github.com/P3nny/pfv_neu.git`

- In das Verzeichnis wechseln

  `cd mein_projekt_name`

- Virtual environment anlegen

  `python3 -m venv myvenv`

- Virtual environment starten

  `source myvenv/bin/activate`

  Windows: `myvenv\Scripts\activate`

- .gitignore Datei anlegen
  Den Inhalt kannst du hier kopieren:

  https://github.com/P3nny/pfv_neu/blob/master/.gitignore

- requirements.txt anlegen
  Den Inhalt kannst du hier kopieren:
  https://github.com/P3nny/pfv_neu/blob/master/requirements.txt

  Dann:

  `pip install -r requirements.txt`

  Du kannst im Terminal auch einzelne Pakete installieren mit:

  `pip install super_paket`

- Jupyter lab starten
  `jupyter lab`

- Datenanalye durchführen
  Hilfe mit pandas gibt es hier:
  https://docs.google.com/spreadsheets/d/1fk8gdO9AaCuB9PhiV2aEHEdb5XlRoTSlolw0a2HromU/edit?usp=sharing

- Datawrapper Chart anlegen
  https://www.datawrapper.de/

- Ergebnisse in Markdown in Jupyter Notebook aufschreiben
  https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

- Datawrapper Chart als iFrame einbinden

  `import IPython`
  
  `IPython.display.IFrame('https://datawrapper.dwcdn.net/IJwst/4/', width='600', height='750')`

- Ggf. neu installierte, eigene Pakete in requirements.txt schreiben

  `pip freeze -r requirements.txt`

- Ergebnisse sichern als commit

  `git add --all .`

  `git commit -m "First data analysis"`

- Code pushen

  `git push`
