# GitHub Pages – Integritetspolicy

Publika integritetspolicyer (SV + EN) för spelen. URL:erna används som **Privacy Policy URL** i Google Play Console och App Store Connect.

## Live-URL:er

Bas-URL (GitHub Pages, mapp `/docs`):

```
https://rikardo-pri.github.io/Ekorrekatten-game-policy-page/
```

| Spel | Fil | Privacy Policy URL |
| --- | --- | --- |
| Översikt | `docs/index.html` | https://rikardo-pri.github.io/Ekorrekatten-game-policy-page/ |
| **Göteborgstegen** | `docs/goteborgstegen.html` | https://rikardo-pri.github.io/Ekorrekatten-game-policy-page/goteborgstegen.html |
| **Göteborgsbörsen** | `docs/goteborgsborsen.html` | https://rikardo-pri.github.io/Ekorrekatten-game-policy-page/goteborgsborsen.html |
| **Londonbörsen** | `docs/londonborsen.html` | https://rikardo-pri.github.io/Ekorrekatten-game-policy-page/londonborsen.html |

Gemensam stil: `docs/policy.css`

## Förhandsgranska lokalt i Visual Studio Code / Cursor

1. Öppna mappen `docs/` (eller en HTML-fil under `docs/`).
2. Installera tillägget **Live Preview** (Microsoft, id: `ms-vscode.live-server`) *eller* **Live Server** (Ritwick Dey).
3. Högerklicka på t.ex. `docs/index.html` → **Show Preview** (Live Preview) eller **Open with Live Server**.
4. Sidan öppnas i en inbyggd förhandsvisning eller i webbläsaren. Länkar mellan spelen fungerar så länge du förhandsvisar från `docs/`.

**Snabbkommando (Live Preview):** öppna HTML-filen och kör kommandot `Live Preview: Show Preview` från Command Palette (`Ctrl+Shift+P`).

**Utan tillägg:** högerklicka på HTML-filen → **Reveal in File Explorer**, öppna filen i webbläsaren. CSS laddas via relativ sökväg (`./policy.css`) så länge filerna ligger kvar i samma mapp.

## Aktivera GitHub Pages

1. Pusha till GitHub.
2. **Settings → Pages** i repot.
3. **Source:** branch `main`, folder `/docs` → **Save**.

## Uppdatera en policy

Redigera rätt HTML-fil under `docs/` och uppdatera datumet under "Senast uppdaterad" / "Last updated". Pusha — GitHub Pages bygger om automatiskt.
