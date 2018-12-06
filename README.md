# mod_2_project_ds102218

Thesis -- Show the correlation between R voters and the chosen independent variables

    --Bonus Thesis: Assuming those correlations remain the same (ceteris paribus), how are the independent variables trending?

    --Per SeanAbu's "predict" question, we are trying to predict how a Texas voter will decide given their congressional district-level population data.

    --Dependent Variable
      --Proportion of Texans who vote for Republicans

        --Elections in Scope (2018 Midterms)
          --U.S. Senate
            --https://enrpages.sos.state.tx.us/public/nov06_331_race0.htm
          --Gubernatorial
            --https://enrpages.sos.state.tx.us/public/nov06_331_race37.htm
          --Congressional Races (32 Districts)
        --Election result data saved to "results_csvs"

    --Independent Variables
      --Data: Texas census data from 2017 (Texas_District_all.csv)
      --what if we assigned the raw district population data to a county?
      --In-Scope:
        --Income and Benefits (In 2017 inflation-adjusted dollars)
          --Mean household income explanation
            --We're using mean rather than median, because we want to be sensitive to districts with HNW households
            --Side Bar: Find rich oil barron living in the middle of nowhere
        --Baby Boomers
          --Population's percentage of baby boomers and older (Born before 1964)
            --data groups 53/54 aged people in with 50-54 group; we've decided to use 20% of this range to obtain entire baby boomer-plus population
        --Race
          --Proportion of white voters
        --Born in TX?
          --Looking at US Born population
          --Proportion of voters born and raised in TX vs. born in U.S. and moved to TX
        --Education
          --Share of population that attained at least an Associates' degree
        --Family Make-up
          --


Fun Bonus:
  --Is there any correlation between most popular Buc-ee's and voting habits (i.e. likelihood of voting, party preference)?
  --Do the stars at night have

Grammar Nazi:
  --Texas' vs. Texas's
    --Chicago: https://www.chicagomanualofstyle.org/qanda/data/faq/topics/PossessivesandAttributives/faq0043.html
    --MLA: https://style.mla.org/apostrophes-three-ways/
    --WaPo: https://www.washingtonpost.com/election-results/texas-16th-congressional-district/
    --tl;dr Texas's

Old assumptions:

--Independent Variables
  --Data: Texas census data from 2017 (Texas_District_all.csv)
    --Population Age
    --Proportion of population by race
    --Owners vs. Renters
    --Place of Birth
    --Ancestry
    --Residency, one year Ago
    --Educational Attainment
    --Average Age
      --Mean age of voters 18+
      --data groups 18/19 y.o. in 15-19; we've decide to use 20% of this range in order to obtain entire voting Population
      --Other ind. options (Source unidentified)
        --
