# Asynchronous Request/Response Assessment

This project will help you assess your ability to apply the JavaScript skills that you practiced in this book.

1. Form fields
1. Collecting user input
1. `fetch()` and `then()`
1. Asynchronous state management

## Demo

<img src="./images/pen-pal-society-demo.gif" width="800px" alt="Animation of Pen Pal Society application" />

## Features

### User can choose an author

**Given** a pen pal wants to send a letter<br/>
**When** the Pen Pal app loads<br/>
**Then** there should be a select element that displays all pen pals to choose for the author

### User can choose an recipient

**Given** a pen pal wants to send a letter<br/>
**When** the Pen Pal app loads<br/>
**Then** there should be a select element that displays all pen pals to choose for the recipient

### User can choose a letter topic

**Given** a pen pal wants to send a letter<br/>
**When** the Pen Pal app loads<br/>
**Then** there should be a group of radio buttons for the user to choose a topic

### User can enter the letter body

**Given** a pen pal wants to send a letter<br/>
**When** the Pen Pal app loads<br/>
**Then** there should be textarea element in which the user can type in the letter body

### User can save letter

**Given** a pen pal wants to send a letter<br/>
**When** the Pen Pal app loads<br/>
**Then** there should be button labeled Send at the bottom of the form<br/>

---

**Given** a pen pal is done writing a letter<br/>
**When** the pal clicks the Send button<br/>
**Then** the letter should be saved in the API database<br/>
**And** the new letter should immediately be rendered in the list of letters below the form<br/>
**And** the rendered letter should display the following information

* author
* recipient
* date sent
* email address of author/recipient
* topic of letter
* content of the letter

## The Data

Below is a description of the different states to be tracked and represented in your application. You will decide on what the key names are for each piece of state and what the data types should be.

### Pen Pals

You need a collection of objects that represent the people who are in the Pen Pal Society. Each pen pal must have the following properties.

* primary key
* full name
* email address

### Letters

You need a collection of objects that represent the letters that the members of the Pen Pal Society send to each other. Properties of the letter are.

* primary key
* letter body
* who sent it
* who received it
* date sent

### Topics

You need a collection of objects that represent the topics that can be assigned to each letter.

* primary key
* label of the topic

### ERD

Before you write any code, or build your `database.json` file for your API service, build an ERD that visualizes the data () and the relationships between each resource.

## Deep Learning

Another reminder from the instruction team. This is NOT A TEST. We are not looking for 100% completion, although if you can make it work completely, then huzzah for you.

What we are looking for is effort, critical thinking about the concepts, creative thinking to bind the concepts together for a solution, and collaboration with your teammates and instruction team.

If you only get 50% of it complete, but display the above Core Skills and can demonstrate understanding of the fundamental code concepts, then you are learning and growing - which is what we care about.

## Optional Advanced Challenge

Think you have a strong understanding of asynchronous operations using `fetch()` and `then()`? In the mood to stretch your coding skills and take on a challenge? Once you complete the assessment given the features listed above, you have the option of taking on this challenge.

<img src="./images/pen-pal-society-multiple-tags-demo.gif" width="800px" alt="animation of choosing multiple topics for a letter" />

### User can choose multiple letter topics

**Given** a pen pal wants to send a letter<br/>
**When** the Pen Pal app loads<br/>
**Then** there should be a group of checkboxes for the user to choose one, or more, topics

### User can save letter with multiple topics

**Given** a pen pal is done writing a letter<br/>
**When** the pal clicks the Send button<br/>
**Then** the letter should be saved in the API database<br/>
**And** the new letter should immediately be rendered in the list of letters below the form<br/>
**And** the rendered letter should display the following information

* author
* recipient
* date sent
* email address of author/recipient
* all topics chosen

How does this change the data relationships? How should you update your ERD -- and the corresponding resources in your databse -- to reflect this change?
