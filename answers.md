# Antworten zu Git Branches

## 1. Was ist der Unterschied zwischen Working Directory, Staging Area und Repository?

- Working Directory: Hier bearbeite ich meine Dateien.
- Staging Area: Hier bereite ich Änderungen für den Commit vor.
- Repository: Hier werden die Commits dauerhaft gespeichert.

## 2. Woran erkennst du, ob ein Merge Fast-Forward war?

Beim Merge zeigt Git `Fast-forward` an.

## 3. Warum kann git merge --ff-only manchmal fehlschlagen?

Wenn auf beiden Branches neue Commits gemacht wurden. Dann kann Git keinen einfachen Fast-Forward durchführen.

## 4. Was ist der Vorteil, Änderungen zuerst auf einem Branch wie dev zu machen?

Man kann Änderungen testen, ohne den `main` Branch direkt zu verändern.

## 5. Mit welchem Befehl siehst du den aktuellen Branch?

```
git branch
```

Der aktuelle Branch ist mit einem `*` markiert.

## 6. Mit welchen Befehlen machst du Änderungen sichtbar und dauerhaft?

Änderungen für den Commit vorbereiten:

```
git add .
```

Änderungen dauerhaft speichern:

```
git commit -m "Beschreibung"
```