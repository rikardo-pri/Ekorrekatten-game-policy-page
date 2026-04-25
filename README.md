# GitHub Pages – Integritetspolicy

Den här mappen publiceras via **GitHub Pages** och innehåller den publika integritetspolicyn för Göteborgsbörsen. URL:en används som "Privacy Policy URL" i Google Play Console och App Store Connect.

## Aktivera GitHub Pages

1. Pusha repot till GitHub.
2. Gå till **Settings → Pages** i ditt GitHub-repo.
3. Under **Source**, välj:
   - Branch: `main` (eller din standardbransch)
   - Folder: `/docs`
4. Klicka **Save**.

Efter någon minut är policyn live på:

```
https://<ditt-användarnamn>.github.io/<repo-namn>/
```

## Filer

- `index.html` – Integritetspolicyn (SV + EN). Servas på rot-URL:en.
- `.nojekyll` – Stänger av Jekylls bearbetning så att alla filer servas oförändrade.

## Uppdatera policyn

Redigera `docs/index.html` och uppdatera datumet under "Senast uppdaterad" / "Last updated". Pusha — GitHub Pages bygger om automatiskt.

> Den ursprungliga `public/privacy-policy.html` ligger kvar och buntas med själva spelet. Håll de två versionerna i synk.
