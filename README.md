This **shiny** app is a reproducible example for an issue I am having with RStudio Connect.

It is simply the template app, with `library("RMySQL")` added to `server.R`.

If you run this app on a Mac, there is no problem. Similarly, there is no problem if you run this on an Ubuntu machine.

However, if you deploy this app to RStudio Connect from a Mac, there is a runtime-error involving an **RMySQL** dependency. 

If you this app to RStudio Connect from an Ubuntu machine, the app runs without error.
