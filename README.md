# cState Seite v5.6.1b

Dies ist das Standardverzeichnis/Ordner für die cState-Statusseite.

* Link zum Beispiel-Site-Repository (Sie sind hier): https://github.com/cstate/example
* Hauptrepository für den cState-Quellcode: https://github.com/cstate/cstate

## Aktualisieren Sie? Verwenden Sie diese Befehle

Laden Sie Ihre Seite mit allen Verzeichnissen herunter. `git clone --recursive <Ihr Repo-Link kommt hier>`

Aktualisieren Sie das cState-Theme-Submodul. `git submodule foreach git pull origin master`

Geben Sie im übergeordneten Verzeichnis `hugo serve` ein. Überprüfen Sie, ob alles funktioniert.

Führen Sie dann `git add -A; git commit -m "Update cState"; git push origin <Branch, wahrscheinlich main oder master>` aus. Ihre Statusseite ist jetzt aktualisiert und hochgeladen.


## Für Betreuer (wahrscheinlich nicht für Sie)

Betreuer müssen sowohl cstate/cstate als auch cstate/example für jede neue Version aktualisieren.

Laden Sie dieses Repository mit allen Verzeichnissen herunter. `git clone --recursive -b master https://github.com/cstate/example.git`

Fügen Sie Ihre Änderungen aus dem Ordner exampleSite von cstate/cstate hinzu.

Aktualisieren Sie das cState-Theme-Submodul. `git submodule foreach git pull origin master`

Dann pushen Sie `git add -A; git commit -m "Update cState vX.X.X"; git push origin master`.

## Lizenz

MIT © Mantas Vilčinskas
