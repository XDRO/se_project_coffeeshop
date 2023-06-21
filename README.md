# Practicum Coffee Shop

This is the second project of the Web Development program at Practicum. It was created using HTML and CSS, based on the design brief.

## Project features

- Semantic HTML5
- Flexbox
- Positioning
- Flat BEM
- A custom form
- CSS animation and transform

## Plan on improving the project

Add your ideas here :)

## A quick description of this project and it's purpose

- It is my second project in software engineering, so the purpose of this was for me to gain more familiarity with HTML5, Flexbox, Poistioning, Flat BEM, Forms, and CSS animation as well as transformation.

### Some highlights of this project

- The highlights of this project to me, would be the HTML5 organization, and proper use of BEM classes (this was quite a challange for me, but was accomplished with time and effort) and CSS organization. Every CSS class is ordered in the same flow as the HTML5, making it easy and convenient to navigate, for the most part.

### Features and Functionality

- Links applied
- Forms applied with different types. These have been made easy for the user to understand what needs to be put in what place.
- Youtube video embeds

### Instructions on deployment and system requirements

- VsCode (or an IDE of your choice)
- Basic knowledge of HTML5, and CSS as well as an understanding of how to clone repositories.
- Knowledge of adding changes and commiting them.
- (If new to coding like myself then here are some commands you can run)
- git add -A (to add files that have been changed)
- git commit -m "" (as well as any message that leaves a description for the changes that you made, in between the quotation marks)
- git status (after commit to ensure you are working with a clean branch)
- git push (to push changes to repository)

### Plans for updating the project

- Needs checkbox to be customizable, I was having difficulties with hidding the overflow. Not until continuing further through the lesson did I become reminded of this property and to apply to the parent div.
  /\* input[type="checkbox"] {
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  margin: 0;
  border-radius: 100%;
  display: grid;
  place-content: center;
  }

input[type="checkbox"]::before {
transform: scale(0);
} \*/

- Some of the properties to make this possible have already been applied, but it needs much more I believe.

- The CSS of course could be seperated into seperate files and linked through and @import to reduce the seemingly endless scrolling that has to be down to navigate down to the class you need.

- Image in header needs to be fixed so when you adjust screen size it does not overlap the title.

- The vh in reservation needs to be edited to fill the entire section or shortend(I've messed with this quite a bit, when I have it on one screen it fully covers the section, but on another it comes up short)
- I just updated it too 200vh on the .reservation class in CSS to fill the whitespace (not sure if this is the best approach or if further changes will be implemented to this property in the future)
