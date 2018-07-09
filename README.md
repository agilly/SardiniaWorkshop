# Welcome !

This repository contains the supporting documents for**Workshop 2  : Hands-on tutorial for GWAS**, given at the 2018 Sardinian Summer School: From GWAS to Function.

The first part of the workshop focuses on QC and is accessible [here](http://nbviewer.jupyter.org/github/agilly/SardiniaWorkshop/blob/master/Sardinia2018-QC.ipynb).

The second part is the association per se, you can find it [here](http://nbviewer.jupyter.org/github/agilly/SardiniaWorkshop/blob/master/Sardinia2018-association.ipynb).

The instructor should point you to a local copy of the data for the project at the beginning of the workshop. If you have trouble locating it, it has been uploaded to Google Drive. Please input the following in your terminal:

```bash
wget --load-cookies cookies.txt -O data.tar.gz --no-check-certificate https://drive.google.com$(wget --save-cookies cookies.txt --keep-session-cookies -q -O- --no-check-certificate 'https://drive.google.com/uc?export=download&id=1jQnwuBnILqBWpzVmzQs6O59FRY-kfpKv' | fgrep 'uc-download-link'|sed 's/.*uc-download-link//;s/.>.*//;s/.*href..//;s/\&amp\;/\&/g') && rm cookies.txt && tar -xvzf data.tar.gz && rm data.tar.gz
```
