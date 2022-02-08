Dev Changelog

- [08.02.2022](#08.02.2022)
- [07.02.2022](#07.02.2022)
- [03.02.2022](#03.02.2022)

# 08.02.2022

# ► Phone Update
    - Eigentlich nichts neues nicht mal die known bugs wurden gefixt.. 

# ► Autos
    - Alle Autos haben nun Preise und sind in der richtige Kategorie
    - Golf GTI MK7 Replaced
    - Golf GTI 7.5 gegen Scirocco Replaced

# ► Bikes
    - neues Bike set was wir uns anschauen sollten https://www.gta5-mods.com/vehicles/zbike-add-on-55-bikes-compilation-pack


# 07.02.2022

# ► Neue CarHud
    - Auf vielfachen wunsch habe ich die neue (alt bekannte) carhud hinzugefuegt
    - Bei Unfaellen fliegt man nun nicht mehr ganz so schnell aus die Karre

# ► Fahrzeug Shops
    - Rechtschreibung / Uebersetzung
    - € vs $ getauscht

# ► Autos
    - Autos der Kategorie Normal in den richtigen Shop geschoben und Preise angepasst
    - Alle fertig gestellten Fahrzeuge von Jack auf den DEV server migriert 

# ► PlasmarKart
    - Umlaute
    - Bugfix im Startscript

# 03.02.2022
# ►  Neue Garagen System
    - Polizei hat nun einen eignen Abschlepphof um Fahrzeuge zu konfiszieren
    - Garagen System kann nun RGB Farben Speichern
    - Haeuser die man Kauft haben nun eine dazugehoerige Garage
    - Converter fuer alte fahrzeuge geschrieben (damit brauchen wir erstmal kein db reset)

# ►  Neue Fahrzeug Shops
    - Trucks hinzugefuegt
    - Bikes hinzugefuegt
    - Luxus wagen hinzugefuegt
    - Uebersetzung vorran getrieben
    - Alle Custom cars sind nun im Shop
    - Anticheat Protection

# ►  BaberShop
    - Bugfix wenn man eine Maske/helm an hat wird es nun automatisch ausgezogen

# ►  Klamotten Laeden
    - Vorbereitung auf neue Jobsystem Polizei / Ambulance / Mech haben ihre eignen Laeden jetzt (wird aber erst mit dem neuen Job system freigeschaltet)
    - Bugfixes und Performance Updates 

# ►  Auto Tracker update
    - Performance
    - SQL inject bugfixes

# ►  Plasmakart 
    - Koennen nun mehr als 4 runden fahren
    - Anticheat bugfix (speed / wall hacks)
    - Bugfix XSound-Problem zu beheben (einige Spieler hörten Geräusche am anderen Ende der Karte).
    - Du kannst jetzt die aktuelle Session löschen. (bsp Ein spieler ist disconnected und du kannst das Rennen nicht zu ende Fahren.)
    - Performance / SQL Optimiert

# ►  New Jobsystem
    - Ist bereits auf dem DEV server
        - Mehrere Artikel verkaufen in der Einstellungsschaltfläche korrigiert, die umgekehrt funktionierte
        - Möglichkeit hinzugefügt, alle Fahrzeuge beim Neustart des Skripts zu parken
        – DeleteVehicle native mit der ESX.Game.DeleteVehicle-Methode bearbeitet, um externe Integrationen zu ermöglichen
        - In Prozess- und Erntemarker wurde die Möglichkeit hinzugefügt, einen Mindestbetrag für das Konto zu definieren, um den Marker zu verwenden
        - Temporäre Fahrzeuge sollten nicht mehr despawnen, wenn der Spieler den Server verlässt
        - Verbesserte Rückrufprüfungen, die helfen, Probleme zu identifizieren, die durch bearbeitete Frameworks verursacht werden
        - Alle Rückrufe aus der Datei esx_callbacks.lua in relative Dateien verschoben
        - Neuer Export für Fahrzeugbeschlagnahmung hinzugefügt (neue Polizei Job system)
        - Ereignis hinzugefügt, um den Dienst von externen Skripten umzuschalten (neue Polizei / Medic / Mechaniker jobs)
        - Jetzt wird das Aktionsmenü blockiert, wenn der Spieler mit Handschellen gefesselt ist 
        - Export hinzugefügt, um Suchaktionen zu ersetzen
  
# ► Drogen System Update
    - Speed farming ist nun nicht mehr möglich
    - Neue Exports um bsp eigne externe verhalten scripte hinzuzufuegen.

# ► DoorLock System
    - Schiebe Tueren sollten nun gefixt sein.
    - Schloss system fuers neue Job System bereits angepasst

# ► Haeuser
     - Haeuser werden nur noch angezeigt die bei dir dran sind, verhaelt sich genauso wie das Tankstellen system.
     - TS probleme behoben man sollte nun sein nachbar nicht mehr hören

# ►  Komplett neues Tuning system Implementiert
    - Es ist viel dynamischer
    - Es liest aus den Script datein was wirklich getuned werden kann und das zeigt er auch (funxt nur bei tuning teilen nicht bei farben zum bsp)
