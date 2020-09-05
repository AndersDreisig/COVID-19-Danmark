# Figurer for smitteudvikling i Danmark baseret på data fra SSI

## Data

Data er hentet på [SSI's COVID-19 overvågningsside](https://www.ssi.dk/sygdomme-beredskab-og-forskning/sygdomsovervaagning/c/covid19-overvaagning) hvor de data der kan downloades opdateres mandag-fredag.

De datasæt der er brugt her er:
- Antal testede og antal positive tests for hele landet
- Antal testede og antal positive tests per kommune
- Antal testede og antal positive tests per aldersgruppe for hele landet
- Antal nyindlagte og antal døde for hele landet

Der går typisk 2-3 dage før testdata for de seneste dage er helt opdateret. På de grafer der inkluderer testdata er de seneste to dage derfor ikke medtaget.   

## Plots

I mappen [figures -> artikel](https://github.com/ktbaek/COVID-19-Danmark/tree/master/figures) kan man finde opdaterede figurer fra artiklen [Kurven over smittede i Danmark er misvisende](https://link.medium.com/Ldu11b9IQ8).

### Dagligt antal positive tests
Plottet viser antallet af positive tests for hele landet. Den optrukne linje viser det løbende gennemsnit baseret på et vindue på 7 dage. 

![](https://github.com/ktbaek/COVID-19-Danmark/blob/master/figures/fig_1_test_pos.png)

### Dagligt antal testede og antal positive tests
Plottet viser det total antal testede personer og antallet af positive tests for hele landet. Den optrukne linje viser det løbende gennemsnit baseret på et vindue på 7 dage. 

![](https://github.com/ktbaek/COVID-19-Danmark/blob/master/figures/fig_2_tests.png) 

### Daglig procentdel positive tests
Plottet viser procentandelen af positive tests ifht. hvor mange der er testet for hele landet fra 1. maj. Den optrukne linje viser det løbende gennemsnit baseret på et vindue på 7 dage. 

![](https://github.com/ktbaek/COVID-19-Danmark/blob/master/figures/fig_3_pct.png) 

### Dagligt antal positive tests og procent positive tests
Plottet sammenligner forløbet af kurven over antal positive tests og kurven over positivandelen for hele landet fra 1. maj. Den optrukne linje viser det løbende gennemsnit baseret på et vindue på 7 dage. 

![](https://github.com/ktbaek/COVID-19-Danmark/blob/master/figures/fig_4_tests_pct.png) 

### Dagligt antal nyindlagte og døde
Plottet viser antal nyindlagte og antal døde for hele landet. Den optrukne linje viser det løbende gennemsnit baseret på et vindue på 7 dage. 

![](https://github.com/ktbaek/COVID-19-Danmark/blob/master/figures/fig_5_hosp.png) 

### Dagligt antal nyindlagte og antal positive tests
Plottet sammenligner hvornår kurven over nyindlagte toppede med hvornår kurven over antal positive tests toppede. Den optrukne linje viser det løbende gennemsnit baseret på et vindue på 7 dage. 

![](https://github.com/ktbaek/COVID-19-Danmark/blob/master/figures/fig_6_postest_hosp.png) 

### Ugentligt antal positive tests og antal testede for hver kommune (kommuner med flest smittede)
Plottet viser det ugentlige antal positive tests og antal testede for kommuner som på et tidspunkt i perioden fra 1. juli til nu har haft over 10 ugentlige positive. 

![](https://github.com/ktbaek/COVID-19-Danmark/blob/master/figures/all_muni_pos_vs_test_july.png) 

### Ugentlig procentandel positive tests for hver kommune (kommuner med flest smittede)
Plottet viser den ugentlige procentandel af positive tests for kommuner som på et tidspunkt i perioden fra 1. juli til nu har haft over 10 ugentlige positive. 

![](https://github.com/ktbaek/COVID-19-Danmark/blob/master/figures/all_muni_pct_july.png) 

### Ugentlig procentandel positive tests for hver kommune (alle 99 kommuner)
Plottet viser den ugentlige procentandel af positive tests for alle kommuner. 

<img src="https://github.com/ktbaek/COVID-19-Danmark/blob/master/figures/all_muni_weekly_pos_pct_tile.png" height="1000" class="center"/>


### Ugentlig incidens for hver kommune (alle 99 kommuner)
Plottet viser det ugentlige antal positive tests per 100.000 indbyggere for alle kommuner. 

![](https://github.com/ktbaek/COVID-19-Danmark/blob/master/figures/all_muni_weekly_incidens_tile.png)











