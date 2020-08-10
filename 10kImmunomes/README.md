# 10k Immunomes Documentation

This is an overview of the 10k Immunomes project. This documentation is for researchers who intend to develop the project further. 10k Immunomes is a web portal where immunologists can explore immunologic reference datasets from healthy control subjects. This documentation provides an introduction to the project and then gives instructions on how to code your own version of 10k Immunomes.


## 10k Immunomes Resources

* [Website](https://10kimmunomes.ucsf.edu/): This is the 10k Immunomes website. The purpose of all this documentation is to allow you to understand how this website is built so that you can begin building you own version.
* [Video Tutorial](https://youtu.be/pwBs4J4xDOw): This video tutorial is a beginners overview of what the 10k Immunoems project is about. Watching the video is the best way to starting learning about 10k Immunomes.
* [Published Paper](https://www.cell.com/cell-reports/pdf/S2211-1247(18)31451-7.pdf): This is a published describing 10k Immunomes. Rading the paper is a good way to learn more about the purpose of 10k Immunomes.
* [Source Code](https://github.com/pupster90/10k_Immunomes): This github repo contains all of the source code. It's useful for scanning through the files. However, I HIGHLY reccomend using the dockerhub image when working on code.
* [Dockerhub](https://hub.docker.com/r/pupster90/10kimmunomes/tags): This docker image is by far the easiest way to start working on this project. It contains a detailed step by step tutorial on how to get website up and running, how to edit code, and how to publish final results to the server.
* [Data Files](www.google.com): This zip file contains EVERYTHING related to the 10k Immunomes project. Most importantly, it contains the raw datasets that were used to proccess the finalized version of the website.

## Getting Started

The best way to get started is by learning to use HarmonyRNA as if you were a user. This way you undertand the purpose of the project. Briefly visit the website, then watch the tutorial video. Follow the steps in the video tutorial to harmonize the example dataset. After this, read the HarmonyRNA paper and supplmentary material to learn the basic architecture of the Harmony website and to learn the methodology behnd its algorithm. Once these steps are done you can then move on to gain a deeper understanding of the code.

## Editing Code

HarmonyRNA source code is available on Github and Dockerhub. The README files on Github are a great place to learn about what the different files do in HarmonyRNA and where the best place is to start coding. However, please do not attempt to replicate HarmonyRNA by first cloning the Github repo. HarmonyRNA is an [R Shiny](https://shiny.rstudio.com/tutorial/) website with very specific settings and very specific packages installed. If you don't know what R shiny is, go through a few of the practice tutorials on their official site. After that, go to the HarmonyRNA [dockerhub](https://www.docker.com/products/docker-hub#:~:text=Docker%20Hub%20is%20a%20hosted,push%20them%20to%20Docker%20Hub) and follow the steps there to launch an [R Shiny Server](https://shiny.rstudio.com/articles/shiny-server.html) where you can run HarmonyRNA locally. [Docker](https://docs.docker.com/get-started/) is a tool that allows you to launch little pre-set-up "mini computers" from your computer. With docker you can launch HarmonyRNA in minutes. This will save you weeks are work. 

If you are interested in the example datasets used in the HarmonyRNA tutorial and would like to learn more about them, you should start by reading through the `other_code` folder on Github. The datasets were originally created as part of the 10k Immunomes project so you may need to eventually read the 10k Immunomes documentation. 

## Help and Contact

If you are another lab interested in 10k Immunomes, we are happy to have you reach out to [Atul Butte's lab](https://buttelab.ucsf.edu/). Sanchita Bhattacharya is the senior scientist and manager of this project (email: Sanchita.Bhattacharya@ucsf.edu). If you are a programmer with technical questions please reach out to the senior programmer of 10k Immunomes, Matthew Elliott (email: melliot1@ucsc.edu). We look forward to hearing from you!





