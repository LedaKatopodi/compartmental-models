# compartmental-models

Implementation of a 6-compartment model (SEIARD) for the modeling of COVID-19.

![Trains](/aes/trains.jpg)

## 📗 Introduction

Compartment models are a very general modelling technique, often applied to infectious diseases. The population of interest is assigned to compartments with descriptive labels, with the individuals progressing through compartments when their status changes. The simplest compartmental model that is often used in an epidemiological framework is the Susceptible-Infected-Recovered (SIR) model. 

The progression of individuals between compartments/ epidemiological states is expressed via a network of Ordinary Differential Equations, the rates and parameters of which are calibrated based on the population of interest and real-life epidemiological data.

## 🔑 Prerequisites

Please make sure that you have [COPASI](http://copasi.org) installed on your computer.

## 👟 Walkthrough

The COPASI implementation of the 6-compartment SEIARD model is based on the work of [Zhao and colleagues](https://idpjournal.biomedcentral.com/articles/10.1186/s40249-020-00735-x). Parameter selection was carried out, as proposed by Zhao et al., based on epidemiological data from Hunan Province, China. 
