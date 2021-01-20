# fahclient-container
Containerized FAHClient rootless and K8S ready to help [Folding@Home project](https://foldingathome.org/) research against [COVID-19](https://en.wikipedia.org/wiki/Coronavirus_disease_2019)

https://foldingathome.org/2020/03/15/coronavirus-what-were-doing-and-how-you-can-help-in-simple-terms/

## Base image

Using CentOS8 Base image for compatibility with their available [RPM](https://download.foldingathome.org/releases/public/release/fahclient/centos-6.7-64bit/v7.5/)

## Public Registry

Image on [Quay.io](https://quay.io) public registry that you can use to pull the image. 

https://quay.io/repository/redhat-emea-ssa-team/fahclient-container

** Source: https://github.com/RedHat-EMEA-SSA-Team/fahclient-container/blob/master/README.md


# HOW TO USE IT

First of all oc client installed and working

Log in to the Hub cluster from your terminal (oc login ....)

git clone https://github.com/avaleror/acm-demo.git

cd acm-demo

oc apply -k app-lifecycle/subscription/
