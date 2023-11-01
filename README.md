# Rilevamento della plastica nelle rive

Questo repository contiene il codice e le risorse necessarie utilizzate per sviluppare un sistema automatizzato per rilevare la presenza di plastica lungo le rive dei fiumi, dei laghi e delle spiagge utilizzando tecniche di visione artificiale.
</br>
Il progetto è stato sviluppato nell'ambito del progetto finale del corso di Visione e Percezione dagli studenti:
- **Antonella Bonelli** (68791)
- **Simona Calocero** (68395)
- **Marco Rosa** (60315)
</br>
### Obiettivo
L'obiettivo principale di questo progetto è lo sviluppo di un software che tramite tecniche di visione artificiale permetta di identificare e classificare gli oggetti di rifiuto presenti in immagini e video acquisite lungo le rive dei fiumi.</br>
Per il raggiungimento degli obiettivi sono stati eseguiti i seguenti passi:

1. Ricerca, aggregazione ed adeguamento di dati provenienti da fonti diverse
1. Addestramento di un modello di object detection
1. Utilizzo e valutazione delle performance del modello
</br>

### Tecnologie utilizzate
1. Python 3
1. YOLOv8
1. Google Colab

## Esecuzione Notebook

I notebook sono stati interamente sviluppati sulla piattaforma Google Colab. I file relativi al training e all'esecuzione del modello sono reperibili nella seguente cartella condivisa [![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1FuXaQC4JHdcJBVd9mniK8hEK6TpIsK8A)

|  |  |
| ----------- | ----------- |
| [YOLOv8 Plastic in River Detector](https://github.com/rosamarco/plastic_in_river_detector/blob/main/yolov8_plastic_in_river_detector.ipynb)      | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rosamarco/plastic_in_river_detector/blob/main/yolov8_plastic_in_river_detector.ipynb) |
| [<sup>(*)</sup>  YOLOv4 Plastic in River Detector](URL_DEL_NOTEBOOK2)  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](URL_DEL_NOTEBOOK2) |

⁽*⁾ prima implementazione, successivamente usata come baseline per valutare le performance di v8