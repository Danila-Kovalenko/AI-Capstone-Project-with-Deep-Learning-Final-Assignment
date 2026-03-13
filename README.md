# AI Capstone Project mit Deep Learning

Dieses Repository enthält die Notebooks und Exportdateien der Abschlussaufgabe aus dem IBM/Cognitive Class Deep-Learning-Kontext. Inhaltlich geht es um **Bildklassifikation von Betonoberflächen** (z. B. „Crack“ vs. „No Crack“) mit klassischen Workflows zur Datenvorbereitung sowie mit **vortrainierten CNN-Modellen**.

## Projektüberblick

Das Projekt ist in mehrere praktische Schritte unterteilt:

- **Daten laden und visualisieren** (erste Exploration des Bilddatensatzes)
- **Datenaufbereitung und DataLoader** für Trainings-, Validierungs- und Test-Pipelines
- **Training mit vortrainierten Modellen**
  - PyTorch: ResNet-basierte Klassifikation (u. a. ResNet18)
  - Keras: Vergleich von VGG16 und ResNet50
- **Modellvergleich und Auswertung** anhand von Klassifikationsmetriken
- **Analyse von Fehlklassifikationen** zur qualitativen Bewertung der Modelle

## Repository-Struktur

- `DL0321EN-1-1-Loading-Data-py-v1.0.ipynb` – Daten laden und erste Inspektion
- `DL0321EN-2-1-Data-Preparation-py-v1.0.ipynb` – Datenaufbereitung
- `DL0321EN-3-1-Pretrained-Models-py-v1.0.ipynb` – vortrainierte Modelle mit Keras
- `DL0321EN-4-1-Comparing-Models-py-v1.0.ipynb` – Modellvergleich (u. a. VGG16 vs. ResNet50)
- `1.0_load_and_display_data.ipynb` bis `4.1_resnet18_PyTorch.ipynb` – PyTorch-orientierte Notebook-Reihe
- `Final_Assignment_Keras.html` und `Final_Assignment_PyTorch.html` – exportierte HTML-Versionen der Abschlussaufgaben

## Technologiestack

- Python (Jupyter Notebooks)
- PyTorch / torchvision
- Keras / TensorFlow
- NumPy, Matplotlib, PIL

## Nutzung

1. Repository klonen
2. Abhängigkeiten in einer virtuellen Umgebung installieren
3. Jupyter starten und die Notebooks schrittweise ausführen

Beispiel:

```bash
git clone <repo-url>
cd AI-Capstone-Project-with-Deep-Learning-Final-Assignment
jupyter notebook
```

> Hinweis: Einige Notebooks laden Datensätze direkt per URL (z. B. `concrete_data_week4.zip`) und erwarten eine passende Verzeichnisstruktur (`train`, `valid`, `test`).

## Ziel des Projekts

Ziel ist es, den vollständigen End-to-End-Prozess eines Computer-Vision-Projekts nachzuvollziehen: von der Datenvorbereitung über Transfer Learning bis hin zur vergleichenden Bewertung mehrerer Modelle für eine robuste Bildklassifikation.
