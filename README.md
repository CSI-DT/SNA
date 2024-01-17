# SNA

Social Network Analyses - Analysis of social contacts in confined indoor environments.

The aim of this repository is to collect the analyses performed by the [CSI:DT research group](https://www.slu.se/en/faculties/vh/research/forskningsprojekt/not/precision-livestock-breeding/) to better understand social interactions and animal movement in dairy cows. The focus of this repository will be on R, using a variety of functions and packages to study animal movement, social behavior and time budgets in dairy cows.

## Content

Core methods to analyse social contact data:

-   `scripts/stERGM_tutorial.Rmd`: This stERGM tutorial replicates the analysis performed in [Marina et al. (2023)](https://doi.org/10.3168/jds.2023-23483), Rmarkdown version.

-   `scripts/stERGM_tutorial.html`: This stERGM tutorial replicates the analysis performed in [Marina et al. (2023)](https://doi.org/10.3168/jds.2023-23483), html version.

Animal raw and processed files:

-   `data/raw/Phenotypes_LateLactationGroup.csv`: Information about the dairy cows.

-   `data/raw/Interactiondata/` : This folder contains the adjacency matrices, computed independently for each functional area ("FeedingArea","RestingArea") and each day (i.e., 24 h) of the 14 days considered in this study using position data.

-   `data/raw/Relationshipdata/`: This folder contains the kindergarten effect matrix, the lactational effect matrix and the additive relationship matrix calculated from the pedigree.

-   `data/processed/Figure1.jpg`: Schematic map of the free-stall barn.

Output obtained from the analyses:

-   `output/Figure2_FA.gif`: Animated transition between the social networks detected in the feeding area.

-   `output/Figure2_RA.gif`: Animated transition between the social networks detected in the resting area.

## Participants in the CSI:DT project

-   Lars Rönnegård (DU & SLU): Principal investigator.
-   Per Peetz Nielsen (RISE)
-   Carsten Kirkeby (KU)
-   Volker Krömker (KU)
-   Freddy Fikse (Växa Sverige)
-   Anna Skarin (SLU)
-   Moudud Alam (DU)
-   Keni Ren (SLU)
-   Maya Katrin Gussmann (KU)
-   Svenja Woudstra (KU)
-   Ida Hansson (SLU)
-   Hector Marina (SLU)

![](https://www.slu.se/globalassets/ew/org/inst/hgen/projektbloggar/social-cows/gruppfoto_230615_webb.jpg)

## Contributing

Pull requests are welcome. Please make sure to update tests as appropriate.

## License

[SLU](https://www.slu.se/)
