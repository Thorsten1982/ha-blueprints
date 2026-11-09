# Home Assistant Blueprints

Eine Sammlung meiner optimierten Blueprints für Home Assistant.

---

## 1. Dynamische Lüftung (AH-basiert, Optimiert v2)

Berechnet die absolute Feuchtigkeit (AH) nach der Magnus-Formel und empfiehlt Stoßlüften, wenn die Außenluft trockener ist als die Innenluft.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FThorsten1982%2Fha-blueprints%2Fblob%2Fmain%2Fdynamic_ventilation_optimized.yaml)

* **Features:** Hysterese-Schwellenwerte (Öffnen/Schließen), anwesenheits- und zeitgesteuert, Kälteschutz, automatischer Helfer-Reset bei geschlossenem Fenster sowie moderne `action:`-Syntax (HA 2024.8+).
* **Credits:** Basiert ursprünglich auf der Blueprint von `@lukinho9821` (Home Assistant Community) sowie Weiterentwicklungen von `@jrfigura`.

---

## 2. Präsenzmelder-Lichtsteuerung mit manuellem Override (V10)

Steuert die Beleuchtung präsenzabhängig und bietet eine zuverlässige Manuell-Sperre (Override) bei Betätigung von Wandschaltern.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FThorsten1982%2Fha-blueprints%2Fblob%2Fmain%2Fpm_light_control.yaml)

* **Features:** Robustes Override-Handling über Zeit-Korrelation (löst Probleme mit fehlenden Context-IDs), "Override Lock" bei
