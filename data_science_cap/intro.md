# Counterfeit Medicine Sales Prediction

## Introduction

Counterfeit medicines are fake medicines which are either contaminated or contain
wrong or no active ingredient. They could have the right active ingredient but at
the wrong dose. Counterfeit drugs are illegal and are harmful to health. `10%` of
the world's medicine is counterfeit and the problem is even worse in developing
countries. Up to `30%` of medicines in developing countries are counterfeit.

Millions of pills, bottles and sachets of counterfeit and illegal medicines are being
traded across the world. The World Health Organization (WHO) is working with
International Criminal Police Organization (Interpol) to dislodge the criminal networks
raking in billions of dollars from this cynical trade.

Despite all these efforts, counterfeit medicine selling rackets don’t seem to stop
popping here and there. It has become a challenge to deploy resources to counter these;
without spreading them too thin and eventually rendering them ineffective.
Government has decided that they should focus on illegal operations of high networth
first instead of trying to control all of them. In order to do that they have
collected data which will help them to predict sales figures given an illegal
operation's characteristics.

## Formal Problem Statement

We would like to make example out a few of these counterfeiters but the challenge
is what yardstick can we employ to determine the 'big fish(es)' that we can use as
scape goat to send a strong message to these clandestine communities and equally
serve as deterrent. After considering numerous features and attributes of these
counterfeiters, we resolved to zero in on their sales figures. To this end we shall
put to use the power of machine learning to scientifically predict current and future
counterfeiters and stop them in their tracks for good!

We would train a model on  data we have collected secretly over the years on their
operations. The data dictionary of the data is as follows:




|Variable               |        Description/Values                                                                    |
|:----------------------|:--------------------------------------------------------------------------:|
|Medicine_ID            |Alphanumeric identification number;Normal Integer                           |
|Counterfeit weight     |weighted percentage attached to each medicine;continuous                    |
|District_ID            |District identification number;alphanumeric                                 |
|Active since           | Year(s)monitoring started till date;Integer                                |
|Medicine MRP           | Medicine price quotes/codes;continuous                                     |
|Medicine type          |The type of the medicine,categorical                                        |
|Side effect level      |The severity of the side effect associated with the medicine;categorical    |
|Availability Rating    |The rate at which the medicine is availablecontinuous                       |
|Area type              |The level of development of an area                                         |
|Area city type         |City rate level;categorical                                                 |
|Area district level    |The level of the area district.categorical                                  |
|Counterfeit sales      |sales figures of counterfeited drugs/medicine                               |
