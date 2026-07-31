# Kochwelt 🍳

Eine Rezept-Website rund ums Kochen und Backen – umgesetzt als statisches Frontend mit reinem **HTML und CSS**. Kein Framework, kein JavaScript, kein Backend.

## Funktionen

- Startseite mit Hero-Bereich, Rezeptvorschau und Info-Abschnitt
- Einzelne Rezeptseiten (Croissants, Kartoffel-Brokkoli-Auflauf, Pancakes, Nutella-Pancakes) mit Zutaten, Zeitangaben und Zubereitung
- Kontaktseite mit Formular-Layout
- Rechtliche Seiten: Impressum, Datenschutz und AGB
- Vollständig responsives Layout, optimiert bis hinunter zu 320px Breite
- Einschiebbares Burger-Menü auf Smartphones
- Inhaltsbereich zentriert mit maximaler Breite von 1440px

## Projektstruktur

```
Kochwelt/
├── index.html              # Startseite
├── css/
│   ├── style.css           # zentrales Stylesheet für alle Seiten
│   └── fonts.css           # Schriftarten
├── assets/
│   └── img/                # Bilder (Rezepte, Logo, Social-Icons)
└── pages/
    ├── bestoftheday.html   # Rezept des Tages (Croissants)
    ├── auflauf.html        # Kartoffel-Brokkoli-Auflauf
    ├── pancake.html        # Pfannkuchen
    ├── nutella-pancakes.html
    ├── kontakt.html        # Kontaktformular
    ├── impressum.html
    ├── datenschutz.html
    └── agb.html
```

## Responsive Verhalten

- Ab **1440px** Breite wächst der Inhalt nicht weiter, sondern bleibt zentriert
- Unter **615px** stapeln sich die Inhalte und die Navigation wird zum Burger-Menü
- Getestet und optimiert bis **320px** Breite (kein horizontales Scrollen)
