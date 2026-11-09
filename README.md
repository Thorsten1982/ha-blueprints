# Home Assistant Blueprints

Eine Sammlung meiner optimierten Blueprints für Home Assistant.

---

## 1. Dynamische Lüftung (AH-basiert, Optimiert v2)

Berechnet die absolute Feuchtigkeit (AH) nach der Magnus-Formel und empfiehlt Stoßlüften, wenn die Außenluft trockener ist als die Innenluft.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FThorsten1982%2Fha-blueprints%2Fblob%2Fmain%2Fdynamic_ventilation_optimized.yaml)

* **Features:** Hysterese-Schwellenwerte, anwesenheits- und zeitgesteuert, automatischer Helfer-Reset bei geschlossenem Fenster, moderne `action:`-Syntax.
* **Credits:** Basiert ursprünglich auf der Blueprint von `@lukinho9821` (Home Assistant Community) sowie Weiterentwicklungen von `@jrfigura`.

---

## 2. PM-Lichtsteuerung mit manuellem Override

Lichtsteuerung über Präsenzmelder mit Unterstützung für manuelle Overrides.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FThorsten1982%2Fha-blueprints%2Fblob%2Fmain%2FPM-Lichtsteuerung%2520mit%2520manuellem%2520Override.yaml)

*(Hinweis: Passe den Dateinamen im Import-Link oben an den exakten Dateinamen deines Präsenzmelder-Blueprints an).*
