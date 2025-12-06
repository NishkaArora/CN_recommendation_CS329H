# CN_recommendation_CS329H
This is my submission to the CS329H Final Project

## Simulated Data (Main Submission)

In order to run the code, opening the colab notebook and running it is enough since the data is simulated. 
Runtime: The expected runtime is 2-5 minutes on a CPU.

## True CN Data (for the note in the appendix)

I hosted the data in a public Google Drive folder:
- **Data link:** [data link](https://drive.google.com/drive/folders/1iGvoPSLKPSOZzmtK-fNghasHagu0MZiL?usp=share_link)

The folder contains:
- `notes_*.tsv`: note metadata
- `ratings_*.tsv`: user-note rating data
- 'note_status_*.tsv': history of note statuses

You can either:
1. Add the folder to your own Drive (`Add shortcut to Drive`), or
2. Download locally and re-upload into your own `MyDrive`.

For the Colab notebook we assume the data lives at: ```/content/drive/MyDrive/CN_recommendation_CS329H/``` 
(but the path can be changed in DATA_DIR in the first block of the notebook if need be)

Runtime: The file runs in 10 mins with the T4 GPU.
