# ruoqu-sivut

Ruoqun verkkosivut (ruoqu.fi), julkaistaan GitHub Pagesilla.

Älä muokkaa HTML-tiedostoja käsin: ne rakennetaan sovelluksen yksityisestä reposta komennolla
`python3 tyokalut/vie_sivut.py ../ruoqu-sivut --asiakirjat --laaja` (laaja sivusto julkaistu perustajan hyväksynnällä 21.11.2026).

Sivustolla ei ole suoritettavia skriptejä, ulkoisia fontteja, evästeitä eikä analytiikkaa.

Julkaisu: Settings → Pages → Deploy from a branch (main, /). Oma verkkotunnus ruoqu.fi:
Zonerin DNS:ään A-tietueet `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
ja CNAME `www` → ristoiisakki.github.io. Sitten Pagesissa Custom domain = ruoqu.fi ja Enforce HTTPS.
Verkkotunnus vahvistetaan GitHubin TXT-tietueella (Settings → Pages → Verified domains).
