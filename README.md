# Submission name

<h2>A technology for finding hospitals during the pandemic</h2>

## Contents

1. [Short description](#short-description)
1. [Demo video](#demo-video)
1. [The architecture](#the-architecture)
1. [Long description](#long-description)
1. [Project roadmap](#project-roadmap)
1. [Getting started](#getting-started)
1. [Running the tests](#running-the-tests)
1. [Live demo](#live-demo)
1. [Built with](#built-with)
1. [Contributing](#contributing)
1. [Versioning](#versioning)
1. [Authors](#authors)
1. [License](#license)
1. [Acknowledgments](#acknowledgments)

## Short description

### What's the problem?

During the global pandemic Covid-19,

·         It has become critical for pregnant ladies and common man seeking medical help to find hospitals for general health issues.

·         People who are new to a location or stuck at different places find it very difficult to find the directions to hospitals from their locations.

·         People with less English knowledge might not be able to use the exact phrases for google search.

·         Some people only need first aid of some general illness by mentioning their symptoms.

### How can technology help?

As this pandemic situation has created a lot of chaos in identifying the hospitals, we can guide people with the technology and help them in identifying and locating the nearby hospitals during emergency situations. We can also let the people know the symptoms, first aid and medicines for the general illness. So that even before they could reach the hospital they could do some first aid for the patients well in advance. Chatbots could be a boon and very helpful in such cases and to people with less English knowledge who find it difficult in using exact phrases for google search. 

### The idea

To overcome all these problem, we are going to configure a chatbot in IBM Cloud that helps people to feed their location and find nearby hospitals at their convenience, give directions to the hospitals to people who are new to that locality.

## Demo video

[![Watch the video]](https://youtu.be/y5eV8jUwAos)

## The architecture
![Architecture](watsonarchitecture.png)
![Video transcription/translation app](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png)

1.       The user communicates with the Watson Assistant with his query.
2.       Watson Assistant responds with the available dialog messages for default queries.
3.       When there is a user input for location and landmark, it communicates with the IBM Cloud Service to provide the required results

## Long description

During the global pandemic Covid-19,It has become critical for pregnant ladies and common man seeking medical help to find hospitals for general health issues.People who are new to a location or stuck at different places find it very difficult to find the directions to hospitals from their locations. So we thought of designing a chat bot that can address this issue. Our chatbot will help the users find the symptoms of some common health issue and other related problems. With the help of chatbot we will also be providing the first aid that can be done for their problem and the general medicines as well. If the user wants to reach hospital we will help them in finding the nearest hospitals and we will also guide them with the route for the hospital they choose. We have also added separate flows to help the Pregnant ladies and parents find a find hospital . To accomplish this we used the Watson Assistant to design the chatbot flow.  We made use of the HERE API’s to get the nearest hospital details and routing details. 

## Project roadmap

![Roadmap](roadmap.jpg)


## Built with

* [IBM Cloudant](https://cloud.ibm.com/catalog?search=cloudant#search_results) - The NoSQL database used
* [IBM Cloud Functions](https://cloud.ibm.com/catalog?search=cloud%20functions#search_results) - The compute platform for handing logic
* [IBM API Connect](https://cloud.ibm.com/catalog?search=api%20connect#search_results) - The web framework used
* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds




