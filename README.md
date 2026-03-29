# ReCEL SDK

SDK Python per integrare ReCEL, un modello di linguaggio progettato per l'ascolto empatico e la connessione umana.

## Installazione

```bash
pip install recel-sdk
```

## Utilizzo rapido

```python
from recel import ReCEL

client = ReCEL()
risposta = client.chat("Ciao")
print(risposta)
```

## Parametri

- `max_tokens` (int, default 256): lunghezza massima della risposta (10‑2048)
- `style` (str, default "emphatic"): "emphatic" (empatico), "deep" (profondo) o "concise" (conciso)
- `temperature` (float, default 0.3): creatività (0.0 = deterministica, 1.0 = più varia)
