# SecureTasks

Turvallinen tehtävienhallinta-API + web-käyttöliittymä. Henkilökohtainen oppimisprojekti,
jonka tavoitteena on oppia backend-kehitystä, tietokantoja, kontitusta ja
tietoturva-ajattelua käytännössä.

## Kansiorakenne

```
SecureTasks/
├── backend/     # FastAPI-sovellus, tietokantamallit, API-endpointit
├── frontend/    # Yksinkertainen HTML/JS (tai React) -käyttöliittymä
├── docs/        # Suunnitelmat, muistiinpanot, tietoturvalöydökset
│   └── CHECKLIST.md   <- viikkotason tehtävälista, avaa tämä ensin
└── README.md
```

## Aloitus

1. Avaa `docs/CHECKLIST.md` ja aloita Viikko 1:stä.
2. Kun backend alkaa muotoutua, kirjaa koodi `backend/`-kansioon.
3. Kun teet käyttöliittymän, se menee `frontend/`-kansioon.
4. Kirjaa kaikki tietoturvalöydökset ja korjaukset omaan tiedostoon
   `docs/SECURITY_NOTES.md` (luo se viikolla 8, kun aloitat tietoturvakierroksen).

## Teknologiat (suunniteltu)

- Backend: Python + FastAPI + SQLAlchemy
- Tietokanta: PostgreSQL
- Kontitus: Docker + docker-compose
- Autentikointi: JWT, salasanat hashattu (bcrypt/argon2)
- CI: GitHub Actions
