## **R/Medicine 2020 Conference - Quick Rundown**

[R/Medicine](https://events.linuxfoundation.org/r-medicine/) was virtual this year, so I finally got to attend. Great speakers, fantastic mix of topics, and really well organized. Both R/Med and csv,conf used Crowdcast - my favourite of the many virtual conference platforms I've experienced this year.

There was a *lot* of information packed into this 2.5-day conference, so I haven't had time to process everything, but here's a quick list of interesting things that I need to read more about later.

Currently the recordings are available on [Crowdcast](https://www.crowdcast.io/e/rmedicine2020) for registrants, but I've tried to link to open sources below. Check out [@r_medicine](https://twitter.com/r_medicine) or [#RMedicine2020](https://twitter.com/hashtag/RMedicine2020) for recaps and conversations. 

* [Tidymodels/machine learning workshop](https://tmv.netlify.app/site/) - this was fantastic, now just need to use this again so I can remember it!

* Reading material:
    * [Double dipping](https://twitter.com/lucylgao/status/1299763664644313089) - fix by conditioning on hypothesis selection procedure (preprint in prep)
    * [HealthyR](https://healthyr.surgicalinformatics.org/) - training & resources for health data analysis
    * [Arcus Education](https://education.arcus.chop.edu/) at Children's Hospital of Philadelphia

* Shiny apps:
    * [{shinyviz}](https://github.com/riinuots/shinyviz) - template Shiny app for summarizing & visualizing categorical data; customize for your own data
    * [{shinyfit}](https://github.com/ewenharrison/shinyfit) - template Shiny app for linear/logistic/etc. regression analysis; customize for your own data
    * [tidyCDISC](https://nate884.shinyapps.io/tidyCDISC/) - Shiny app to explore & visualize ADaM-format clinical trial data; slides [here](https://rmed-tidycdisc.netlify.app/); will be on GitHub "soon"
    * [{nDSPA}](https://github.com/riyuebao/nDSPA) - Shiny app & package for working with spatial omics data
    * [READi Tool](https://github.com/btbeal/readi) - Shiny app for evaluating real-world data - creates custom PubMed search from input; summary [here](https://sop.washington.edu/choice/research/research-projects/readi/); still in beta testing ([app](http://34.210.151.228:3838/READi/) seems to be down as of 9/4/2020)

* Packages - general R/R Markdown/Shiny:
    * [{listdown}](https://github.com/kaneplusplus/listdown) - programmatically generate R Markdown files from named lists
    * [{dbplyr}](https://dbplyr.tidyverse.org/) - do data manipulation on SQL server, then just pull what you need into R for analysis
    * [{drake}](https://github.com/ropensci/drake) - plan your workflow so you don't have to keep repeating the computationally intensive parts
    * [{pkgdown}](https://pkgdown.r-lib.org/) - build a website for your R package (i.e. pkg documentation as knowledge repository)
    * Docker & [{holepunch}](https://github.com/karthik/holepunch) - share research compendia on GitHub
    * [{shinyviz}](https://github.com/riinuots/shinyviz) - template Shiny app for summarizing & visualizing categorical data
    * [{shinyfit}](https://github.com/ewenharrison/shinyfit) - template Shiny app for linear/logistic/etc. regression analysis
    * [{golem}](https://github.com/ThinkR-open/golem) - opinionated framework for building robust Shiny apps
    * [{pool}](https://github.com/rstudio/pool) to make a separate data layer for your workflow/Shiny app

* Packages - Publications/communication
    * [{gtsummary}](https://github.com/ddsjoberg/gtsummary) - make publication-ready analytical and summary tables. Example:
    <img src="https://github.com/ddsjoberg/gtsummary/raw/master/man/figures/README-tbl_merge_ex1-1.png" width="500" />
    
    * [{finalfit}](https://github.com/ewenharrison/finalfit/blob/master/README.md) - make nice tables for publication; similar to {gtsummary}

* Packages - Clinical data
   * [{survminer}](https://github.com/kassambara/survminer) - make Kaplan-Meier curves with ggplot
    * [{ggconsort}](https://github.com/higgi13425/ggconsort/) - programatically generate CONSORT diagrams; still in development
    * [{foreceps}](https://github.com/kaneplusplus/foreceps) - processing & wrangle ADaM-format clinical trial data; will be available in a few weeks
    * [{collaboratoR}](https://github.com/kamclean/collaborator) - work with REDCap data in R
    * [{redcapR}](https://github.com/OuhscBbmc/REDCapR) - interact with the REDCap API

* Packages - Other
    * [{treeheatr}](https://trang1618.github.io/treeheatr/) - decision tree + heatmap visualization for better interpretability. Example:
    ![example from treeheatr github](https://trang1618.github.io/treeheatr/reference/figures/unnamed-chunk-4-1.png)
    * [{runcharter}](https://github.com/johnmackintosh/runcharter) - plot & analyze run charts to track changes over time. Example:
    <img src="https://github.com/johnmackintosh/runcharter/raw/master/man/figures/runs_below-1.png" width="500" />
    
    * [{twilio}](https://github.com/seankross/twilio) - connect to Twilio API to send text messages from R    
    






