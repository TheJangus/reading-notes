# Reading 07

## [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

1. Explain why we need domain modeling
- Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.
- A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

## [HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

1. Why should tables not be used for page layouts?
- Layout tables reduce accessibility for visually impaired users
- Tables produce tag soup
- Tables are not automatically responsive:

2. List and describe 3 different semantic HTML elements used in an HTML `<table>`.
- `<td>` table data - data in a cell
- `<tr>` table row - this comes before and after the table data
- `<table>` - table = gets the whole thing started/ended

## [Introducing Condeuctors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

1. What is a constructor and what are some advantages to using it?
- A constructor is a special function that creates and initializes an object instance of a class. In JavaScript, a constructor gets called when an object is created using the new keyword. The purpose of a constructor is to create a new object and set values for any existing object properties
- Automatic initialization of objects at the time of their declaration. 
- Multiple ways to initialize objects according to the number of arguments passes while declaration. 
- The objects of child class can be initialised by the constructors of base class

2. How does the term `this` differ when used in an object literal versus when used in a `constructor`?
- bind `this` to the new object, so you can refer to `this` in your constructor code


## [Object Prototypes Using a Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)

1. Explain prototypes and inheritance via an analogy from your previous work experience
- In programming terms, a prototype is an object that supplies base behavior to a second object. The second object then extends this base behavior to form its own specialization. Let’s see in the next section how our knowledge of prototypes in CSS buttons maps to JavaScript.
- an object (obj) inheriting its properties and base-behavior from another object (Object.prototype) — is what we call prototypal inheritance.
