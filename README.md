Borrowing heavily from https://github.com/EconometricsBySimulation/Shiny-Demos/tree/master/Survey, this is an R Shiny framework to conduct online survey experiments using sequential blocked randomization. 

The tricky part is storing, uploading, and downloading the blocking file ("sdata.RData"). I use rdrop2 to upload and download from Dropbox, since Shinyapps.io has no permanent storage. But if you're hosting this Shiny application on your own servers, you can skip that code.

This particular application replicates the experimental procedure of Michael Tomz (2007), a paper about audience costs in domestic public opinion of foreign policy. 
