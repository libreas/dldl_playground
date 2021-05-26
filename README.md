### DLDL Workflow

Markdown zu PDF (direkt)

```
pandoc --template=header.sty --include-in-header=meta.tex -N -C --variable csquotes="true" main.md -o main_rendered.pdf
```

### Dateien

- main.md - Hauptdokument
- dldl.bib - annotierte Bibliographie
- header.sty - LaTeX Vorlage LIBREAS
- meta.tex - Metadaten mit TeX (geht auch besser :-)
- main_rendered.pdf - Ergebnis
- apaabstract.xml - CSL Style-Datei mit der das Template für DLDL definiert werden kann. Mehr zur Citation Style Language <https://citationstyles.org/>