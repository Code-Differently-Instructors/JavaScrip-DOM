# Javascript DOM Example

# Table of Content

- [Javascript DOM Example](#javascript-dom-example)
- [Table of Content](#table-of-content)
  - [Objectives](#objectives)
  - [About](#about)
  - [Phase 1](#phase-1)
      - [Objective 1](#objective-1)
      - [Objective 2](#objective-2)
      - [Objective 2](#objective-2-1)
      - [Objective 3](#objective-3)
      - [Bonus Objective 4](#bonus-objective-4)
  - [Phase 2](#phase-2)
      - [Objective 1](#objective-1-1)
      - [Objective 2](#objective-2-2)
      - [Objective 3](#objective-3-1)
  - [Phase 3](#phase-3)
      - [Objective 1](#objective-1-2)
      - [Objective 2](#objective-2-3)
      - [Objective 3](#objective-3-2)

## Objectives

- Phase 1
- Phase 2
- Phase 3


## About

JavaScript allows you to create interactive web pages that can respond to a user's actions. Here we will walk through phases of doing that with the DOM.


## Phase 1
Phase one will consist of us manipulating and accessing the DOM utilizing data that we will populate in the `index.html` file. Please see Below on what we will be adding to our `index.html` file:

#### Objective 1
**Please remember that `id` attributes can only be used once on each tag, should never had multiple `id` attributes with the same value, but you can do that with the `classes` attribute**
We will do the following in the `index.html` file:

- Add your `script` tag under the `body` closing tag.
- In the `body` we will add an `image`, `h1`, and `p` tags and fill each tag with some information.
- The `image` tag will contain an image of a person or place (not derogatory) and have an `id` attribute.
- The `h1` tag will contain a name for said image and have a `class` and `id` attribute.
- The `p` tag will contain a sentence about said image and have a `class` and `id` attribute. 
  
#### Objective 2
- In the `phase1.js` file is where we are going to manipulate what we created in our `index.html` file.
- In order to access and manipulate the DOM, we need to use our DOM methods, as stated in [DOM Lesson](../Dom%20Explanation.md). Here we can speak on different DOM methods there are.
- We are going to first address the `body` of the document using a DOM method.
- Lets access the `h1` tag that holds the name of the person or place we created in the `index.html` file.
- Lets change the name of the person or place we created in the `index.html` file using the DOM. 

#### Objective 2
- Lets access the `p` tag that holds the statement we wrote.
- Lets change the statement we wrote using the DOM.

#### Objective 3
- Lets access the `image` of what we created.
- Lets change the `image` of the person.

#### Bonus Objective 4
- Lets use a `for loop` to iterate over the data.


## Phase 2
Here we will create our own data and populate the document in our `phase 2` file using only the DOM.

#### Objective 1
- Create an `object` named `characterData` and it should have the following properties:
  - ID
  - name
  - alias
  - gender
  - specialty
  - image
- Next we will address the `body` of our document using the DOM.
- Create a new `h1` tag using the DOM.
- Create a new `p` tag using the DOM.
- Create a new `image` tag using the DOM.
- Declare a variable that takes in the `keys` of the `characterData` object

#### Objective 2
- Using the DOM, populate the new `h1` tag.
- Using the DOM, populate the new `p` tag.
- Using the DOM, populate the new `image` tag.

#### Objective 3
- Use the Dom to `append` the new `h1` tag data to the `body`.
- Use the Dom to `append` the new `p` tag data to the `body`.
- Use the Dom to `append` the new `image` tag data to the `body`.

## Phase 3 
We will utilize a third party API to generate data!

#### Objective 1
- Choose an API from [here](https://github.com/public-apis/public-apis) to work with.
- Lets install [Axios](https://github.com/axios/axios) to access our API. 
- Our `script` tag will need to be modified to `type = module` in our `index.html` file.
- Declare a variable name `path` with a value of where the JSON data will go once generated.
- Declare a variable called `URL` with the value of the API link you chose. 
- Make sure to require Axios.
- Make sure to require `fs`.

  
#### Objective 2
- Make Axios call to generate data. 
- Data will populate into `Data Json` file.
- Create `data.js` file and move data from `Data Json` into `data.js` file.


#### Objective 3
- import data from `data.js` file into `phase2.js` file using `import` keyword.
- Address the `body` of the document using the Dom.
- Using the `map` method, we can populate the document with our API data.
