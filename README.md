# Rilevamento della plastica nelle rive

Questo repository contiene il codice e le risorse necessarie utilizzate per sviluppare un sistema automatizzato per rilevare la presenza di plastica lungo le rive dei fiumi, dei laghi e delle spiagge utilizzando tecniche di visione artificiale.
</br></br>
Il progetto è stato sviluppato nell'ambito del progetto finale del corso di Visione e Percezione dagli studenti:
- **Antonella Bonelli** (68791)
- **Simona Calocero** (68395)
- **Marco Rosa** (60315)
</br></br>
# Obiettivo
L'obiettivo principale di questo progetto è sviluppare un algoritmo di visione artificiale in grado di identificare e classificare gli oggetti di rifiuto presenti nelle immagini acquisite lungo le rive dei fiumi. Gli oggetti di rifiuto sono suddivisi in quattro categorie: **bottiglia di plastica**, **sacchetto di plastica**, **altro rifiuto di plastica** o **rifiuto non plastico**.
</br></br>

## Notebooks

I notebook seguenti sono disponibili in questo repository:

|  |  |
| ----------- | ----------- |
| [Notebook 1: Explore Dataset](https://github.com/rosamarco/plastic_in_river_detector/blob/main/explore_dataset.ipynb)      | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rosamarco/plastic_in_river_detector/blob/main/explore_dataset.ipynb)       |
| [Notebook 2: Nome del notebook](URL_DEL_NOTEBOOK2)  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](URL_DEL_NOTEBOOK2) |



Puoi fare clic sul badge ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) accanto a ciascun notebook per aprirlo direttamente su Google Colab e interagire con il codice.
</br></br>
# Installazione
1. Assicurarsi di avere [**conda**](https://docs.conda.io/en/latest/miniconda.html) installato nel proprio sistema.

1. Clonare il repository sul proprio computer utilizzando il comando:
    ```bash
    git clone https://github.com/rosamarco/plastic_in_river_detector.git
    ```

1. Navigare nella directory del repository clonato:
    ```bash
    cd plastic_in_river_detector
    ```

1. Creare l'ambiente virtuale conda utilizzando il file environment.yml incluso nel repository:
    ```bash
    conda env create --file environment.yml
    ```
1. Attivare l'ambiente virtuale conda appena creato:
    ```bash
    conda activate plastic_in_river
    ```