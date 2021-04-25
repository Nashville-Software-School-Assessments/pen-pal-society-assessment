# The Pen Pal Society

For this project, you will be building a fairly simple user interface, but the coordination of the state of the project is the goal. The person using the application can choose an author for a letter, provide the body of the letter, choose 1+ topics for the letter, and then choose a recipient.

<img src="./pen-pal-initial-form.gif" width="800px" alt="animation of filling out the letter form" />

## The Data

Below is a description of the different state to be tracked and represented in your application. You will decide on what the key names are for each piece of state and what the data types should be.

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

### Letter Topics

You need a collection of objects that represent the relationships between a letter and the topics chosen for it.

* primary key
* the letter
* the topic

### ERD

Before you write any code, or build your `database.json` file for your API service, build an ERD that visualizes this data and the relationships between each resource.
