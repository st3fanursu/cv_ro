---
name: Stefan
surname: Ursu
position: "Student"
address: "Cluj-Napoca, Cluj, Romania"
phone: +40 745 29 39 24
email: "stefan.wrsw@gmail.com"
istagram: hi.im.steff
github: st3fanursu
linkedin: www.linkedin.com/in/ștefan-ursu-8065442b0
date: "`r format(Sys.time(), '%B %Y')`"
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = FALSE, warning = FALSE, message = FALSE)
library(vitae)
```

# Descriere

  Am finalizat recent studiile în domeniul economiei și am dobândit cunoștințe solide în R, SQL și manipularea spreadsheet-urilor în timpul cursului online oferit de cei de la Google. Sunt motivat să-mi încep cariera în analiza datelor și sunt dornic să învăț și să-mi dezvolt abilitățile în acest domeniu. Sunt o persoană organizată, cu abilități excelente de rezolvare a problemelor și cu o atitudine proactivă față de învățare și dezvoltare.

  Alte lucruri despre mine, am crescut intr-o familie modestă. Am fost la un pas sa ajung jucator profesionist de fotbal la vârsta de 16 ani, dar am decis să-mi termin studiile. Nu am niciun frate/soră.


# Educația

```{r}
library(tibble)
tribble(
  ~ Degree, ~ Year, ~ Institution, ~ Where,
  "Liceul", "2015-2019", "Colegiul Națion „Calistrat Hogaș”", "Piatra-Neamț, România",
  "Facultatea", "2019-2022", "UBB : Facultatea de Științe Economice și Gestiunea Afacerii", "Cluj-Napoca, România",
  "Masteratul", "2022-prezent", "UBB : Facultatea de Științe Economice și Gestiunea Afacerii", "Cluj-Napoca, România"
) %>% 
  detailed_entries(Degree, Year, Institution, Where)
```

# Ultimele locuri de muncă

```{r}
tribble(
  ~Where, ~Year, ~Post, ~Location,
  "OMV-Petrom", "2020", "Lucrător platformă și casier", "Piatra-Neamț, NT-România",
  "OMV-Petrom", "2021", "Lucrător platformă și casier", "Cluj-Napoca, CJ-România",
  "Pink Pony", "2023", "Expo și ajutor de ospătar", "Mackinack Island, MI-USA"
) %>% 
  detailed_entries(Where, Year, Post, Location
  )
```

# Aptitudini

```{r, results='asis', out.height="80%", out.width="10%"}
tribble(
  ~Type,~Nimic, ~Where,
  "Muncă în echipă","", "OMV-Petrom, Pink Pony și în timpul studiilor și a voluntariatului",
  "Tableu","", "În timpul programului „Google Analitics Specialization”",
  "Spreadsheets","", "În timpul programului „Prepare Data for Explorationand” și „Process Data from Dirty to Clean”",
  "Microsoft Excel","", "În timpul programului „Prepare Data for Exploration” și „Process Data from Dirty to Clean”",
  "SQL","", "În timpul programului „Prepare Data for Exploration” și „Process Data from Dirty to Clean”",
  "R - programare","", "În timpul programului „Data Analysis with R Programming”",
  "Economics and Finance","", "Cunoștiințe dobândite în timpul studiilor de licență și masterat",
  "Rezolvarea de probleme","", "În timpul programului „Google Data Analytics Specialization” și a studiilor"
) %>%
  detailed_entries(Type,Nimic, Where
  )
```

# Muncă de voluntar

```{r}
tribble(
  ~Organization, ~What, ~When,
  "Untold", "Am contribuit activ la coordonarea și implementarea festivalului, asigurându-mă că evenimentul s-a desfășurat în conformitate cu standardele ridicate și că participanții au avut o experiență pozitivă.", "2022",
) %>%
  detailed_entries(Organization, When, What
  )
```

# Certificate

*TOATE DE MAI JOS SUNT LINK-URI, DESCHIDE-ȚI ÎNTR-UN TAB NOU*

-   [Google Data Analytics Specialization](https://www.coursera.org/account/accomplishments/specialization/U4EF8A2QLBZF)
-   [Analyze data to answer questions](https://www.coursera.org/account/accomplishments/verify/MQGGAWXD3WVU)
-   [Data Analysis with R programing](https://www.coursera.org/account/accomplishments/verify/YXB6UPD2J8EQ)
-   [Prepare data for exploration](https://www.coursera.org/account/accomplishments/verify/SWC5D38FTK2U)
-   [Process data from Dirty to Clean](https://www.coursera.org/account/accomplishments/verify/G7YWK3TFS9GT)
-   [Share data through the Art of Visualization](https://www.coursera.org/account/accomplishments/verify/9JZNJ6CB5ASE)
-   [Ask questions to make Data-Driven Decisions](https://www.coursera.org/account/accomplishments/verify/SYQRES9WWMU9)
-   [Foundations: Data, Data, Eveywhere](https://www.coursera.org/account/accomplishments/verify/W57L9ANJYSA2)
