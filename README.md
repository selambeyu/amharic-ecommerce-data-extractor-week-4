# Amharic E-commerce Data Extractor

This project extracts, preprocesses, and labels Amharic-language e-commerce data from Telegram channels for downstream NLP tasks such as Named Entity Recognition (NER).

## Features

- **Telegram Channel Scraping:** Uses Telethon to ingest messages, photos, and documents from specified Telegram channels.
- **Amharic Text Processing:** Tokenizes and normalizes Amharic text for further analysis.
- **Manual Labeling:** Provides a workflow for manually labeling entities in Amharic messages for NER.
- **Data Export:** Saves processed and labeled data in CSV and CoNLL formats.
