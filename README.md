

---

# Erstes KI-Projekt: Einkaufs- & Fahrzeuganalyse

Dieses Repository enthält zwei Jupyter-Notebooks zur Datenanalyse und Mustererkennung mit maschinellem Lernen.

---

## Projektstruktur

```
├── shopping_notebook.ipynb         # Einkaufsanalyse mit Apriori-Algorithmus
├── vehicules_notebook.ipynb        # Fahrzeuganalyse basierend auf Antriebstypen
├── vehicules_notebook - Kopie.ipynb # Backup des Fahrzeuganalyse-Notebooks
├── README.md                       # Projektdokumentation
```

---

## Einkaufsanalyse (shopping_notebook.ipynb)

Dieses Notebook verwendet den Apriori-Algorithmus zur Analyse von Einkaufsdaten.  
- **Datensatz**: `shopping.csv`  
- **Verwendete Bibliotheken**: `mlxtend`, `pandas`  
- **Ziel**: Erkennen häufig gekaufter Artikelkombinationen  

---

## Fahrzeuganalyse (vehicules_notebook.ipynb)

Dieses Notebook analysiert Fahrzeugdaten und filtert nur Fahrzeuge mit Front-, Heck- oder Allradantrieb.  
- **Datensatz**: `vehicles.csv`  
- **Verwendete Bibliotheken**: `pandas`  
- **Ziel**: Analyse von Fahrzeugen anhand ihres Antriebstyps  

---

## Installation & Nutzung

1. Notwendige Bibliotheken installieren:
   ```sh
   pip install pandas mlxtend notebook
   ```
   
2. Jupyter Notebook starten:
   ```sh
   jupyter notebook
   ```

3. Das gewünschte Notebook öffnen und ausführen.

---

## Lizenz

Dieses Projekt ist lizenzfrei
