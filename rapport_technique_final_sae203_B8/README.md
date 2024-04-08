# Installation de services réseaux

Auteurs: [Dylan ZHANG](), [Nathan MARQUIS](), [Lorenzo FLAGOTHIER]()

Groupe : B8

## Methode de conversion

(Avant de convertir assurez-vous de vous mettre au répertoire du fichier MarkDown src/ )

### Conversion du fichier Markdown en fichier HTML

```
pandoc --css ../styles/pandoc_styles.css --toc -s nomDuFichier.md -o ../html/nomDuFichier.html
```

Dans notre cas ce sera:

```
pandoc --css ../styles/pandoc_styles.css --toc -s rapportFinalMD.md -o ../html/rapportFinalHTML.html
```

Cela permet de convertir à l'aide de pandoc le fichier MarkDown en fichier HTML
Le style css sera également intégré dans la conversion et le --toc permet de générer une table de matière automatiquement après la conversion.

---

### Conversion du fichier MarkDown en fichier PDF

```
pandoc --css ../styles/pandoc_styles.css --toc -s nomDuFichier.md -o ../pdf/nomDuFichier.pdf
```

Dans notre cas ce sera:

```
pandoc --css ../styles/pandoc_styles.css --toc -s rapportFinalMD.md -o ../pdf/rapportFinalPDF.pdf
```

Cela permet de convertir à l'aide de pandoc le fichier MarkDown en fichier PDF.Le style css sera également intégré dans la conversion et le --toc permet de générer une table de matière automatiquement après la conversion.

---