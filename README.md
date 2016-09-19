# CRISPR meets Docker
### Common bioinformatic analysis involving genome editing experiments made easy with Docker


This guide uses Docker images and step by step instructions documented in IPython notebooks (bash kernel) to illustrate common CRISPR bioinformatic analysis. These are the tools currently covered: CRISPOR(https://github.com/maximilianh/crisporWebsite), CRISPResso (https://github.com/lucapinello/CRISPResso) and MAGeCK(https://sourceforge.net/p/mageck).

In this repository I cover common computational analysis involving CRISPR sequencing data:

- **Example 1**: Guide design with **CRISPOR**.

- **Example 2**: Quantification of editing efficiency, off-target effects and allele frequency from (deep)sequencing data with **CRISPResso**.

- **Example 3**: Genome wide screen with **MAGeCK**.

To make the execution of command line version of those tools as painless as possible I have created Docker images, so you don't have to install anything on your machine except for Docker. You can install Docker from here:

- Windows: https://docs.docker.com/docker-for-windows/
- Mac: https://docs.docker.com/docker-for-mac/
- Linux: https://docs.docker.com/engine/installation/

Remember to share some folder with the Docker images (from the tray icon of Docker select *Preferences...* and then the *File Sharing* tab). At least the folder that contain this repository.

Each example is organized in the following way: inside each example folder you have the **input data used an html file** that shows the execution log and the commands used to run the Docker commands. I provide also the IPython notebook file .ipynb used to create the html file, in case you want to modify it and/or run it interactively  (in this case you need to install IPython and the bash kernel).

Note: These examples are not designed to be very detailed and comprehensive but instead to be a starting point to get used to those tools. You can read more about more complex analysis in the packages documentations.

If you want to contribute with more tool/examples shoot me a message. I think this repository may be helpful for many people

BTW I am starting a lab at **Massachusetts General Hospital/ Harvard Medical School** in Boston and I am currently hiring! if you are interested in **computational challenges** in bioinformatic in genomics, CRISPR genome editing and love reproducible research practices take a look to my website for **available positions: http://pinellolab.org**
