# BrandenBeef One-Pager

Moderner One-Pager fuer die Direktvermarktung von BrandenBeef.

## Logo einbinden

Lege dein Logo als Datei unter folgendem Pfad ab:

`assets/logo.png`

Falls keine Datei vorhanden ist, wird automatisch ein Text-Fallback angezeigt.

Lege das Foto fuer den Qualitaets-Abschnitt unter folgendem Pfad ab:

`assets/rinder.jpg`

## Lokal mit Docker starten

```bash
docker build -t brandenbeef-site .
docker run --rm -p 8080:80 brandenbeef-site
```

Danach im Browser oeffnen: `http://localhost:8080`
