# Script for Assignment 3

## Listening to data collection habits

An exercise designed to describe the sonic environment of New York University Abu Dhabi quickly turned into a study of human behaviour on data collection simply by gathering one additional piece of data: Location.

In data science we often procure datasets that are ready to be analysed for a particular purpose. However, the readily available datasets are rarely the raw data the are collected in an experiment. Raw data is biased, revealing imperfections in the data collection process, or even eponymous such that the analysis is sidetracked by uncovering such features. This was what we observed while generating a dataset aiming to describe the sounds around our campus. In this assignment I will attempt to provide an interpretation of certain aspects of the data pertaining to the sounds on campus, and then use the same data to examine how this sousveilance exercise without proper preprocessing can lead to deanonymization of the data.

## Data collection

Data collection was carried out using Survey123, a tool by ESRI that enables creating questionnaires that further capture the geographical location of the responder with impressive accuracy. This is the perfect tool to collect information about the location of the sounds to be able to eventually describe an acoustic landscape of our environment. Using the help of (blank) professor Wristley designed the questionnaire shown in the figure below according to our class discussion.

------- IMAGE -------

The guiding principle in its design were to find balance between the simplicity to fill the form out and the introduction of enough subjectivity in the data to describe the context of the measurements. The rationale for subjectivity comes from the idea outlined by Herz in data feminism where they argue that contextualizing data increases the impact on the final reader who is called to interpret them. As a result, we have fields for a short description of the sound, along with a larger text field for additional information and even a field to optionally upload an image. Alongside with the contextualizing information we collect the sound level, where "height" the sound was observed, and of course the location.

Here is a .csv file with the total data collected. 

------- CSV LINK ----------

## How loud is campus?

This seems like a trivial question to answer with the dataset we have collected. However it is not as straightforward as it sounds. The purpose of this section is to show how we can tackle this question in depth from a systematic point of view.

The first step is to refine the question. If one wants to find out how loud campus is using the data that we collected then plotting the frequency of observing different types levels of loudness could 
