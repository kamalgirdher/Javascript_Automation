# Javascript_Automation
This repository is to learn Javascript automation from scratch.

To start with Javascript automation, you should have fair understanding of the HTML page source code and CSS styling. Let's begin with that.

Open trello dashboard(https://trello.com) in chrome. And open Developer Tools (Ctrl+Shift+I or F12). We gonna play with Elements and Console tabs frequently.

Elements tab allow you to access page source and Console allows you to fire js commands.


## Commands Overview and Object Identification using CSS

#### 1. document

> Document object represents HTML document that is currently open in the browser. It has various properties. The way a document content is accessed and modified is called the Document Object Model, or DOM.

When we type **document** in console and hit ENTER, we get complete html document.

[document](/images/document.png)


#### 2. document.querySelector

#### 3. document.querySelectorAll

#### 4. Using Tag Name
document.querySelector('div')

#### 5. Using ID
document.querySelectorAll('#trello-root')


document.querySelectorAll('#notification')



#### 6. Using Tag and ID together
document.querySelectorAll('p#notification')
