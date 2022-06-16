# Anaconda-pakken og Jupyter Lab

## Installasjon

Anacondapakken lastar du ned frå [anaconda.org](https://www.anaconda.com/products/individual). Følg installasjonsretteleiaren der. 

## Anaconda navigator

Når du har lasta ned Anaconda er du klar til å begynna. For å komma i gang opnar du **Anaconda Navigator** som du kan søka etter med Spotlight (Mac) eller i Start-meny (Windows).

Når du opnar navigasjonsprogrammet vil det sjå ut som dette:

```{image} ../img/navigator.png
:width: 700px
:align: center
```

Her er det mange program å velga mellom. Me kjem i hovudsak til å nytta **Jupyter Lab** til programmeringa vår. 


````{admonition} Tips
:class: tip

Snarveg for å opna Jupyter Lab. Søk etter "Anaconda Prompt" på Windows eller "Terminal" på Mac.

```bash
jupyter lab
```
````

## Oppdatering
For å oppdatera heile anaconda-pakken og tilhøyrande bibliotek kan du bruka 
```bash
conda update --all
```
På eit tidspunkt får du spørsmål om du vil halda fram `[y/n]`. Skriv inn `y` (for yes) og trykk enter. 

Det _kan_ henda du må bruka
```bash
conda install -c conda-forge jupyterlab
```
for å installera den aller nyaste versjonen av Jupyter Lab, men du bør først ha oppdatert alt som skildra over. 

````{admonition} Tips
:class: tip

For å sjekka kva versjon av Jupyter Lab du har innstallert kan du skriva
```bash
jupyter lab --version
``` 
````

## Jupyter Lab

Her kjem litt om jl.
