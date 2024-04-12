# RagaGEN

# Harmonizing Tradition and Technology: Fine-Tuning MusicGen for Authentic Raga Melody Generation
### ISMIR2024 Official paper submission

## Objective
Investigate the integration of traditional Indian Raga music with modern AI techniques by fine-tuning the MusicGen model for Raga melody generation.

## Gap in Research
Identified a significant gap in the application of AI for Raga melody generation, particularly with autoregressive language models like MusicGen.

## Dataset
Curated a dataset of 20 singing voices in Jog Raga, converted to MIDI format for input into GPT-4, and subsequently transformed into WAV files for fine-tuning with MusicGen.

## Methodology
Involved segmenting audio into 30-second chunks for resampling and normalization, extracting features like genre and mood, and using Librosa to detect key and BPM. Metadata for each clip was stored in a JSONL file.

## MusicGen Fine-Tuning Process
Utilized the Dora framework with specified hyperparameters for training the MusicGen model.

## Results
Achieved a 96% adherence to traditional patterns and structures in the generated Raga melodies.

### Composed sample track
The AI-generated melodies were used to compose an instrumental track featuring violin, cello, santoor, and piano, available on SoundCloud.

```
https://on.soundcloud.com/fS4WPNsa38iNhjNj9 
```

## Raga Fine-tuned MusicGen Inference
This repository contains a Jupyter Notebook designed for generating Raga melodies using a fine-tuned MusicGen model. The notebook is intended to be run on Google Colab and requires access to a Google Drive containing the fine-tuned MusicGen checkpoint.

To use the inference notebook to generate song:

- Open the notebook in Google Colab.
- Mount your Google Drive to provide access to the fine-tuned MusicGen checkpoint.
- Follow the instructions within the inference notebook to load the MusicGen model and generate Raga melodies using textual prompts.
- The generated audio can be played directly in the notebook and saved to your Google Drive or local machine for further use.
