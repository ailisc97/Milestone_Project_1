## Table of Contents
* [Purpose](#Purpose)
* [User Experience Design (UX)](#User-Experience-Design)
  * [User stories](#User-Stories)
    * [First Time Visitor Goals](#First-Time-Visitor-Goals)
    * [Returning Visitor Goals](#Returning-Visitor-Goals)
    * [Frequent User Goals](#Frequent-User-Goals)
  * [Structure](#Structure)
  * [Design](#Design)
    * [Colour Scheme](#Colour-Scheme)
    * [Typography](#Typography)
    * [Imagery](#Imagery)
    * [Wireframes](#Wireframes)
    * [Differences to Design](Differences-to-Design)
* [Limitations](#Limitations)
- [Features](#Features)
    * [Existing Features](#Existing-Features)
    * [Future Features](#Features-Left-to-Implement)
* [Technologies](#Technologies)
* [Testing](#Testing)
    * [Test Strategy](#Test-Strategy)
      * [Summary](#Summary)
      * [High Level Test Cases](#High-Level-Test-Cases)
      * [Out of Scope](#Out-of-Scope)
    * [Test Results](#Test-Results)
    * [Testing Issues](#Issues-and-Resolutions-to-issues-found-during-testing)
* [Deployment](#Deployment)
    * [Project Creation](#Project-Creation)
    * [GitHub Pages](#Using-Github-Pages)
    * [Locally](Run-Locally)
* [Credits](#Credits)
  * [Content](#Content)
  * [Media](#Media)
  * [Acknowledgements](#Acknowledgements)
  * [Comments](#Comments)

# Milestone Project 1
## Purpose
This website was created for Milestone Project 1 in the Software Developement Course in Code Insitute.
The languages used in this project are languages that ive learned so far in the course, HTML, CSS and User Centric Design.

The live website can be found [here]

## Griffith Park Leisure Centre Responsive Website

![Website Mock Up]

The Giffith Park Leisure Centre is based on an imaginary sport centre based in Dublin 4. The benefit to this website is that people can check out the two main sports (swimming and basketball) that are in this sport centre.
The client requested to show the muliple different classes in the facility. The client requested to show off the Coaches in the sports centre and to give a little bit of a bio about the different Coaches.
Having the Gallery was a great way to show off the most recent championships with the different teams. The Contact page was a necessity for the website and it was essential for the users who had different questions about the multiple different classes avilable.


*** 
## User Experience Design

### User stories
#### First Time Visitor Goals
* As a First Time user, I want to easily and quickly navigate the website to learn more about the Leisure Centre.
* As a First Time user, I want to easily and quickly navigate the website to check what sports are played in this Sport Centre.
* As a First Time user, I want to view the website and content clearly on my mobile device.
* As a First Time user, I want to find ways to follow the Leisure Centre on different social media platforms.
* As a First Time user, I want to know the loaction and opening hours of the Centre.
#### Returning Visitor Goals
* As a Returning user, I want to check the times for any of the swimming or basketball classes.
* As a Returning user, I want to contact the centre for any questions I have.
* As a Returning user, I want to know which coach teaches what class.
#### Frequent Visitor Goals
* As a Frequent user, I want to check to see the results and pictures of the new competitions.
* As a Frequent user, I want to check to see when the next swimming races are on.
* As a Frequent user, I want to sign up to the Newsletter so I can always be in the loop.

### Structure
All Pages will have a Navigation bar (using Bootstrap) at the top of the Webpage that allows the User to easily navigate between the different pages of the site.
The Navigation bar is collapsable into a hamburger menu on a Mobile device, this will help maximise the space.
The purpose of this is to fulfill user story:
> *As a First Time user, I want to view the website and content clearly on my mobile device.

Bootstrap will be used to make the Website responsive by the use of media queries and/or the Boostrap Grid system.

All pages will be responsive to multiple different devices, Phone, Tablets and Desktop. Using Bootstrap and media max and min widths will help with the font not being too big/small,
or the photos being too big/small.
The purpose of this is to fulfill user story:
> As a First Time user, I want to view the website and content clearly on my mobile device.

The Home Page will contain an about us, which talks about the orgins of the club.
The purpose of this is to fulfill user story:
> * As a First Time user, I want to easily and quickly navigate the website to learn more about the Leisure Centre.

Under the about us on the Home Page there will be a small discription of the sports that are played in this club.
The purpose of this is to fulfill user story:
>* As a First Time user, I want to easily and quickly navigate the website to check what sports are played in this Sport Centre.


All pages will contain a Footer Element with Opening Hours, Contact Information, Location and Responsive Social Media Icons. The icons used will be
from font-awesome. Once clicked they will take the user to the desired Social Media platform. 
The aim of the Footer elements are to fulfill user stories:
> * As a First Time user, I want to find ways to follow the Leisure Centre on different social media platforms..<br>
> * As a First Time user, I want to know the loaction and opening hours of the Centre.


The Swimming Page will contain information about the multiple different classes and the the times they are on at. Below this the User can see the Coaches and read about their bio and learn about what class they teach.
The purpose of this is to fulfull user stories:
>* As a First Time user, I want to easily and quickly navigate the website to check what sports are played in this Sport Centre.
>* As a Returning user, I want to check the times for any of the swimming or basketball classes.
>* As a Returning user, I want to know which coach teaches what class.
>* As a Frequent user, I want to check to see when the next swimming races are on.



The Events Page will contain information on upcoming and previous events run by the Club. There will be a booking form 
connected to this page. 
The purpose of this is to fulfull user stories:
> As a Returning user, I want to order tickets online in advance of events so that I am garanteed entry.<br>
> As a Frequent user, I want to check to see if there are any new upcoming events.

The Gallery Page will contain several Galleries with 8 photographs in each from various activities the club has engaged in.
The purpose of these galleries are to fulfill user story:
> As a Frequent user, I want to check to see if there are any new photos and media from the clubs activities.

The Contact Page will contain a form that can be used to contact the Club through the website. This will also contain a check 
box that will allow the user to sign up for the Clubs newsletter in order to keep up to date with the club.
The purpose of this Page is to fulfill user stories:
> As a Returning user, I want to contact the organisation so I can request more information.<br>
> As a Frequent user, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation.

Throughout the desktop version of the website there will also be an alert at the top of all pages except the Events Page. This
can be engaged with by the user. The resulting action will open up a modal form to allow the user to book event tickets.