# Sparse Transfer Learning auf Transformer

Dieses Repository enthält den Code und die Experimente im Rahmen meiner Bachelorarbeit zum Thema **Sparse Transfer Learning auf Transformer-Architekturen**.



## Überblick

Ziel der Arbeit ist die Untersuchung der Effektivität von Sparse Transfer Learning auf  Transformer-Modelle im Bereich des Natural Language Processing (NLP). Es wurden drei typische Architekturtypen evaluiert:

- **Encoder-only** (`/encoder`, BERT base uncased)
- **Decoder-only** (`/decoder`, GPT-2)
- **Encoder-Decoder** (`/encoder-decoder`, T5-Small)


## Anforderungen

Alle benötigten Pakete können mit folgendem Befehle installiert werden:

```bash
pip install -r requirements.txt
```

**Hinweis**: Falls es beim Installieren oder Ausführen Probleme mit torch gibt, kann folgender Befehl verwendet werden:

```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu126
```