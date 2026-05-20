# ECCE AI Hub Uganda — Gentle Buttons Build

This build reduces the size and visual weight of the two main tool buttons:

- Is My Centre Ready?
- Is This Centre Safe?

They now match the smaller badge-style scale of the ECCE Digital Support Tool badge.

It keeps:
- ECCE AskDesk
- Is My Centre Ready?
- Is This Centre Safe for My Child?
- MoES and theme logos
- Working page buttons/interactions
- Non-sticky/slimmer header

Render settings:

Build Command:
```bash
python -m pip install --upgrade pip setuptools wheel && pip install -r requirements.txt
```

Start Command:
```bash
python -m uvicorn app:app --host 0.0.0.0 --port $PORT
```

Leave Pre-deploy Command empty.
Leave Root Directory empty.
