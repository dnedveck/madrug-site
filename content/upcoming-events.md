---
title: Upcoming events
---

## March 26th, Thursday 6pm-7:30pm 

**Location:** Room 301 at Madison Public Library (201 W Mifflin St, Madison, WI)

Come join us for a talk from Rob Schwartz on a Shiny app that he developed for reporting. 

Rob will give an overview of how one feature of the app is used to generate reports by creating a formatted Excel spreadsheet, Word Doc analysis, and a PowerPoint presentation. The data used for reporting is coming from call and web form data, as well as web metrics from Google Ads and Google Analytics.

Rob will also cover how he handles errors that can occur in the app through the use of `try()`, `tryCatch()` and some custom infix functions.

More detail from Rob:

> The shiny app I maintain has various features, but feature I will be showing off is the reporting feature which creates a formatted Excel spreadsheet, a Word Doc analysis, and a PowerPoint presentation for a selected client. Essentially, the data we work with is primarily call and
web form data, but I need to integrate it with other web metrics that are pulled from both Google Ads and Google Analytics. This app works for all the clients we work with, but since there is a fair amount of change year over year, such as addition of clients or clients that left our agency, I need to use a fair amount of error control for both testing and error handling in the final app since there's a fair amount of detail that can be missed if everything crashes, as none of the 3 files will be generated if that were to happen. Moreover, since the app is hosted on a server through Digital Ocean, I don't get to see a lot of the errors that one would usually see in RStudio's console after an error has occurred.

> As such, I mainly want to cover the error control features of the app, namely through the use of try(), tryCatch() and a few custom infix functions that have been built to make error control fairly simple. My overall plan is to go over a few of the nuances of the app to explain what kind of errors I expect to see, go over the main differences between try() and tryCatch(), show some generalized examples of how either are performed and why one may be preferred over the other, and then show how I use these to make more readable infix functions that help identify problems sooner. 

## April, Thursday 6pm-7:30pm 

**Location:** Room 301 at Madison Public Library (201 W Mifflin St, Madison, WI)

Group activity -- working through a [#tidytuesday](https://www.tidytuesday.com/) dataset


-----------------


## Potential future topics

- using R for side / hobby projects
- bleeding edge of the tidyverse (video talk and follow up discussion?)
