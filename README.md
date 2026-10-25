# Snackrummet

Responsiv svensk kontorssimulator med elva karaktärer, individuella SVG-avatarer och yrkesbadges.

## Kör

```sh
cd /workspace/BGP
python3 -m http.server 3000 --bind 0.0.0.0
```

Öppna index.html i webbläsaren eller använd port 3000 i din utvecklingsmiljö. Inga paket eller API-nycklar behövs.

## Repliker

Varje ordinarie karaktär har en egen bank med personligt skrivna tankar och skämt om jobb, intressen och kontorslivet. Dessa kan kombineras med karaktärens inledningar och avslut. Samma grundtanke återanvänds först när personens bank har gått ett helt varv. De senaste 100 fullständiga replikerna undviks där det finns alternativ. Minnet gäller aktuell sidvisning. Det är lokal textgenerering, ingen extern AI.

Ge någon ordet, starta hela gänget eller aktivera automatiskt snack. Egna personer sparas i webbläsarens localStorage och använder enklare mallar. Karaktärsdata och replikbanker finns i defaults och voices i index.html. Avatarerna är stiliserade illustrationer, inte porträtt av verkliga personer.
