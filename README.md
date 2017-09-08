# webmorph
Source code for the web application, *webmorph*, and its online generator

## Requirements
Initiation of a *webmorph* project requires:
* web hosting through a server that supports PHP
* a Google Drive account

As the files required to run *webmorph* are small, storage requirements on the hosting server are generally dependent on the file size of the images to be analyzed.

Users must have internet access to submit data.

## Instructions on setting up a *webmorph* project
1. Create a [Google Form](https://www.google.com/forms/), where each entry represents one column in your resulting data table.  These need to be in short answer format.

Each entry in the Google Form will collect one measurement.  In addition to the user-generated data, there must be two entries required by *webmorph* to collect metadata: **image**, which collects the file name being viewed, and **scale**, which records how much the image has been resized to fit in the applet viewing area.

2. Submit the source code of the form to: https://www.ocf.berkeley.edu/~luchang/webmorph/generator.  This page automatically detects the Google Form input fields and provides an interface to designate data type, viewing order, and more.


## Example application
Example of use can currently be found at:

https://www.ocf.berkeley.edu/~luchang/webmorph


## Application generator
Active webmorph generator can currently be accessed at:

https://www.ocf.berkeley.edu/~luchang/webmorph/generator
