# PlaguePY

<img src="https://img.shields.io/badge/Build-Passing-brightgreen.svg" alt="Build passing"> <img src="https://img.shields.io/badge/Licence-Apache%202.0-blue.svg" alt="Licence Apache 2.0"> <a href='https://plaguepy.readthedocs.io/'> <img src='https://readthedocs.org/projects/plaguepy/badge/?version=latest' alt='Documentation Status' /></a>

Deze repository bevat alle code, documentatie en de applicatie van het IPASS-project. Alle code bevind zich in `plaguepy/`. Dit is de library. De code maakt gebruik van en genereerd data in `data/`. De applicatie waarmee de functionaliteit aan de hand van verschillende casussen wordt getoont is te vinden in `app.ipynb`.

## Documentatie

De documentatie is te vinden in iedere functie. Tevens zijn er HTML-pagina's gegenereerd, deze zijn te vinden in `docs/build/html/index.html`. Via ReadTheDocs.io is de laatste versie van de documentatie te zien via [deze link](https://plaguepy.readthedocs.io/). De documentatie kan worden bijgewerkt met `make html`. Tevens kan de documentatie in EPUB- of LaTeX-vorm worden gegenereerd met `make epub` resp. `make latex`.

## Installatie

De library is te installeren via Pypi met pip: `pip install plaguepy`. Vervolgens kan de repository worden geimporteerd als `plaguepy`.   De benodigde libary's zijn te vinden in `requirements.txt` en te installeren met:

```bash
    pip install -r requirements.txt
```

Het is aanbevolen om met een Anaconda omgeving te werken zodat de [GEOS](https://trac.osgeo.org/osgeo4w/) uitbreiding in C goed wordt geinstalleerd. Deze komt standaard met Anaconda wanneer cartopy wordt geinstalleerd. Mocht u `cartopy` zelf willen installeren, dan is voor Windows aan te raden om de volgende pre-build [binary](https://www.lfd.uci.edu/~gohlke/pythonlibs/#cartopy) te gebruiken.

Om de code te testen kan het commando `pytest` worden uitgevoerd. Helaas zijn plots niet te testen.

***

> © Thijs van den Berg 2019
> 1740697

## Bronnen

- Malhotra, R., Dey, D., van Doorn, E. A., & Koonen, A. M. J. (2000). Traffic modeling in a reconfigurable broadband nomadic computing environment. In Proceedings of SPIE Vol. 4211: Internet, Performance and Control of Network Systems. Boston.  
- Dobrin, A. (2002). A REVIEW OF PROPERTIES AND VARIATIONS OF VORONOI DIAGRAMS. Whitman. Geraadpleegd van <https://www.whitman.edu/Documents/Academics/Mathematics/dobrinat.pdf>  
- van den Berg, T. (2009). Denbergvanthijs/AC-opdrachten. Geraadpleegd 24 juni 2019, van <https://github.com/Denbergvanthijs/AC-opdrachten>
- 9.2. math — Mathematical functions — Python 2.7.16 documentation. (z.d.). Geraadpleegd 17 juni 2019, van <https://docs.python.org/2/library/math.html>
- Distributiekasten lichtnet Den Haag | Data overheid. (2017). Geraadpleegd 22 juni 2019, van <https://data.overheid.nl/dataset/47539-distributiekasten-lichtnet-den-haag>
-Hondenpoepbakken Tilburg | Data overheid. (2017). Geraadpleegd 22 juni 2019, van <https://data.overheid.nl/dataset/58437-hondenpoepbakken-tilburg>
- How to get the filename without the extension from a path in Python? (2009, 24 maart). Geraadpleegd 24 juni 2019, van <https://stackoverflow.com/questions/678236/how-to-get-the-filename-without-the-extension-from-a-path-in-python>  - mplot3d tutorial — Matplotlib 2.0.1 documentation. (2017). Geraadpleegd 21 juni 2019, van <https://matplotlib.org/2.0.1/mpl_toolkits/mplot3d/tutorial.html>  
- mplot3d tutorial — Matplotlib 2.0.2 documentation. (2017). Geraadpleegd 21 juni 2019, van <https://matplotlib.org/mpl_toolkits/mplot3d/tutorial.html>  
- scipy.spatial.Voronoi — SciPy v0.18.1 Reference Guide. (2016). Geraadpleegd 19 juni 2019, van <https://docs.scipy.org/doc/scipy-0.18.1/reference/generated/scipy.spatial.Voronoi.html>  
- Simulation of Infectious Disease Spread. (2019). Geraadpleegd 20 juni 2019, van <http://apmonitor.com/wiki/index.php/Apps/MeaslesVirus>  
- Structuring Your Project — The Hitchhiker’s Guide to Python. (2019). Geraadpleegd 27 juni 2019, van <https://docs.python-guide.org/writing/structure/>  
- WisFaq! (2009). Geraadpleegd 19 juni 2019, van <https://www.wisfaq.nl/show3archive.asp?id=59864>  
- Zorginstellingen Utrecht | Data overheid. (2017). Geraadpleegd 22 juni 2019, van <https://data.overheid.nl/dataset/48412-zorginstellingen-utrecht>  
