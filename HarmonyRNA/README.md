# HarmonyRNA Documentation

This is an overview of the HarmonyRNA project. This documentation is for reserchers who intend to develop the project further. HarmonyRNA is a web tool for harmonizing RNA-Seq data in TPM and counts format. The documentation provides and introductory explanation about the project and then gives advice on how to go about coding your own version of it. Below is a list of all available resources related to HarmonyRNA:

**List of HarmonyRNA Resources**
* [Website](http://harmonyrna.ucsf.edu/): This is the HarmonyRNA website. The purpose of this documentation is to allow researchers and programmers to understand how this website is built so that they can begin building their own version of it.
* [Video Tutorial](https://youtu.be/lm3t6yaIlV8): This video tutorial is a beginners overview of what the HarmonyRNA is about and how to use it. Watching the video is the best way to begin learning about harmonyRNA. The video shows how to harmonize data steb-by-step using an example dataset.
* [Paper](https://drive.google.com/file/d/16xouMFAHRIXzRuIgKzalHpPLNAwJRUgS/view?usp=sharing): This is a preprint paper describing HarmonyRNA (to be published in Bioinformatics). Reading the paper is a good way to learn more about the purpose of 10k Immunomes. It also describes the novel TPM harmonization algorithm that was created for HarmonyRNA. You may also be interested in reading the [supplemental material](https://drive.google.com/file/d/1BjGXj2Do185-p6RNSwJMO4RS6djdJ4G1/view?usp=sharing).
* [Dockerhub](https://hub.docker.com/r/pupster90/combat-seq): This docker image is by far the easiest way to start working on the HarmonyRNA project. It contains a detailed step by step tutorial on how to get the website up and running, how to edit code, and how to publish final results to a shiny proxy server.
* [Github](https://github.com/pupster90/harmonyrna): This github repo contains all of the source code. It's useful for scanning through the files. However, I HIGHLY reccomend using the dockerhub image when working on code. The github repo also has README files that provide thorough descriptions about all the source files.
* [10k Immunomes Documentation](https://github.com/pupster90/buttelab_documentation/tree/master/10kImmunomes): HarmonyRNA was used to harmonize data from the 10k Immuomes project. The 10k Immunoms data is also the example dataset that's up on the website and that's used in the tutorial video. To learn more about 10k Immuomes, you should read it's documentation.

## Getting Started

The best way to get started is bying learning to use HarmonyRNA as if you were a user. This way you undertand the purpose of the project. Briefly visit the website, then watch the tutorial video. Follow the steps in the video tutorial to harmonize the example dataset. After this, read the HarmonyRNA paper and supplmentary material to learn the basic architectue of the Harmony website and to learn the methodology behnd its algorithm. Once these steps are done you can then move on to gain a deeper understanding of the HarmonyRNA code if you like.

## Editing Code

HarmonyRNA source code is available on Github and Dockerhub. The README files on Github is a great place to learn about what the different files are in HarmonyRNA and where the best place is to start coding. However, please do not attempt to replicate HarmonyRNA by first cloning the Github repo. HarmonyRNA is an [R Shiny](https://shiny.rstudio.com/tutorial/) website with very specific settings and very specific packages installed. If you don't know what R shiny is, go through a few of the practice tutorials on their official site. After that, go to the HarmonyRNA [dockerhub](https://www.docker.com/products/docker-hub#:~:text=Docker%20Hub%20is%20a%20hosted,push%20them%20to%20Docker%20Hub) and follow the steps there to launch an [R Shiny Server](https://shiny.rstudio.com/articles/shiny-server.html) where you can run HarmonyRNA locally. [Docker](https://docs.docker.com/get-started/) is a tool that allows you to launch little pre-set-up "mini computers" from your computer. With the docker tutorial you can launch HarmonyRNA in minutes. This will save you weeks are work and stress. 

If you are interested in the example datasets used in the HarmonyRNA tutorial and would like to learn more about them, you should start by reading through the `other_code` folder on Github. The datasets were originally created as part of the 10k Immunomes project so you may need to eventually thead the 10k Immunomes documentation. 



## Help and Contact





