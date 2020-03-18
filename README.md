# Protokolle

Öffentliche Protokolle von Vorstandssitzungen und Versammlungen von [de-RSE e.V.](https://www.de-rse.org/).

## Ausdrucken

Um ein druckfertiges PDF aus einem Markdown-Dokument zu erstellen eignet sich unter Linux der folgende Befehl für [pandoc](https://pandoc.org/):

```bash
rm print.pdf; pandoc Vorstandssitzungen/Protokoll-Vorstand-deRSE-2019-05-17.md -V geometry:margin=2.5cm -o print.pdf
```

Ggf. ist noch die Optinon `--pdf-engine=xelatex` hilfreich falls es Probleme mit Umlauten gibt.
