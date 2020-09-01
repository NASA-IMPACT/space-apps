

# Image Labeler's Data

All image data for a given event inside the Image Labeler application falls into two main 
classifications; *labeled* and *unlabeled*. *Unlabeled* data has only been organized into an Earth 
Science Event and may or may not actually show the event. This data is also referred to as 
*untagged*.

*Labeled* (or *tagged*) data has been manually reviewed and further refined with a status of 
*present* or *not present*; indicating whether the phenomenon in question is shown or not in the 
given image. This data is ready to be downloaded and used for analysis and training.

For this challenge, *labeled* data is available for immediate download (see below for directions).
Alternatively, there is an option to upload, select, and tag your own images to create a custom
dataset. 


# Labeling Images

To begin labeling, you'll first need to add your own set of images. Documentation on this topic can
be [found here.](https://nasa-impact.github.io/image_labeler_docs/html/sectionfour.html) The linked 
page explains how to populate an event by either uploading images or extracting them from satellite 
data.

Once you're satisfied with the *unlabeled* images contained inside an event, you can start assigning
labels. A walkthrough of how to classify images as *present* or *not present* is 
[shown here.](https://nasa-impact.github.io/image_labeler_docs/html/sectionfive.html)


# Downloading Labeled Images

Now that you've chosen a set of *labeled* images, its time to download this data from Image Labeler. 
There are a couple ways to download images depending on what exactly you're looking for.

When browsing the Earth Science Events list page, two download options are given. First is the 
**Bulk Download** button in the top right. Clicking this button will give the option to download
all images(both *labeled* and *unlabeled*) for any selected events. The use of *Shift+Click* or 
*Ctrl+Click* allows multiple events to be downloaded at once. 

A download button is also given for each event in the list. When clicked, a pop-up menu will prompt 
for which combination of *unlabeled*, *present*, or *not present* images you are interested in 
downloading.

Lastly, when inside an event page, individual images can be selected and downloaded. This is useful
for downloading a subset of images already classified into one of the aforementionted categories. 
Directions for performing this download can be [found here.](https://nasa-impact.github.io/image_labeler_docs/html/sectionsix.html#images)

This document provides example phenomena which have labeled datasets on ImageLabeler. You may choose to use any of the provided phenomena for your detection model.

### Transverse Cirrus Bands (TCB) 

Bands of clouds oriented perpendicular to the flow in which they are embedded. They often are seen best on satellite photographs. When observed at high levels (i.e., in cirrus formations), they may indicate severe or extreme turbulence. A labeled dataset of TCBs is available on ImageLabeler using the link below.
[Image Labeler](https://labeler.nasa-impact.net/images/transverse-cirrus-band/yes)

### Dust

Atmospheric dust consists of a mixture of solid and liquid particles suspended in the atmosphere varying in composition, source and size. Dust itself can be a boon or a bane. Dust from the Sahara desert provides nutrition to the Amazon rainforest. However, dust storms cause extensive societal impacts so detecting them is extremely important. ImageLabeler has a labeled dataset of dust which you may use for your detection model.

SPoRT?

### High Latitude Dust


### Smoke

Smoke from events such as wildfires, volcanoes, and industrial pollution cause numerous health impacts. ImageLabeler has a labeled dataset of smoke which you may use for your detection model.

Labeled geotiffs (Kumar to post)
Air quality data
CSV formatted data and labels
Contains PM2.5, GOES 16 AOD, HRRR T, RH, U and V winds, and PBL height
Cloud streets
https://labeler.nasa-impact.net/images/cloud-streets/yes

