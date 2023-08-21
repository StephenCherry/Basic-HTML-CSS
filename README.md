# AN ABSOLUTE BEGINNER TUTORIAL ON HTML & CSS for Beginners

Welcome to my repository for the **HTML & CSS for Beginners**! This repository contains the code and materials I've worked on during the course to learn and practice Basic HTML and CSS.

## About This Repository

In this repository, you'll find the following:

- **Lecture Code:** HTML and CSS code I've written while following along with the course lectures.

- **Projects:** Practical exercises and small projects completed as part of the course.

- **Notes:** My personal notes on important concepts, tips, and tricks related to HTML and CSS.

## How to Use This Repository

1. **Fork:** Fork this repository to your local machine:


2. **Navigate:** Browse through the different directories to access lecture code, projects, and notes.

3. **Practice:** Feel free to explore the code, experiment with it, and make changes to better understand HTML and CSS concepts.

## Prerequisites

- Basic understanding of web development concepts is recommended.
- Familiarity with version control (Git) is helpful for cloning and managing repositories.


# FORMS CREATION

 This is all about defining the basic attributes of how forms are created take user's input. The "br" tag at the end of
almost every line is just to create a simple line break to differentiate each line. Form has 2 methods which are **POST AND GET methods**

## HTML Form Elements And Its Documentation

This simple HTML document demonstrates the usage of various form input elements to collect user information. 
 Forms are a fundamental part of web development, allowing users to input data that can be submitted to a server for further processing. Below is a breakdown of some of the elements some of them are self explanatory though.

- <!DOCTYPE HTML>: This declaration specifies that this HTML document follows HTML5 standard.

- <html>: The opening tag of every HTML documents.

- <body>: The opening tag for the main content of the HTML page.

- <form action=" " method="post">: This tag defines a form that will gather user input. 

- The **ACTION** attribute specifies the URL where the form data will be sent but since i am not yet connected to the backend API that is why it is empty here. **METHOD** attribute specifies the HTTP method to be used (i am using POST).

- The **PLACEHOLDER** attribute provides a hint for the expected input from the user.

 - A Date Picker input, allowing the user to select a date while A Time Picker input, allows the user to select a time.

 - RESET: A button resets all the form inputs to their default values.

- SUBMIT: A button to submit the form data to the server for further processing.

    Below are the following operations Iperform on the following form creation.

1. **Input Text Fields**
2. **Selecting Menus**
3. **The following buttons were implemented(Check Boxes and Radio Buttons)**
4. **Text Areas and Buttons**


## Public Disclaimer: 

**The simple website project I built in this tutorial is strictly with HTML. It is just to provide an additional understanding of the HTML syntax on project**

Since i have not cover the CSS part yet, I will be using inline text formatting on this project which is consider outdated and unsupported in CSS world. However, The layout responses to Mobile devices only viewing this on a large screen might not be friendly. So using HTML I am limited to certain retrictions. I am using table for large file in this project is also considered outdated in web development. Note that: Understanding how Table functons is part of the fundamentals of web development.

   Furthermore, let me walk you through the operations i have performed in bulding this simple website project.

 1. **HTML Header:** This is used to define the website name and its description.
 2. **HTML Callout:** This is used to define the website name and the contact number.
 3. **HTML Image Insertion:** This is used to insert image into this simple website. Note that the image inserted might not as you you presumed because for security reasons your web browser is not allowed to explicitely access your local machine.
 4. **HTML Text Insertion:** This is used to insert text into this simple website.
 5. **HTML Links and Form:** This contains the insertion of links into this simple website.
 6. **HTML Tabular Data:** This contains the insertion of Texts in tabular format (ABOUT | OUR VISION | SERVICES)
 7. **HTML Project Footer:** This contains the insertion of Footer into the website.


## CSS (CASCADING STYLE SHEET)
    Cascading Style Sheet is a language used to style the presentation of HTML documents. It allows user to control the appearance of text, images and other elements on webpage.

    In the HTML-Project I developed a basic webpage using tables and inline styles attributes. Let's discuss the inefficiency of this project.
     
     1. Styling of Table border, headings and background color using inline text formatting attributes. This process is quite inefficient. There were bunch of repetitions of the same style attributes over and over again. This make the code lengthy and have some redundant codes.

     2. The content image was displayed and put together using rows and columns inside the nested tables which helps in the process of organizing the page but there were no much flexibility in the positioning of the content. So the resriction of the content gives us the inability to stack objects on one another.

     
        But in this section, We are going to explore the world of CSS which iS CASCADING STYLE SHEET. CSS helps to eliminate inline text formatting and decoration styles. It makes development process much more flexible, efficient and browser friendly. You can make CSS base on your needs , it's highly customizeable, easy to create and use.
            
            Furthermore, You can link each page on a url website to a single page and update tons of pages simultaneously. I will halt the suspense for now. But lemme show you what CSS looks like

            <style type="text/css">
                Body{
                    color: #000000 or white;
                }
                </style>
        
        Please Note that the syntax for HTML is different from CSS.


## CSS RULES!
    CSS rules are written in a cascading order, which means that the rules closer to the element will take precedence over the rules further away. The property is the name of the style that you want to change, and the value is the new value for that style. 
    
    The basic syntax for a CSS rule is:

  **The Selector:**  **The Property:**  **The Value:** 
         **Selector { property: value;}**

     So think of CSS as setting up as a catalogue of different styles and referencing to it when you need to apply them to your HTML element. 
     
     Meanwhile, you can also use CSS to style elemeents based on their class or id attributes. Whenever you are defining a class in CSS make sure you give your class name a meaningful and desriptive names for the purpose of redability.


   Let's talk about CSS types of rules.
    1. **The Internal Line Styles:** This means that the style sheet is defined in the same html document.
    2. **External Line Styles**This means the the style sheet is defined outside of the html document and link the file into the html document where tags are used.

        
## DIV ELEMENT     
    Div element is ageneric container element in HTML. It can be used to group together other ellements and style them as a single unit. The DIV element does not have any inherent meaning, so it can be used to represent any kind of content. It is an important part of the CSS development.

    To style a div element with CSS, you can use the SELECTOR to select the div element and the specify the properties that you want to change. For example, the following code will set background color of all div element to blue. div{ background-color: blue;}

    You can also use CSS to style div element based on their class or if attributes. 

## CSS IDs
    This is similar to Classes. They are defined in the stylesheet and referenced to in the url html elements.
    The primary difference is that once an id is being referenced to in an html element it cannot b used again within the same HTML file. One of the great place to use IDs is for defining CSS roles.

    However, As we proceed on this tutorial we will be using internal Line Styles formatting for the sake of this tutorial.

    Certainly! Here's a complete README file that explains the provided CSS snippet and its usage:

# Responsive CSS Layout Example

This repository contains a CSS layout example that demonstrates a responsive web layout using HTML and CSS. The layout includes a header, left and right columns, main content, and a footer. It is designed to adapt to different screen sizes, providing an optimal viewing experience on both desktop and mobile devices.

## Table of Contents

- [Introduction](#introduction)
- [Layout Structure](#layout-structure)
- [Media Queries](#media-queries)
- [Navigation Bar](#navigation-bar)


## Introduction

This CSS layout in this project showcases a slight responsive design that adapts to various screen sizes, ensuring a consistent user experience across devices. It utilizes CSS properties and media queries to reposition and resize elements as the screen size changes.

## Layout Structure

The layout consists of the following components:

- `header`: A black header with a bold font.
- `leftColumn`: A left sidebar with a blue background.
- `rightColumn`: A right sidebar with a yellow background.
- `contentColumn`: The main content area with a margin to accommodate the sidebars.
- `footer`: A footer with a black background and white text.
- `navigationBar`: A horizontal navigation bar with responsive behavior.

## Media Queries

Responsive design is achieved using media queries. The layout adjusts based on the screen size:

- When the screen size is above 840px:
  - The left column remains on the left side.
  - The right column remains on the right side.
  - The content column has a margin to avoid overlapping.

- When the screen size is 840px or below:
  - The left column is shifted below the content.
  - The right column spans the full width below the content.

## Navigation Bar

The navigation bar is styled with a black background and white text. When hovering over navigation items, they change to a darker shade. The active item is highlighted with a blue background.

Feel free to adapt and expand upon this example to create your own responsive layouts! If you have any questions or need further assistance, don't hesitate to reach out and I will keep pushing new updates. Thank you!

Created by Stephen Olujare | stephenolujare7@gmail.com | 21-08-2023


Happy Coding!


