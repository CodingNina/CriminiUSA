# CriminiUSA
<h1 align="center">CrimimiUSA Shiny Application </h1>

<p> The goal of this project is to show different rates of four main crimes: Murder, Assault, UrbanPop and Rape, accross the US State, in an choropleth map.
The Shiny App has two widgets: one for selecting which crime to select and a slider to choose the range you're interested into.
  </p> 
<br>


<h2> Installation </h2>

```R
# first install the following packages, if not installed
install.packages("shiny")
install.packages(c("maps", "mapproj"))
```

<h2> Usage </h2>

```R
# To run it, please use the following command:
shiny::runGitHub("CrimeRateUSA", "CodingNina", ref ="main")
```

<h2> Dataset </h2>
<p> The study consists of 1 dataset named "CrimeRateUSA" from year 1973. 
This data set contains statistics, in arrests per 100,000 residents for assault, murder, and rape in each of the 50 US states in 1973
</p>
