This example demonstrates how to use the core functions in the `shinyhelper` package:

* `helper()`  -  this augments each shiny tag (input or output) with an icon of your choice
* `use_shinyhelper()`  -  this goes in your ui.R script, and is a wrapper round `shinyjs::useShinyjs()`
* `observe_helpers()`  -  this goes in your server.R script, and creates the event handlers for bringing up your help pages.

