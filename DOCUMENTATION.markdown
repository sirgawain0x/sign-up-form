## 1.	Tell me about your proudest professional achievement.  It can be a personal or school project.

One particular proud moment in my professional career is winning an award from the State of California Businesses for Best Recording Label of 2018. What made me most proud was it was a business I built on my own and accomplished recognition for my art and business knowledge.

## 2.	Tell me a about a book, blog, article or GitHub repo you read or liked recently, and why you like it and why you should recommend I do the same. 

One book I've been reading is Hurricanes by Rick Ross. The book is an autobiography and goes into detail about the struggles in life that he had to face to achieve his success. The book has a lot of motivational and influential exceperts. I would recommend someone to read it because it reads like a great movie.

## 3.	If you were to describe to a 7-year old what Availity does, what would you say? 

They build apps for doctors.

## 4. Coding Exercise

isMatchingBrackets.js

## 5. Coding Excerise

## Installation

Ensure you have a recent version of [node & npm](https://nodejs.org/en/download/) or [yarn](https://yarnpkg.com/en/docs/install) installed.

All of the following steps run on the command line within this directory. You can substitute `npm` for `yarn` depending on your preferences.

Install all the necessary packages:

```
npm install
```

## Build

To build for distribution:

```
npm run build
```

All of the final output will be dropped into the [/dist/](./dist) folder.

## Server

Run a local server that will automatically compile your code & refresh when you save a change!

```
npm run serve
```

---

## Folder Structure

```
/exported-item/
|-- /build/ - Build scripts
|  |-- gulpfile.js - The tasks for the main build process
|  |-- util.js - Utilities used by the tasks
|
|-- /src/ - Your code
|  |-- index.template.html - The wrapper around your compiled HTML that includes any external stylesheets and scripts
|  |-- index.partial.(html|pug|haml|...) - The raw HTML input or preprocessor equivalent
|  |-- style.(css|scss|less|...) - The raw CSS input, or preprocessor equivalent
|  |-- script.(js|ts|coffee|...) - The raw JavaScript input, or preprocessor equivalent
|
|-- /dist/ - The compiled output after running `npm run build`
|  |-- index.html
|  |-- script.js
|  |-- style.css
|  |-- /dist/
|  |-- /src/
```