# SecureTasks – 12 viikon tarkistuslista

Tavoite: turvallinen tehtävienhallinta-API + web-käyttöliittymä. 2 sessiota/viikko, n. 1–1,5h/sessio.
Jos viikko jää kesken kurssikiireiden takia, siirrä koko suunnitelmaa viikolla eteenpäin.

## Viikko 1 – Työkalut pystyyn
- [] S1: Asenna Python, Git, VS Code, PostgreSQL, Docker
- [x] S1: Luo GitHub-tili ja tyhjä repo
- [] S2: Harjoittele Git-peruskomennot (add/commit/push/branch) testitiedostolla
- [x] S2: Luo FastAPI-projektin runko ja virtuaaliympäristö

## Viikko 2 – Ensimmäinen toimiva pala
- [x] S1: Tee `/health`-endpoint, testaa selaimessa/curl:lla
- [ ] S2: Suunnittele tietokantamalli (käyttäjät + tehtävät) paperille
- [ ] S2: Asenna SQLAlchemy ja yhdistä PostgreSQL:ään

## Viikko 3 – Käyttäjät
- [ ] S1: Toteuta käyttäjätaulu ja rekisteröinti-endpoint
- [ ] S2: Lisää salasanan hashaus (bcrypt/argon2) rekisteröintiin

## Viikko 4 – Kirjautuminen
- [ ] S1: Kirjautumis-endpoint + JWT-tokenin generointi
- [ ] S2: Suojaa muut endpointit vaatimaan kelvollinen JWT

## Viikko 5 – Tehtävät (CRUD)
- [ ] S1: Tehtävien luonti ja listaus -endpointit
- [ ] S2: Muokkaus ja poisto -endpointit, testaa Postmanilla

## Viikko 6 – Kontitus
- [ ] S1: Kirjoita Dockerfile backendille
- [ ] S2: docker-compose.yml (backend + tietokanta), testaa yhdellä komennolla

## Viikko 7 – Käyttöliittymä
- [ ] S1: HTML+JS-lomake rekisteröintiin/kirjautumiseen
- [ ] S2: Tehtävälistanäkymä (näytä, lisää, poista)

## Viikko 8 – Tietoturva alkaa
- [ ] S1: Käy läpi OWASP Top 10, mieti mitkä koskevat omaa sovellusta
- [ ] S2: Testaa SQL-injektiota hakuihin/kirjautumiseen, korjaa jos löytyy

## Viikko 9 – Auktorisointi
- [ ] S1: Testaa IDOR (pääseekö käyttäjä A toisen tehtäviin ID:tä vaihtamalla), korjaa
- [ ] S2: Tarkista lokitus – ei salasanoja/tokeneita lokeihin

## Viikko 10 – Viimeiset suojaukset
- [ ] S1: Rate limiting kirjautumiseen (esim. slowapi)
- [ ] S2: Dokumentoi löydöt ja korjaukset README:n tietoturva-osioon

## Viikko 11 – Dokumentointi ja automaatio
- [ ] S1: Kirjoita kunnollinen README (mitä sovellus tekee, arkkitehtuuri, asennusohjeet)
- [ ] S2: GitHub Actions -pipeline joka ajaa perustestit

## Viikko 12 – Viimeistely
- [ ] S1: Siivoa koodi, varmista että `docker-compose up` toimii puhtaalta pöydältä
- [ ] S2: Julkaise projekti (LinkedIn, CV), reflektoi mitä opit

## Taustalla koko ajan
- [ ] 1 TryHackMe-tehtävä/viikko (Pre Security -polku), esim. sunnuntai-iltana
