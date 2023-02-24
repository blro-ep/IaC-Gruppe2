# Kontiniuierliches vs. onetime Konfigurationsmangagment

## Tools
- Ansible - Communtity Edition
- puppet - Community Edition
- Cloud-Init
- Kickstart by Redhat

## Fragen

### Können alle IaC-Tools Konfigurationen nach der Installationen anpassen?
- Ansible - Communtity Edition
    - Ja, working idempotent, agent less
- puppet - Community Edition
    - ja, agent auf host
- Cloud-Init
    - Nein
- Kickstart by Redhat
    - Nein, kann jedoch für Version upgrade verwendet werden.

### Gibt es Tools die nur für das einmalige ausführen gedacht sind?
- Ansible - Communtity Edition
    - nein
- puppet - Community Edition
    - nein
- Cloud-Init
    - ja
- Kickstart by Redhat
    - ja

### Was könnte das mit Idempotenz zu tun?
- Ein Task wird nur ausgeführt, wenn das Zielbild noch nicht existiert.

### Es gibt den push und pull Ansatz. Was versteht man unter diesen?
- push --> Tool sendet direkt Befehle an Zielsystem
- pull --> Tool holt Befehle vom Zentralsystem (z.B. Git)


# Deklarative vs. Imperative Sprachen?

## Fragen
### Wie kommunizieren Menschen im Alltag?


### Gibt es Programmiersprachen welche sowohl deklarativ wie auch imperativ gebraucht werden können?


### Kann in BASH deklarativ programmiert werden?


### Welcher Teil von SQL ist eine imperative Sprache?


### Warum werden einige Sprachen als imperativ und andere als deklarativ bezeichnet?


### Was sind die sind die Hauptunterschiede zwischen deklartivem und imperativen programmieren?
