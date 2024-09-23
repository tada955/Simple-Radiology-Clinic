## Description

This repository contains an example of a Conceptual Model of a simple radiology clinic that conforms with the HCCM Standard.
The CM is available as a website at https://tada955.github.io/Simple-Radiology-Clinic/ and a pdf.
Currently both the web and pdf version are created using [Quarto](https://quarto.org/) and manually writing the .qmd file(s).
The goal is to eventually have an electronic representation of the CM (probably in JSON or XML) and then automatically generate the web and pdf versions of the CM from this (probably by generating the .qmd file(s)).

## Simple Radiology Clinic

The CM presented here is based on the following description of a radiology clinic.

In the CT service of a radiology clinic patients:
- arrive according to a known distribution 24/7;
- check in at reception with a receptionist, which takes a uniformly distributed amount of time;
- have a scan in a CT Machine, the duration of which also follows a known distribution;
- finally leave.

Both when waiting for check in, and waiting for a scan, patients are seen in a first-in-first-out order. In addition there are dedicated staff for each CT Machine, so if the machine itself is available there will always be the staff required to perfom a scan available as well.

